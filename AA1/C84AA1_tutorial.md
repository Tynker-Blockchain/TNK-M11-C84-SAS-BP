Debug the generateHash() function 
=================================

In this activity, you will learn to debug the code to the return hash value of every character using ASCII.


<img src= "https://s3.amazonaws.com/media-p.slid.es/uploads/1525749/images/10640491/pasted-from-clipboard.png" width = "521" height = "60">


Follow the given steps to complete this activity.:
* Open the file hash.py.


* Run the code and check if each character gets hashed using an ASCII code.


* Replace the if condition with a for loop to iterate through every character in the input string instead of an if condition.

```sh
    for char in inputString:
```
    	    
* Add the encrypted characters to the hashValue variable. 

```sh
    hashValue += ord(char)
```
* Save and run the code to check the output.
