@ruchaupadhye2017 ➜ /workspaces/Rucha-Linux/linux-basics (main) $ cd day1
bash: cd: day1: No such file or directory
@ruchaupadhye2017 ➜ /workspaces/Rucha-Linux/linux-basics (main) $ ls
Day1  Day2
@ruchaupadhye2017 ➜ /workspaces/Rucha-Linux/linux-basics (main) $ cd Day1
@ruchaupadhye2017 ➜ /workspaces/Rucha-Linux/linux-basics/Day1 (main) $ cd ..
@ruchaupadhye2017 ➜ /workspaces/Rucha-Linux/linux-basics (main) $ cd Day2
@ruchaupadhye2017 ➜ /workspaces/Rucha-Linux/linux-basics/Day2 (main) $ cd ..
@ruchaupadhye2017 ➜ /workspaces/Rucha-Linux/linux-basics (main) $ mkdir Day3
@ruchaupadhye2017 ➜ /workspaces/Rucha-Linux/linux-basics (main) $ mkdir Day4
@ruchaupadhye2017 ➜ /workspaces/Rucha-Linux/linux-basics (main) $ cd Day3
@ruchaupadhye2017 ➜ /workspaces/Rucha-Linux/linux-basics/Day3 (main) $ touch file1 file2 file3
@ruchaupadhye2017 ➜ /workspaces/Rucha-Linux/linux-basics/Day3 (main) $ rm file3
@ruchaupadhye2017 ➜ /workspaces/Rucha-Linux/linux-basics/Day3 (main) $ ls
file1  file2
@ruchaupadhye2017 ➜ /workspaces/Rucha-Linux/linux-basics/Day3 (main) $ mkdir pratice
@ruchaupadhye2017 ➜ /workspaces/Rucha-Linux/linux-basics/Day3 (main) $ mkdir pratice/commands
@ruchaupadhye2017 ➜ /workspaces/Rucha-Linux/linux-basics/Day3 (main) $ rm -Ri pratice/commands
rm: remove directory 'pratice/commands'? y
@ruchaupadhye2017 ➜ /workspaces/Rucha-Linux/linux-basics/Day3 (main) $ rm -R pratice
@ruchaupadhye2017 ➜ /workspaces/Rucha-Linux/linux-basics/Day3 (main) $ touch redme.md
@ruchaupadhye2017 ➜ /workspaces/Rucha-Linux/linux-basics/Day3 (main) $ mkdir di1
@ruchaupadhye2017 ➜ /workspaces/Rucha-Linux/linux-basics/Day3 (main) $ mkdir mkdir dir2 dir3
@ruchaupadhye2017 ➜ /workspaces/Rucha-Linux/linux-basics/Day3 (main) $ touch di1/file.txt dir2/file2.txt dir3/file3.txt
@ruchaupadhye2017 ➜ /workspaces/Rucha-Linux/linux-basics/Day3 (main) $ rm -Riv di1
rm: descend into directory 'di1'? y
rm: remove regular empty file 'di1/file.txt'? y
removed 'di1/file.txt'
rm: remove directory 'di1'? y
removed directory 'di1'
@ruchaupadhye2017 ➜ /workspaces/Rucha-Linux/linux-basics/Day3 (main) $ rm -Rv dir2
removed 'dir2/file2.txt'
removed directory 'dir2'
@ruchaupadhye2017 ➜ /workspaces/Rucha-Linux/linux-basics/Day3 (main) $ git add .
@ruchaupadhye2017 ➜ /workspaces/Rucha-Linux/linux-basics/Day3 (main) $ git commit -m"Leraned how to remove files using rm command"
[main e1daada] Leraned how to remove files using rm command
 4 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 linux-basics/Day3/dir3/file3.txt
 create mode 100644 linux-basics/Day3/file1
 create mode 100644 linux-basics/Day3/file2
 create mode 100644 linux-basics/Day3/redme.md
@ruchaupadhye2017 ➜ /workspaces/Rucha-Linux/linux-basics/Day3 (main) $ git push
Enumerating objects: 8, done.
Counting objects: 100% (8/8), done.
Delta compression using up to 2 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 535 bytes | 535.00 KiB/s, done.
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/ruchaupadhye2017/Rucha-Linux
   a941d23..e1daada  main -> main
@ruchaupadhye2017 ➜ /workspaces/Rucha-Linux/linux-basics/Day3 (main) $ 