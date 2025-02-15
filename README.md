 pwd
/c/Users/User

cd /c/Users/User/Documents

git init

mkdir project

git add .placeholderfile

cd projects

git init

git commit -m "step1"

git config --global user.email "evelynoge08@gmail.com"

git config --global user.name "Ogechukwuedeh"

git commit -m "step1"

touch .projectfile

git add .

git commit -m "step1"

mkdir week1 week2

touch  week1/.weekfile week2/.weekfile

git add .

git commit -m "step2"

cd week1

touch hello.txt

git add hello.txt

git commit -m "step3"

cd ..

cp week1/hello.txt week2/hello_copy.txt

git add week2/hello_copy.txt

git commit -m "step4"

rm week1/hello.txt

git add -u

git commit -m "step5"

vim about_me.txt

git add about_me.txt

git commit -m "step6"

git remote add origin https://github.com/Ogechukwuedeh/LINUX-Assignm

git branch -M master

git push -u origin master

git push -u origin master
