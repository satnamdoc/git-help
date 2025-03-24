# Git commands from java developer cource [sprint #3](https://practicum.yandex.ru/trainer/java-developer-plus/lesson/332f9bef-e574-4600-9b07-c2529cdba26a/#afe01e3c-f093-4497-bafd-6d4f40b732ba)


### git add
Moves changes from the working directory to the staging area. This gives you the opportunity to prepare a snapshot before committing it to the official history.

### git clone
Creates a copy of an existing Git repository. Cloning is the most common way for developers to obtain a working copy of a central repository.

### git commit
Takes the staged snapshot and commits it to the project history. Combined with git add, this defines the basic workflow for all Git users.

### git config
A convenient way to set configuration options for your Git installation. You’ll typically only need to use this immediately after installing Git on a new development machine.

### git init
Initializes a new Git repository. If you want to place a project under revision control, this is the first command you need to learn.

### git log
Lets you explore the previous revisions of a project. It provides several formatting options for displaying committed snapshots.

### git push
Pushing is the opposite of fetching (with a few caveats). It lets you move a local branch to another repository, which serves as a convenient way to publish contributions. This is like svn commit, but it sends a series of commits instead of a single changeset.

### git remote
A convenient tool for administering remote connections. Instead of passing the full URL to the fetch, pull, and push commands, it lets you use a more meaningful shortcut.

### git status
Displays the state of the working directory and the staged snapshot. You’ll want to run this in conjunction with git add and git commit to see exactly what’s being included in the next snapshot.