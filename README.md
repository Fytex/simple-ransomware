# Just a Simple Ransomware made in C


This ransomware uses XOR cypher to encrypt the files. It will only affect non-system files under User desktop's directory. This is limited to User's directory but you can specify another relative instead of Desktop's one or None by changing **RELATIVE_FOLDER**'s value in main.c.

Once you run the program it will check if the first file is encrypted or not. If it´s not encrypted it will encrypt all the not encrypted others and vice versa.

In case you want to have it in a pen to auto-execute but at the same time avoiding running it in your own computer when inserting the pen you could add the following key and value to your system's variable. 

Key: H43_xor_encryption 

Value: H43


Leave a star in this project if you liked :)

Don't be evil because I don't take any responsability for your bad use :)
