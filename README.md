# First-Session HTML ONLY Brainnest Project
<h2> Git Terminal Commands:</h2>
<h3>Main Terminal Commands we're using</h3>
<div>
    <ul>
        <li><h3>git init</h3></li>
            <q>This command turns a directory into an empty Git repository. This is the first step in creating a repository. After running git init, adding and committing files/directories is possible.</q><hr>
        <li><h3>git add .</h3></li>
            <q>Adds files in the to the staging area for Git. Before a file is available to commit to a repository, the file needs to be added to the Git index (staging area). There are a few different ways to use git add, by adding entire directories, specific files, or all unstaged files.</q><hr>
        <li><h3>git commit -m "example message"</h3></li>
            <q>Record the changes made to the files to a local repository. For easy reference, each commit has a unique ID.<br>
            It’s best practice to include a message with each commit explaining the changes made in a commit. Adding a commit message helps to find a particular change or understanding the changes.</q><hr>
        <li><h3>git push</h3></li>
            <q>Sends local commits to the remote repository. git push requires two parameters: the remote repository and the branch that the push is for.</q>
    </ul><hr>
     Other commands
    <ul>
        <li><h3>git pull</h3></li>
            <q>To get the latest version of a repository run git pull. This pulls the changes from the remote repository to the local computer.</q><hr>
        <li><h3>git clone</h3></li>
            <q>To create a local working copy of an existing remote repository, use git clone to copy and download the repository to a computer. Cloning is the equivalent of git init when working with a remote repository. Git will create a directory locally with all files and repository history.</q><hr>
        <li><h3>git merge</h3></li>
            <q>Integrate branches together. git merge combines the changes from one branch to another branch. For example, merge the changes made in a staging branch into the stable branch.</q><hr>
        <li><h3>git remote</h3></li>
            <q>To connect a local repository with a remote repository. A remote repository can have a name set to avoid having to remember the URL of the repository.</q><hr>
        <li><h3>git checkout</h3></li>
            <q>To start working in a different branch, use git checkout to switch branches.</q><hr>
        <li><h3>git branch</h3></li>
            <q>To determine what branch the local repository is on, add a new branch, or delete a branch.</q><hr>
        <li><h3>git status</h3></li>
            <q>This command returns the current state of the repository.
            git status will return the current working branch. If a file is in the staging area, but not committed, it shows with git status. Or, if there are no changes it’ll return nothing to commit, working directory clean.</q><hr>
        <li><h3>git log</h3></li>
            <q>To show the chronological commit history for a repository. This helps give context and history for a repository. git log is available immediately on a recently cloned repository to see history.</q><hr>
        <li><h3>git stash</h3></li>
            <q>To save changes made when they’re not in a state to commit them to a repository. This will store the work and give a clean working directory. For instance, when working on a new feature that’s not complete, but an urgent bug needs attention.</q><hr>
        <li><h3>git rm</h3></li>
            <q>Remove files or directories from the working index (staging area). With git rm, there are two options to keep in mind: force and cached. Running the command with force deletes the file. The cached command removes the file from the working index. When removing an entire directory, a recursive command is necessary.</q>
    </ul>
</div>
