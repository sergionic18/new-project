Initial content for README
This is addintional instructuion which I added to readme

Instructions to get properly README.md file (were added manually):

mkdir new-project
cd new-project
git init
echo "Initial content for README" > README.md
git add README.md
git commit -m "init"
git checkout -b development
echo "This is addintional instructuion which I added to readme" >> README.md
git add README.md 
git checkout master
git barnch -m "main"
git merge development 