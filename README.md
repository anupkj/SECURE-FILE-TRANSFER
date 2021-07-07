# SECURE-FILE-TRANSFER

As users trust over different platform for sharing sensitive information has decreased. This is a secure file transfer mechanism that takes place between two peers without using any server for communication. We are using peer to peer communication for sending file.

For secure transmission of file, we are sending encrypted file with encryption done with a symmetric key. That key is simultaneously mailed to the client(other peer). The client can use the OTP to decrypt the file.

This eliminates the possiblity of intercepting the sensitive document.

Run server.c and client.c simultaneouly. A random key would be developed and sent to the client's entered mail ID. Encrypted file will have name as cipher_FileName.
same file would be decrypted on client side when client will enter the OTP correctly.
