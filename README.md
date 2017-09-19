# edurekaDevOps
mkdir GIT_NEW_PROJECT
cd GIT_NEW_PROJECT
  
git init
  
git config --global user.name "mobilekbhat"
git config --global user.email karthikkbhat@yahoo.co.in
git remote add origin https://github.com/mobilekbhat/edurekaDevOps.git
  
cat config 
  
touch edureka1.txt
touch edureka2.txt
touch edureka3.txt
git status
git add . # can add this way as well git add -A or git add edureka1.txt 
git commit -m "Adding first files - edureka1.txt, edureka2.txt, edureka3.txt" #git commit -a -m "message" if already file exits in repo and it is only the modify

git branch Develop #creating branch
git branch #list all branches and indicates which branch user is using
  
git checkout Develop #connects to Develop branch, default would be *master branch
 
git push origin Develop
