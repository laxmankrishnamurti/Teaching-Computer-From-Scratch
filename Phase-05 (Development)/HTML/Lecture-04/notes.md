# How to push system files on GitHub.

- SignIn on Github
- Create a Git Repository.
- Copy the Repository Link
- Clone the project on your system
- Open the terminal and run the command

```bash
git clone <link>
```

- Add/Edit files
- Run add command

```bash
git add .
```

- Then, Commit all changes and write a commit message

```bash
git commit -m "<type_message_here>"
```

- Finally, Push all changes on GitHub

```bash
git push origin main
```

- If the branch name differs, change the branch name

```bash
# Know your exact branch name
git branch

# Change the branch name
git branch -m <new_branch_name>
```

all are set.

Now, you can push your local files on your remote location(GitHub).
