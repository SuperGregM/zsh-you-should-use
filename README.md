You Should Use
==============

Simple zsh plugin that reminds you that you should use one of your existing aliases for a command you just typed.

Usage
-----

You dont need to do anything. Once it's installed, `zsh-you-should-know` will let you know if you wrote a
command with an existing alias.

```
$ git commit -m "test commit"
Found existing alias for "git commit". You should use: "gc"
On branch master
Your branch is up-to-date with 'origin/master'.
Changes not staged for commit:
	modified:   README.md

no changes added to commit
```

List Aliases
------------

I have also included a bonus command `lsalias` as part of this plugin that will allow you to list your existing aliases.

```
$ lsalias
.. = "cd .."
gc = "git commit"
cd.. = "cd .."
gd = "git diff"
xc = "xcopy"
h = "history"
LS = "LS -e"
gap = "git add -p"
xp = "xpaste"
t = "tig"
...
```

Installation
------------

Add one of the following to your `.zshrc` file depending on your package manager:

```
zplug "MichaelAquilina/zsh-you-should-use"
```

```
antigen bundle "MichaelAquilina/zsh-you-should-use"
```

```
zgen load "MichaelAquilina/zsh-you-should-use"
```

Contributing
------------

Pull requests and Feedback are welcome! Feel free to open an issue for any bugs that you find! :tada:
