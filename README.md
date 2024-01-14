# Color-Code-Encryption-In-Python-


Hi I'm Flin from South Africa,  I am trying to create a Color Code Encryption  that is random using 4 Colors for each individual character
Of a pass phrase. I hope more experienced programmer's can contribute to this public project  or perhaps fuse this type of Encryption 
With other Encryption Types, making it worth the while.  I personally thank all contributors. 
Let me know how this project can be bettered and fused with existing Encryptions. 

Okay so I will show you a preview of my example code below:


Here's a simple Python code example that allows you to create a 4-color multiple character selection encryption for a password:import random

def encrypt_password(password):
    color_options = ['white', 'red', 'yellow', 'blue']
    encrypted_password = ''

    for char in password:
        selected_color = random.choice(color_options)
        encrypted_password += f'[{selected_color}] {char} '

    return encrypted_password.strip()

# Example usage:
password_to_encrypt = "securepassword"
encrypted_result = encrypt_password(password_to_encrypt)
print(f"Original Password: {password_to_encrypt}")
print(f"Encrypted Password: {encrypted_result}")

# This code defines a function encrypt_password that takes a password as input and randomly selects a color for each character from the given color options. 
# The result is an encrypted password string with color codes.

# Let me know what the thoughts are of this project.  

# Original Idea was to make a program that lets you select a color each time after typing a character,  number or special character of the original password/ pass phrase. 
# I need help with that idea. 
# I wanted the password to be more tricky so that password loggers can be useless. 

# Does Anyone Understand My Idea & How It Can Be Used In Other Ways As well Making Passwords Safer. 


# Feel free to email me and be in Touch.   flin199019@gmail.com   

# Thanks Everyone 
