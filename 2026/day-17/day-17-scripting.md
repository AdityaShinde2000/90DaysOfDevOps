
#!/bin/bash

for fruit in apple mango banana orange grapes
do
        echo "Fruit is : $fruit"
done

for i in {1..10}
do
        echo "Number is $i"
done


#!/bin/bash

if [ $# -eq 0 ];then
        echo "No arguments passed"
        exit 1
fi

echo "This is First argument $1 "

ubuntu@ip-172-31-44-1:~/scripts$ ./greet.sh 
No arguments passed
ubuntu@ip-172-31-44-1:~/scripts$ ./greet.sh adi
This is First argument adi 
ubuntu@ip-172-31-44-1:~/scripts$ 

#!/bin/bash


read -p "Enter the number " num

while [ "$num" -ge 0 ]
do
        echo "$num"
        num=$((num - 1))
done

echo "Done"

ubuntu@ip-172-31-44-1:~/scripts$ vim while_loop.sh 
ubuntu@ip-172-31-44-1:~/scripts$ ./while_loop.sh 
Enter the number 5
5
4
3
2
1
0
Done
ubuntu@ip-172-31-44-1:~/scripts$ 

#!/bin/bash


PACKAGES="nginx curl wget"

for pkg in $PACKAGES
do
  if dpkg -s $pkg &> /dev/null; then
    echo "$pkg is already installed"
  else
    echo "Installing $pkg..."
    apt install -y $pkg
  fi
done

#!/bin/bash

set -e 

mkdir /tmp/devops-test || echo "Directory Already Exists"
cd /tmp/devops-test
touch test.txt

echo "All Steps Completed successfully"

ubuntu@ip-172-31-44-1:~/scripts$ ./safe_script.sh 
mkdir: cannot create directory ‘/tmp/devops-test’: File exists
Directory Already Exists
All Steps Completed successfully
ubuntu@ip-172-31-44-1:~/scripts$ 

