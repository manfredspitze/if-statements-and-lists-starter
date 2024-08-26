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

