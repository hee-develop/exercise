# Exercise

Repository for learning something new

## List

### React
- React tutorial(tic tac toe) / branch: [react/tutorial](./tree/react/tutorial)


<br>

---

### Enter new project

#### Via real sub-project
```
# in sub-project
git remote add origin git@github.com:hee-develop/exercise.git

git push origin master:[new_branch_name]

## result
# origin/[new_branch_name]
```

#### Via subtree (currently not used)
```
# add remote
git remote add [remote_branch_name] [repository]

# add subtree
git subtree add --prefix=[prefix_name] [repository] [target_branch=master]

# checkout
git pull [repository]
git checkout --track [repository/target_branch] -b [new_branch_name]
```
