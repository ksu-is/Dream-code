Commit Changes 

import random

def generate_username(name, color, animal):
    # Extracting first letter of each input
    initials = name[0].lower() + color[0].lower() + animal[0].lower()
# I started with this in order to start the process or randomizing your username and password using information that you will give in your input. 

# Generating a random number between 1000 and 9999
    rand_num = random.randint(1000, 9999)
    
    # Combining initials and random number to create username
    username = initials + str(rand_num)
# I used these commands in order to further randomize the username and password by adding numbers and combing it with the first part. 

# Taking inputs
    name = input("Enter your name: ")
    color = input("Enter your favorite color: ")
    animal = input("Enter your favorite animal: ")
# these will be the inputs for the project that generate the username and password.

# Printing username and password
    print("Generated username:", username)
    print("Generated password:", password)
This command will tell the user their user name and password as an output after all the inputs.

#First code before testing 
import random

def generate_username(name, color, animal):
    # Extracting first letter of each input
    initials = name[0].lower() + color[0].lower() + animal[0].lower()
    
    # Generating a random number between 1000 and 9999
    rand_num = random.randint(1000, 9999)
    
    # Combining initials and random number to create username
    username = initials + str(rand_num)
    
    return username

def generate_password(name, color, animal):
    # Generating password by combining name, color, and animal
    password = name.capitalize() + '_' + color.lower() + '_' + animal.lower()
    
    return password

def main():
    # Taking inputs
    name = input("Enter your name: ")
    color = input("Enter your favorite color: ")
    animal = input("Enter your favorite animal: ")
    
    # Generating username and password
    username = generate_username(name, color, animal)
    password = generate_password(name, color, animal)
    
    # Printing username and password
    print("Generated username:", username)
    print("Generated password:", password)

if __name__ == "__main__":
    main()
# Inputs and outputs of tested code
Enter your name: jabari Oneal
Enter your favorite color: Purple
Enter your favorite animal: Snake 
Generated username: jps8883
Generated password: Jabari oneal_purple_snake 
# the code ran how I wanted it to run the ouputs of the code where exactly what I wanted them to be 

purpose = input("What are you using this password for? ")
# I added this line of code so that what you are using the username and password for are imbeded in them so that it is easier to remember 


purpose = input("What are you using this password for? ")
# i added this line of code in order for you to kind of be able to remember what username and password you used for what purpose
