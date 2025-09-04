# For creating the SHA code
```
echo "Hello World" | git hash-object --stdin
```

# To get to know what is there in SHA code we can print using the below command
```
git cat-file <commit id sha code> -p  --> prints the file
```
# For creating the duplicate 
```
git checkout -b karam-dosa
```

# Best way for git is
```
git checkout main
git pull origin main
```
# Reset 
# It will undo the changes.It will change history and commit id
# Three types of reset 
# 1. soft  --> it will remove the commit id but the code will remain as it is it provides an option to modify.
# 2. mixed  --> it will remove commit id and the code what we entered to commit should also be removed
# 3. hard  --> hard reset will remove everything .
```
git reset --soft HEAD~1  # Removes the first commit in the head
```
```
git reset HEAD~1   # mixed
```
```
git reset --hard HEAD~1 # hard 
```

# Revert

```
git revert HEAD~1 # do 1 revert at a time
```


