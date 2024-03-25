<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/MuslehMutahhar/Password-Fortress/tree/main">
    <img src="https://github.com/MuslehMutahhar/Password-Fortress/blob/main/resources/logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">PasswordFortress</h3>

  <p align="center">
    Generate encrypted password and share with secure.
   
  </p>
</div>





<!-- ABOUT THE PROJECT -->
## About The Project
<div align="center">
<img src="https://github.com/MuslehMutahhar/Password-Fortress/blob/main/resources/main_windows.png" alt="Logo" width="600" height="500">
</br>
</br>
PasswordFortress is a sophisticated password encryption and decryption tool developed in Python, equipped with a user-friendly graphical interface. It is designed to provide a secure and efficient way to manage sensitive information, particularly passwords. PasswordFortress harnesses the power of cryptography to ensure that your passwords are stored and handled with the utmost security.

Core Features:

+ Encryption & Decryption: Utilizes advanced cryptographic techniques to encrypt and decrypt passwords securely.
+ Intuitive GUI: Features a custom tkinter-based interface that is easy to navigate, ensuring a seamless user experience.
+ Password Management: Efficiently handles password storage and retrieval, helping users manage their credentials with ease.
+ File Handling: Allows users to save encrypted passwords in files, ensuring safe storage and easy retrieval.
+ Versatility in Usage: Suitable for both personal and professional settings where password security is paramount. 
</br>
</br>
Ideal Users:
</br>
Individuals looking for a secure way to manage their passwords.
Professionals in need of a reliable tool to handle sensitive information.
Organizations seeking an efficient solution for secure credential management.</br>
</div>



## Built With

<a href="https://www.python.org">
<img src="https://github.com/MuslehMutahhar/Password-Fortress/blob/main/resources/py_icon.png" alt="Icon" width="32" height="32">
</a>
&nbsp;
<a href="https://customtkinter.tomschimansky.com">
<img src="https://github.com/MuslehMutahhar/Password-Fortress/blob/main/resources/ctk_icon.png" alt="Icon" width="32" height="32">
</a>



<!-- USAGE EXAMPLES -->
## Usage
</br>

### SUMMARY

1. Starting the Application:
Run the PasswordFortress_gui.py script in a Python environment with the required dependencies (tkinter, cryptography, PIL).
2. Encrypting a Password:
Enter the password you wish to encrypt in the provided field.
Click on the 'Encrypt' button to encrypt the password. The encrypted password along with a key file will be saved in a zip archive.
3. Decrypting a Password:
To decrypt a password, select the appropriate key file and the encrypted password file using the dropdown menus.
Click on 'Decrypt' to display the decrypted password.
4. Additional Features:
Use the 'Copy' button to copy the password to the clipboard.
The 'Send by Email' feature allows you to share the encrypted password securely.
Access the project's GitHub repository directly through the GUI for updates and information.
Exiting the Application:
Click the 'Exit' button to safely close the application.
</br>

### DETAILED
####  GENERATE AND ENCRYPT
##### By default, a 12 characters length password is generated, you can generate another length by changing the value or write your own password.
###### Once the password is generated click on **Encrypt**, PasswordFortress then creates three files.
- One is a text file containing the encrypted password.
- The second one is the *.key that is a crucial file to decrypt the encrypted password.
- The last one is a zip file containing both files previously quoted. The two files (.key and .txt) will be available in the combobox fields (as well as inside the directory where the script is launched) above the Decrypt button.

<img src="https://github.com/MuslehMutahhar/Password-Fortress/blob/main/resources/files.png" width="750" height="500">



#### DECRYPT
##### When you encrypted a password, the generated .key and .txt files are named by the timestamp.Select the same .key and .txt then click on **Decrypt**.The password will be shown in the first field.
#### The password is automatically copied to the clipboard by clicking anywhere in the text field.

<img src="https://github.com/MuslehMutahhar/Password-Fortress/blob/main/resources/decrypt_screenshot.png" width="750" height="600">


#### SEND ENCRYPTED PASSWORD BY EMAIL
###### Clicking on the **Send button** will open a filedialog where you can choose the zip file (that contains both key and text files), then the application MAIL (OSX) will be launched with the zip file attached to a new email. Write the mail of the person you want to send to and click on send.

<img src="https://github.com/MuslehMutahhar/Password-Fortress/blob/main/resources/send_screenshot.png" width="600" height="500">



