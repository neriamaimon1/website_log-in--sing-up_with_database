import os

name = input("Hey new user whats your name?\n")



#Creating Username
username = input("ok "+name+" lets pick an username!\n")
check_username = username + ".txt"
while os.path.exists(check_username) == True:
    username = input("This username already exists Try one another\n")
    check_username = username + ".txt"



#Creating Password
password = input(""+name+" lets choose a password!\n")
while len(password) < 5:
    print("Your password need to be longer!")
    password = input("Choose stronger password\n")



#add to the database
username1 = username + ".txt"
add1 = open(username1, "w")
add1.write(""+username+"\n")
add1 = open(username1, "a")
add1.write(password)
add1.close()



#log in
print("LOG IN")
print("Hey user please log in!")



#check if username exists
def check(username):
    return os.path.exists(checkuser)
checkuser = input("enter your username:\n")
checkuser = checkuser + ".txt"
while not check(checkuser):
    checkuser = input("This username not exists Try again\n")
    checkuser = checkuser + ".txt"



#check whats is the password
checkpassword = open(checkuser)
linepass = checkpassword.readlines()
checkpassword.close
linepass = linepass[1]
print("Ok we found you!")



#check password
checklinepass = input("Whats is your password:\n")
while checklinepass != linepass:
    print("worng password!")
    checklinepass = input("Try again, whats is your password:\n")
print("YOU LOG IN SUCCESSFULLY!")
