# gitcreate

gitcreate.sh is a script that will create a GitHub repository and add all files based on your current working directory. This is all done from the command line and will save you some time from going into your browser, creating a repository, and copying and pasting commands. It is also useful for beginners who are confused with GitHub.

This script gets a username from .gitconfig.  If it indicates that your default username is an empty string, you can set it with
`git config --add github.user YOUR_GIT_USERNAME`

Great article on [bash scripting](https://medium.com/devnetwork/how-to-create-your-own-custom-terminal-commands-c5008782a78e).

## How to use
- After sourcing the script, simply go to a project directory and run `gitcreate`

### Credit
Forked from [jerrykrinock](https://gist.github.com/jerrykrinock/6618003) and [robwierzbowski](https://gist.github.com/robwierzbowski/5430952).
