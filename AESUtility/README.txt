AES Utility README File

Step 1: open cmd window
Step 2: change directory to src folder to access java file.
Step 3: Type command
	AESU -e[d] -k key <-i inital_vector> -m mode -in input_file -out output_file
	AESU: Calls program.
	-e[d]: either encrypts file -e or decrypts file -d.
	-k: Required
	key: here is where you enter the key with 16, 24, or 34 characters. Used for encryption and decryption.
	-i: is optional. Required for all modes, exept optional for "ecb" mode.
	initial_vector: input initial vecotor 16, 24, or 34 characters.
	-m: Required
	mode: enter encryption mode (ecb, cbc, cfb, ofb, or ctr).
	-in: Required
	input_file: enter path to the document that you will be encrypting (plaintextfile.txt).
	-out: Required
	output_file: enter the path to your document where the encrypted/decrypted document should be saved (cipherfile.txt).

Information: I have a Mac OS. And openssl does not work with Mac OS, so there was no way for me to check this information. When running it try Windows OS.