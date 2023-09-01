Generate a Hash Value Using an Algorithm
===================

In this activity, you will learn about the secure hashing algorithm (SHA)and use it to encrypt the block data.


<img src= "https://s3.amazonaws.com/media-p.slid.es/uploads/2071954/images/10637841/SA2.gif" width = "521" height = "281">


Follow the given steps to complete this activity.


* Open the file hash.py.


* Import the hashlib library to use the hashing techniques.

```sh
    import hashlib
```  


* Create a hash object by using SHA sha256().
```sh
    hash_object = hashlib.sha256()
```

* Update the hash object to accept the input string.

```sh
     hash_object.update(input_string.encode('utf-8'))
``` 	

* Generate the hash value for the input string using the hexdigest() method.
```sh
    hash_value = hash_object.hexdigest()
```

* Save and run the code to check the output.
