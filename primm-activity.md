## PRIMM Activity
### If Statements & Lists

Take a minute or two to examine the Python code below.

```python
current_users = ['eric', 'willie', 'admin', 'erin', 'Garrett']
new_users = ['sarah', 'Willie', 'PHIL', 'garrett', 'Alyssa']

# Generate a new list of usernames in lowercase
current_users_lower = []
for user in current_users:
    current_users_lower.append(user.lower())

for new_user in new_users:
    if new_user.lower() in current_users_lower:
        print(f"Sorry {new_user}, that name is already taken.")
    else:
        print(f"Great, {new_user} is still available.")
```

### Code Analysis

1. How many lists will you have after you run this script?

2. How will the items in `current_users` be different from the items in `current_users_lower`?

3. In simple terms, explain what the first `for` loop is doing or is used for.

4. What is the purpose of the `if-else` statement in the second `for` loop?
