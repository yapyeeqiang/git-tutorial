# Learn GIT

- [ ] Create a repository
- [ ] Add files
- [ ] Commit changes
- [ ] Push changes

## Prerequisite

Make sure you have git installed. You can check by:

```sh
## On all operating systems
git --version

## On UNIX-like operating systems:
which git
```

## Create a repository

1. Navigate to your project folder, and:

```sh
git init
```

This is to create a hidden file `.git` which contains the plumbing needed for
Git to work.

2. You can check the status of your files or changes by:

```sh
git status
```

## Add files

You can specify which files to place into version control by:

```sh
git add <file/directory name #1> <file/directory name #2> < ... >
```

If you want to add all files without typing it one by one, you can do:

```sh
git add .
```

By adding files, you have already `stage` those files to be added to
`version control`.

If you want to avoid some files to be added, you can create a file named
`.gitignore` and specify the file you want to ignore before running `git add`.

## Commit changes

Once your desired files are added, you can commit those files along with a
message by:

```sh
git commit -m 'Initial commit'
```
