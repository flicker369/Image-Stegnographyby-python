# Image-Stegnographyby-python
here we are using many modules for the proper functioning of our application **tkinter //message box ,fielddialog are more specific modules from tkinter **os **hashlib **json **PIL //image,image are specific modules used from pillow(PIL) **os the functioning of this desktop application : login window :here you enter the usernameand password ,the password is hashed through the SHA-256 algorithm encoder window :here we input the image ,pass key and secret message,this combines message and passkey(string) and converts it into binary format and places them in the image using LSB format that means it is place in the pixels (rgb) at the least bit decoder window: this extracts the LSB bits placed in image pixels are extracted and then deconverted into string and places the message there
