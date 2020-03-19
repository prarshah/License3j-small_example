
License3j
(https://github.com/verhas/License3j)

Pros: 
1. Open source license manager that you can use free
2. Has apache license
3. To protect the license file from any manipulation, the license file will be signed using a digital signature. The algorithm used to sign the license file is RSA which is an asymmetric algorithm. This means the key that is used to sign the file has a public and private part and theoretically it would not be possible to manipulate the license file using only one part of the key.
   Include custom data in the license file so you have the ability to easily store your customer information in the license file.
4. Provision to tie the generated license to an individual's machine using machine unique identifier.
5. License is saved to a file it can be saved binary, base64 or text
6. We can create a key pair, license, add features to the license using an interactive application available from a separate project at https://github.com/verhas/license3jrepl ( which is also opensource )
7. MethodCall for license verification.
8. Magic bytes prevents loading to prevent accidental loading of non-license files or corrupted files.
9. The hardware binder class that binds a license to a certain hardware.


Process:
https://docs.google.com/presentation/d/1Bd0qwV478e8zF_IvQADY0DtJA1o_kXJXA0CQUtUe_Bs/edit?usp=sharing


