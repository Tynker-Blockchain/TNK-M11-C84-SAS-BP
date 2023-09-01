Generate hash value of fixed length
===================================


In this activity, you will have to generate a hash value of fixed length with the help of a fixed prime number.


<img src= "https://s3.amazonaws.com/media-p.slid.es/uploads/1525749/images/10640526/pasted-from-clipboard.png" width = "521" height = "92">


Follow the given steps to complete this activity.


* Open the file hash.py.


* Create variables to store a prime number and a hash length of your choice.  

```sh
    prime = 31
   	hashLength = 8
```

* Calculate the hash value using the equation “(hashValue * prime + ord(char))”. You can write your own equation too!

```sh
    hashValue = (hashValue * prime + ord(char))
```
    	    
* Use the mod operator to reduce the hash to the fixed length.

```sh
    hashValue = hashValue % 10 **  hashLength
```

* Convert the hash value to a fixed-length string by padding with zeros if necessary.

```sh
    hashValue = str(hashValue).zfill(hashLength)
```

* Save and run the code to check the output.
