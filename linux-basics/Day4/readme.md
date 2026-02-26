@ruchaupadhye2017 ➜ /workspaces/Rucha-Linux/linux-basics/Day4 (main) $ mkdir div1
@ruchaupadhye2017 ➜ /workspaces/Rucha-Linux/linux-basics/Day4 (main) $ ls
div1
@ruchaupadhye2017 ➜ /workspaces/Rucha-Linux/linux-basics/Day4 (main) $ touch file1
@ruchaupadhye2017 ➜ /workspaces/Rucha-Linux/linux-basics/Day4 (main) $ echo "Welcome" > file1
@ruchaupadhye2017 ➜ /workspaces/Rucha-Linux/linux-basics/Day4 (main) $ rm
rm: missing operand
Try 'rm --help' for more information.
@ruchaupadhye2017 ➜ /workspaces/Rucha-Linux/linux-basics/Day4 (main) $ ls
div1  file1
@ruchaupadhye2017 ➜ /workspaces/Rucha-Linux/linux-basics/Day4 (main) $ pwd
/workspaces/Rucha-Linux/linux-basics/Day4
@ruchaupadhye2017 ➜ /workspaces/Rucha-Linux/linux-basics/Day4 (main) $ cat file1
Welcome
@ruchaupadhye2017 ➜ /workspaces/Rucha-Linux/linux-basics/Day4 (main) $ touch file2
@ruchaupadhye2017 ➜ /workspaces/Rucha-Linux/linux-basics/Day4 (main) $ cp -r file1 file2
@ruchaupadhye2017 ➜ /workspaces/Rucha-Linux/linux-basics/Day4 (main) $ cat file2
Welcome
@ruchaupadhye2017 ➜ /workspaces/Rucha-Linux/linux-basics/Day4 (main) $ mkdir div2
@ruchaupadhye2017 ➜ /workspaces/Rucha-Linux/linux-basics/Day4 (main) $ echo "wlc" > div2
bash: div2: Is a directory
@ruchaupadhye2017 ➜ /workspaces/Rucha-Linux/linux-basics/Day4 (main) $ ls
div1  div2  file1  file2
@ruchaupadhye2017 ➜ /workspaces/Rucha-Linux/linux-basics/Day4 (main) $ echo "wlc" > file2
@ruchaupadhye2017 ➜ /workspaces/Rucha-Linux/linux-basics/Day4 (main) $ cp -r file2 file1
@ruchaupadhye2017 ➜ /workspaces/Rucha-Linux/linux-basics/Day4 (main) $ cat file1
wlc
@ruchaupadhye2017 ➜ /workspaces/Rucha-Linux/linux-basics/Day4 (main) $ cat file2
wlc
@ruchaupadhye2017 ➜ /workspaces/Rucha-Linux/linux-basics/Day4 (main) $ git add .
@ruchaupadhye2017 ➜ /workspaces/Rucha-Linux/linux-basics/Day4 (main) $ git commit -"All command pratice"
error: unknown switch `A'
usage: git commit [-a | --interactive | --patch] [-s] [-v] [-u[<mode>]] [--amend]
                  [--dry-run] [(-c | -C | --squash) <commit> | --fixup [(amend|reword):]<commit>]
                  [-F <file> | -m <msg>] [--reset-author] [--allow-empty]
                  [--allow-empty-message] [--no-verify] [-e] [--author=<author>]
                  [--date=<date>] [--cleanup=<mode>] [--[no-]status]
                  [-i | -o] [--pathspec-from-file=<file> [--pathspec-file-nul]]
                  [(--trailer <token>[(=|:)<value>])...] [-S[<keyid>]]
                  [--] [<pathspec>...]

    -q, --[no-]quiet      suppress summary after successful commit
    -v, --[no-]verbose    show diff in commit message template

Commit message options
    -F, --[no-]file <file>
                          read message from file
    --[no-]author <author>
                          override author for commit
    --[no-]date <date>    override date for commit
    -m, --[no-]message <message>
                          commit message
    -c, --[no-]reedit-message <commit>
                          reuse and edit message from specified commit
    -C, --[no-]reuse-message <commit>
                          reuse message from specified commit
    --[no-]fixup [(amend|reword):]commit
                          use autosquash formatted message to fixup or amend/reword specified commit
    --[no-]squash <commit>
                          use autosquash formatted message to squash specified commit
    --[no-]reset-author   the commit is authored by me now (used with -C/-c/--amend)
    --trailer <trailer>   add custom trailer(s)
    -s, --[no-]signoff    add a Signed-off-by trailer
    -t, --[no-]template <file>
                          use specified template file
    -e, --[no-]edit       force edit of commit
    --[no-]cleanup <mode> how to strip spaces and #comments from message
    --[no-]status         include status in commit message template
    -S, --[no-]gpg-sign[=<key-id>]
                          GPG sign commit

Commit contents options
    -a, --[no-]all        commit all changed files
    -i, --[no-]include    add specified files to index for commit
    --[no-]interactive    interactively add files
    -p, --[no-]patch      interactively add changes
    -U, --unified <n>     generate diffs with <n> lines context
    --inter-hunk-context <n>
                          show context between diff hunks up to the specified number of lines
    -o, --[no-]only       commit only specified files
    -n, --no-verify       bypass pre-commit and commit-msg hooks
    --verify              opposite of --no-verify
    --[no-]dry-run        show what would be committed
    --[no-]short          show status concisely
    --[no-]branch         show branch information
    --[no-]ahead-behind   compute full ahead/behind values
    --[no-]porcelain      machine-readable output
    --[no-]long           show status in long format (default)
    -z, --[no-]null       terminate entries with NUL
    --[no-]amend          amend previous commit
    --no-post-rewrite     bypass post-rewrite hook
    --post-rewrite        opposite of --no-post-rewrite
    -u, --[no-]untracked-files[=<mode>]
                          show untracked files, optional modes: all, normal, no. (Default: all)
    --[no-]pathspec-from-file <file>
                          read pathspec from file
    --[no-]pathspec-file-nul
                          with --pathspec-from-file, pathspec elements are separated with NUL character

@ruchaupadhye2017 ➜ /workspaces/Rucha-Linux/linux-basics/Day4 (main) $ git commit -m"All command p
ratice"
[main 1c6f51e] All command pratice
 2 files changed, 2 insertions(+)
 create mode 100644 linux-basics/Day4/file1
 create mode 100644 linux-basics/Day4/file2
@ruchaupadhye2017 ➜ /workspaces/Rucha-Linux/linux-basics/Day4 (main) $ git push
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 2 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (5/5), 403 bytes | 403.00 KiB/s, done.
Total 5 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/ruchaupadhye2017/Rucha-Linux
   adbb4fa..1c6f51e  main -> main
@ruchaupadhye2017 ➜ /workspaces/Rucha-Linux/linux-basics/Day4 (main) $ rm -Ri div2
rm: remove directory 'div2'? y
@ruchaupadhye2017 ➜ /workspaces/Rucha-Linux/linux-basics/Day4 (main) $ ls
div1  file1  file2
@ruchaupadhye2017 ➜ /workspaces/Rucha-Linux/linux-basics/Day4 (main) $ rm -Ri file2
rm: remove regular file 'file2'? y
@ruchaupadhye2017 ➜ /workspaces/Rucha-Linux/linux-basics/Day4 (main) $ rm -Rv file1
removed 'file1'
@ruchaupadhye2017 ➜ /workspaces/Rucha-Linux/linux-basics/Day4 (main) $ touch file1
@ruchaupadhye2017 ➜ /workspaces/Rucha-Linux/linux-basics/Day4 (main) $ git add .
@ruchaupadhye2017 ➜ /workspaces/Rucha-Linux/linux-basics/Day4 (main) $ git commit -m"command pratice"
[main da5c531] command pratice
 2 files changed, 2 deletions(-)
 delete mode 100644 linux-basics/Day4/file2
@ruchaupadhye2017 ➜ /workspaces/Rucha-Linux/linux-basics/Day4 (main) $ git push
Enumerating objects: 9, done.
Counting objects: 100% (9/9), done.
Delta compression using up to 2 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (5/5), 380 bytes | 380.00 KiB/s, done.
Total 5 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/ruchaupadhye2017/Rucha-Linux
   1c6f51e..da5c531  main -> main
@ruchaupadhye2017 ➜ /workspaces/Rucha-Linux/linux-basics/Day4 (main) $ touch readme.md
@ruchaupadhye2017 ➜ /workspaces/Rucha-Linux/linux-basics/Day4 (main) $ 