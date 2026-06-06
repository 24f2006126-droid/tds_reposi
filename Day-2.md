---
---

--- Before Day-2 ---
I already knew ...
--- 

## Day-2 Checklist

- [ ] I understand what `PATH` is and why commands like `python` work without full paths
- [ ] I can navigate the filesystem without clicking — using `cd`, `ls`, and `pwd` only
- [ ] I can read, search, and inspect files using `cat`, `head`, `tail`, `grep`, and `wc`
- [ ] I can edit a file using `nano` (open, edit, save, exit)
- [ ] I understand pipes (`|`) and redirection (`>`, `>>`, `2>`) and can chain commands
- [ ] I can set an environment variable in `.bashrc` and apply it with `source ~/.bashrc`
- [ ] I know the difference between `export VAR=value` (available to child processes) and just `VAR=value` (shell-local)

--- After Day-2 ---
I learned these things ...
1)PATH is a list of folders.
2)cat → view full file.Shows the entire file content
3)head → first lines
4)tail → last lines
5)grep → search inside files. /grep -i "git" notes.txt/(Case-insensitive search.show all lines where Git or git present)
/grep -n "error" notes.txt/(Show line numbers)
6)wc → count lines, words, characters.(/wc folder.txt/ returns =>6  20 120 notes.txt)
7)nano -->Open a file(nano filename.txt).for edit -->Once inside nano, just type normally.
8)CTRL + O -->Save the file and ENTER.
9)CTRL + X -->Exit nano
10)Pipes (|) →A pipe sends the output of one command into another command.(/cat notes.txt | grep "error"/ =>cat notes.txt prints file content and grep "error" filters only matching lines)
11) > → overwrite file(Old content is deleted.)
12) >> → append to file(Adds output to the end of file.)
13) 2> → redirect errors(/cat missing.txt 2> error.log/ (save error))
14) VAR=value` => (Shell-local variable)Only exists in the current shell
15)export VAR=value (export VAR="hello")=>Exported variable.Available in current shell and ALSO passed to any child process.
---

--- Feedback (Suggestions for the TDS Team) ---
This is my feedback ...Same as before
---

---
---

You can write your personal notes here; they will not be parsed and are for your own reference.
