Data
==

Git
=
```
git clone --recursive https://github.com/hamshif/data.git

# or

git clone https://github.com/hamshif/data.git
cd data
git submodule update --init --recursive

# or


git submodule foreach 'git checkout master && git pull'
```


This is a super repository for use in cloud data projects such as datalake
It's used to version control code in different languages and frameworks organized in independent repositories

submodule git instructions at:

https://chrisjean.com/git-submodules-adding-using-removing-and-updating/

for IntelliJ instructions Look in Wielder submodule: IntelliJ.md

