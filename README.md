# README
doanthanhdi
$ git clone https://github.com/your-username/your-repo.git
$ echo "Hello, World!" > README.md
$ git add README.md
$ git commit -m "Initial commit"
$ git push origin master
$ echo "This is a new line" >> README.md
$ git add README.md
$ git commit -m "Add new line to README.md"
Hello, World!
This is a new line
This is a new line added remotely
$ git push origin master
To https://github.com/your-username/your-repo.git
$ git pull origin master
Auto-merging README.md
CONFLICT (content): Merge conflict in README.md
Automatic merge failed; fix conflicts and then commit the result.
Hello, World!
This is a new line
This is a new line added remotely

This is a fix for the conflict
$ git push origin master
