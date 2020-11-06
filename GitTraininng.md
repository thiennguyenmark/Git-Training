
### Work Follow with git

# Step 1: Checkout base branch

Example: ```git checkout master```

# Step 2: Pull newest code from base branch

Example: ```git pull origin master```

# Step 3: Create new branch

Example: ```git checkout -b f-product```

Convention:

Feature: f-product

Hotfix: hotfix/something

Fix: fix-something

# Step 4: Update new changes

Ex: ```git add .```

Ex: ```git commit -m "Your changes message"```

Ex: ```git push origin your-branch```

# Step 5: Create PR

Ex: ```git push origin your-branch```

# Step 6: Ask leader to review your PR

--------------------------------------------------------------------------------------------------------------------------------------------------------------------
--------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Case 1: Conflict when having new Code, pull from base branch

Ex: ```git pull origin master -r```

After fix conflict

```git add .```

```git rebase --contiunue```

```git push origin your-branch -f```


# Case 2: Add changes lastest commit

```git add .```

```git commit --amend --no-edit```

```git push origin your-branch -f```

