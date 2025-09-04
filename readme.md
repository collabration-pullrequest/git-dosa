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