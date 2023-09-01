Validate the Data Received
==========================


In this activity, you will learn to validate the hash data received.


<img src= "https://s3.amazonaws.com/media-p.slid.es/uploads/1525749/images/10640126/final.gif" width = "521" height = "236">


Follow the given steps to complete this activity:


* Open the file app.py.


* Check a condition for getting an argument request from form 1 as f1.

```sh
    elif request.args.get("form") == "f1":
```

* Fetch and store the sender, receiver, amount, and hash data from the form.
```sh
	else:
        sender = request.form.get("sender")
        receiver = request.form.get("receiver")
        amount = request.form.get("amount")
        hash = request.form.get("hash")
```

* Using concatenation, pass the form data as a single argument to the generateHash() function to generate a validation hash. Store the new hash as validationHash.

```sh
    validationHash = generateHash(sender+receiver+amount)
```

```What will you change in the code to display the correct notification?```

```The notifications within the if and the else blocks will need to be swapped.```

```sh
    if validationHash == hash:
        message= "Success"  `
    else:
        message = "Failed"
```

* Create a “validation” dictionary and store “message”, “blockHash”, and “validationHash” keys in it with their respective values.

```sh
    validation = { 
               "message": message,
               "blockHash": hash,
               "validationHash": validationHash 
        }
```

* Save and run the code to check the output.
