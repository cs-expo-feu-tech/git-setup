# git-setup
This repository is for members to test whether their git environment is set correctly.

## Instructions for members

Open a command line window.

Clone the repository to your local machine using this command:

```bash
git clone https://github.com/cs-expo-feu-tech/git-setup
```

Go to the `git-setup` directory:

```bash
cd git-setup
```

Checkout the `hello-members` branch by using this command:

```bash
git checkout hello-members
```

Open the `README.md` file with your favorite editor, put your name below this file, then save the file.

Back to the command line, "stage" the file for changes using the following command:

```bash
git add README.md
# Alternatively, you can also do git add -A
```

Commit your changes using the ff. command, making sure to replace your name inside the quotes:

```bash
git commit -m "YOUR NAME HERE - added name to README"
```

Lastly, push the commits to Github.

```bash
git push --set-upstream origin hello-members
```

💡 Note that if you have run the previous command, you don't need to include `--set-upstream origin hello-members` part.

Check the repository on Github, change the branch to 'hello-members', and see your changes show up!

---

Marc Steven Clemen