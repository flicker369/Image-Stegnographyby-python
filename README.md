# Image-Stegnographyby-python
here we are using many modules for the proper functioning of our application **tkinter //message box ,fielddialog are more specific modules from tkinter **os **hashlib **json **PIL //image,image are specific modules used from pillow(PIL) **os the functioning of this desktop application : login window :here you enter the usernameand password ,the password is hashed through the SHA-256 algorithm encoder window :here we input the image ,pass key and secret message,this combines message and passkey(string) and converts it into binary format and places them in the image using LSB format that means it is place in the pixels (rgb) at the least bit decoder window: this extracts the LSB bits placed in image pixels are extracted and then deconverted into string and places the message there
login window-![Screenshot 2024-09-09 133756](https://github.com/user-attachments/assets/6e18011a-af4b-4082-91ec-6a47eb06bd70)
              ![Screenshot 2024-09-08 192900](https://github.com/user-attachments/assets/c1b83f3c-8120-4027-835f-02867952a619)

encoder window-![Screenshot 2024-09-09 134202](https://github.com/user-attachments/assets/1a4e6a59-52b3-4afd-a14c-db24eed56817)
                ![Screenshot 2024-09-08 193516](https://github.com/user-attachments/assets/c5a16d25-02dd-43b5-beff-41ff5b19d3f3)
                ![Screenshot 2024-09-08 193531](https://github.com/user-attachments/assets/acda3f6d-42d5-4cd8-bf8c-915bda48d49a)

decoder window-![Screenshot 2024-09-09 134833](https://github.com/user-attachments/assets/e5c5a7f7-16a4-47ca-8e03-1963dcf24d8c)

