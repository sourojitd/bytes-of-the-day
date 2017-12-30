# Git & CLI (Saturdays)

## 2017-11-04 (Saturday)

### Git & CLI
**`git bisect` for Bug Hunting** — Use `git bisect` to perform a binary search through your commit history to find the exact commit that introduced a bug. Start with `git bisect start`, then mark commits as `good` or `bad`.

https://git-scm.com/docs/git-bisect

---

## 2017-11-11 (Saturday)

### Git & CLI
**`grep` for Searching Text** — Use `grep -r 'search_term' .` to recursively search for a string in the current directory. `grep` is a powerful command-line utility for searching plain-text data sets for lines that match a regular expression.

https://www.gnu.org/software/grep/manual/grep.html

---

## 2017-11-18 (Saturday)

### Git & CLI
**Git: Amending Commits** — Made a mistake in your last commit message, or forgot a file? Use `git commit --amend` to modify the most recent commit. Be careful not to amend commits that have already been pushed to a public branch.

https://git-scm.com/book/en/v2/Git-Tools-Rewriting-History

---

## 2017-11-25 (Saturday)

### Git & CLI
**`awk` for Text Processing** — Use `awk` to process and analyze text files. For example, `awk '{print $1}' filename.txt` will print the first column of a space-separated file. It's a powerful tool for data extraction and reporting.

https://www.gnu.org/software/gawk/manual/gawk.html

---

## 2017-12-02 (Saturday)

### Git & CLI
**Git: `git stash` to Save Changes** — Need to quickly switch branches but aren't ready to commit your current work? Use `git stash` to temporarily shelve your changes. You can reapply them later with `git stash pop`.

https://git-scm.com/docs/git-stash

---

## 2017-12-09 (Saturday)

### Git & CLI
**Git: Interactive Rebase** — Use `git rebase -i HEAD~3` to interactively edit the last 3 commits. You can reorder, squash, reword, or drop commits. It's a powerful tool for cleaning up your local commit history before sharing it.

https://git-scm.com/book/en/v2/Git-Tools-Rewriting-History#_squashing

---

## 2017-12-16 (Saturday)

### Git & CLI
**Using `xargs`** — The `xargs` command builds and executes command lines from standard input. It's useful for piping the output of one command into another, e.g., `find . -name '*.tmp' | xargs rm` to delete all .tmp files.

https://man7.org/linux/man-pages/man1/xargs.1.html

---

## 2017-12-23 (Saturday)

### Git & CLI
**Git: Finding a Commit by Message** — Use `git log --grep='Your search string'` to search for commits that contain a specific string in their commit message. This is incredibly useful for finding when a particular change was made.

https://git-scm.com/docs/git-log

---

## 2017-12-30 (Saturday)

### Git & CLI
**Git: `git reflog` for Recovery** — Think you've lost a commit? `git reflog` shows a log of where your HEAD and branch references have been. It's a safety net that can help you recover commits that seem to be lost after a rebase or reset.

https://git-scm.com/docs/git-reflog

---

