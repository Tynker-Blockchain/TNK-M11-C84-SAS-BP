Generate a Hash Value using ASCII Values
===================

In this activity, you will learn to generate hash values based on ASCII values of characters in an input string.


<img src= "https://s3.amazonaws.com/media-p.slid.es/uploads/2071954/images/10637840/SA1.gif" width = "521" height = "281">


Follow the given steps to complete this activity.


* Open the file hash.py.


* Define a function to generate the hash value by adding the ASCII values of each character to the input string.

```sh
	def generateHash(inputString):
		hashValue = 0
		for char in inputString:
        hashValue += ord(char)
```
  
* Create the inputString value for giving text and print the inputString and its stored text value.

```sh
	inputString = "Hello, Convert me into a hash."
  	print("Input String:", inputString)
```


* Create the hash value for input string by calling the function generateHash() and print it by first storing it in a variable.

```sh
	hashValue = generateHash(inputString)
	print("Hash value:", hashValue)
```
		
* Save and run the code to check the output.
* You can create your own hash function by changing the equation to create a hash or try changing the arithmetic operator to see how the hash value changes.
