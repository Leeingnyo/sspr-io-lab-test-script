# 2020 Fall SNU System Programming Lab 2 - I/O Lab Test Script

This is not official test script
This script doesn't guarantee 100% pass on real score

## Prepare

after cloning and entering the directory

```
mkdir -p testcases/not-permitted
chmod 400 testcases/not-permitted
```

## How to Use

move all files to lab folder except README.md and run ttest.sh

```
clone [this repo]
mv [repo folder]
mv * -t [lab folder]
cd [lab folder]
git checkout -- README.md
./ttest.sh
```

check failcase diff with testcase number via df.sh (using vimdiff)

```
./df.sh [testcase number]
```

## Notice

the reference program might have bugs

* in multiple directories with summary option, the reference program doesn't calculate sockets and pipes of total stat well.

## Etc.

you can contribute this repo by adding testcases and tree files or porting these script into Windows bat files.
