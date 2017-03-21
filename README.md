## Repo Manifest ##

Since this project has evolved to a point where there's so many sub-projects, it would make life easier for everyone 
to have a tool to download all projects in this organization. 

## Getting Started ##
---------------
To get started on this project, you will need to download [repo](https://source.android.com/source/using-repo.html) from Google.

```bash
$ mkdir ~/bin
$ echo "PATH=~/bin:$PATH" >> ~/.bashrc
$ source ~/.bashrc
$ curl https://storage.googleapis.com/git-repo-downloads/repo > ~/bin/repo
$ chmod a+x ~/bin/repo
```

After that, create a working directory simply initiazlize your local repository.

```bash
$ mkdir PAS
$ cd PAS
$ repo init -u git@github.com:Proximity-Attendance-System/Repo-Manifest.git
$ repo sync 
```

**Note that you will need a macOS device to be able to build the iOS clients.**
