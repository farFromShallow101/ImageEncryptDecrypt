# ImageEncryptDecrypt
An image encryption and decryption project on JAVA<br>Uses XOR cipher to do both the encryption and decryption.<br><br>

# Why XOR cipher is used?
When we XOR a byte with a key to get the result, if we XOR the result with the same key again, then we get the original byte back.<br>Thus we can use the same cipher function to perform both the encryption and decryption. <br><br>

# Warning
Using this cipher on images of larger size will take a lot of time and can also result in overheating issues on regular laptops.<br>Preferably, use this cipher on images of size lesser than 200 KB.
