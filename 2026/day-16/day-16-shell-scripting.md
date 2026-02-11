Task 1: Your First Script

#!/bin/bash
echo "Hello World"

ubuntu@ip-172-31-47-192:~/scripts$ ./hello.sh 
Hello World

Task 2: Variables

#!/bin/bash

NAME="Aditya"
ROLE="Devops Engineer"

echo "My name is $NAME and my role is $ROLE"

ubuntu@ip-172-31-47-192:~/scripts$ ./variables.sh 
My name is Aditya and my role is Devops Engineer

Task 3: User Input with read

#!/bin/bash

read -p "Enter your name " NAME
read -p "Enter your favourite tool " TOOL

echo "Hello $NAME , your favourite tool is $TOOL"

ubuntu@ip-172-31-47-192:~/scripts$ ./greet.sh 
Enter your name Aditya

Task 4: If-Else Conditions


read -p "Enter the file name " filename

if [ -f $filename ]; then
        echo "File Exists"
else
        echo "File do not exists"
fi

ubuntu@ip-172-31-47-192:~/scripts$ ./file_check.sh 
Enter the file name aditya
File do not exists

read -p "Enter number: " number

if [ $number -gt 0 ]; then
    echo "Number is positive"
elif [ $number -lt 0 ]; then
    echo "Number is negative"
else
    echo "Number is zero"
fi

ubuntu@ip-172-31-47-192:~/scripts$ ./check_number.sh 
Enter number: 8
Number is positive
ubuntu@ip-172-31-47-192:~/scripts$ ./check_number.sh 
Enter number: -1
Number is negative
ubuntu@ip-172-31-47-192:~/scripts$ 

Task 5: Combine It All

# Store service name in a variable
service_name="nginx"   # change this to sshd or any service

# Ask the user
read -p "Do you want to check the status of $service_name? (y/n): " answer

if [ "$answer" = "y" ]; then
    # Check service status and print active/inactive
    status=$(systemctl is-active "$service_name")
    echo "Service '$service_name' is $status."
else
    echo "Skipped."
fi

ubuntu@ip-172-31-47-192:~/scripts$ ./server_check.sh 
Do you want to check the status of nginx? (y/n): y
Service 'nginx' is inactive.
ubuntu@ip-172-31-47-192:~/scripts$ ./server_check.sh 
Do you want to check the status of nginx? (y/n): n
Skipped.
ubuntu@ip-172-31-47-192:~/scripts$ 


