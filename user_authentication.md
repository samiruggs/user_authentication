# User Authentication

username = input("Username: ")
password = input("Password: ")
is_logged_in = False

if username == 'samiruggs@12':
    if password == 'wisdom':
        is_logged_in = True
        print("Login Successful")
elif username != 'samiruggs@12':
    if password == 'wisdom':
        is_logged_in = False
        print("Invalid Username")
elif username == 'samiruggs@12':
    if password != 'wisdom':
        is_logged_in = False
        print("invalid Password")
else:
    print("Username and Password invalid")