- [ ] When you run a command in the terminal, where does BASH look for that command?
- [] On a UNIX computer, how do you stop a running process?
  control + c

- [ ] What packages do you have installed via homebrew?
  `autoconf        git             icu4c           libgpg-error    libtool         openssl         pkg-config      readline
automake        hub             jpeg            libksba         node            ossp-uuid       postgresql      redis`

- [ ] On a UNIX computer, how do you find the process id of a running process?
  pgrep
- [ ] In a terminal, what does control-c do?
  aborts an action

- [ ] In a terminal, what does control-a do?
  places the cursor at the beginning of the command line

- [ ] In a terminal, what does control-e do?
  cursor goes to the end of the command line

- [ ] What keyboard shortcut do you use to split the screen in your editor?
  Drag the file I want to the left side of my editor

- [ ] What keyboard shortcut do you use to split the screen in your terminal?
  command + d

- [ ] When a terminal command completes, how can you tell if it was successful or not?
  by the green arrow

- [ ] What does your `~/.gitconfig` have in it? (paste the whole file here)
credential.helper=osxkeychain
user.name=rogercamps
user.email=rogercamps@me.com
push.default=simple
core.repositoryformatversion=0
core.filemode=true
core.bare=false
core.logallrefupdates=true
core.ignorecase=true
core.precomposeunicode=true
remote.origin.url=https://github.com/rogercamps/phase-2-challenge.git

remote.origin.fetch=+refs/heads/*:refs/remotes/origin/*
branch.master.remote=origin
branch.master.merge=refs/heads/master
branch.setup.remote=origin
branch.setup.merge=refs/heads/setup
branch.part3.remote=origin
branch.part3.merge=refs/heads/part3

- [ ] What is the difference between a relative and absolute path?
  The difference is that absolute is the full path to a file and relative

- [ ] Lets say you have the following file structure

  ```
  ~
  └── Projects
      ├── pinterest-for-dogs
      │   ├── README.md
      │   └── package.json
      └── linkedin-for-dancers
          ├── README.md
          └── package.json
  ```

  And you were in the `linkedin-for-dancers` folder. What command would you use to change folders to the `pinterest-for-dogs` folder?
    cd ..
    cd pint (tab and it would show me the options starting by 'pint' so i just have to press enter)

- [ ] What keyboard shortcut do you use, in your editor, when you want to open a specific file?
  Command + o

- [ ] What files or folders do you want all git repositories to ignore?
  node modules

- [ ] What is the main difference between `==` and `===` in JavaScript?
  === is strict comparison operator while == is more forgiving even though it is also a comparison operator
