$ cd C:\Users\Anwaar-ul-Karim Shah\Desktop\Assignment
bash: cd: too many arguments

Anwaar-ul-Karim Shah@MAAAKS MINGW64 ~
$ cd Desktop\Assignment
bash: cd: DesktopAssignment: No such file or directory

Anwaar-ul-Karim Shah@MAAAKS MINGW64 ~
$ cd Desktop/Assignment

Anwaar-ul-Karim Shah@MAAAKS MINGW64 ~/Desktop/Assignment
$ git clone https://github.com/Muhammad-Muzammil-Shah/cde-b1-assignments.git
Cloning into 'cde-b1-assignments'...
remote: Enumerating objects: 4, done.
remote: Counting objects: 100% (4/4), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 4 (delta 0), reused 4 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (4/4), done.

Anwaar-ul-Karim Shah@MAAAKS MINGW64 ~/Desktop/Assignment
$ cd cde-b1-assignments/

Anwaar-ul-Karim Shah@MAAAKS MINGW64 ~/Desktop/Assignment/cde-b1-assignments (main)
$ ls
M_muzammil-340493/  assignment/

Anwaar-ul-Karim Shah@MAAAKS MINGW64 ~/Desktop/Assignment/cde-b1-assignments (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        M_muzammil-340493/

nothing added to commit but untracked files present (use "git add" to track)

Anwaar-ul-Karim Shah@MAAAKS MINGW64 ~/Desktop/Assignment/cde-b1-assignments (main)
$ git add .
warning: in the working copy of 'M_muzammil-340493/Assignment 01 (Python Basics).ipynb', LF will be replaced by CRLF the next time Git touches it

Anwaar-ul-Karim Shah@MAAAKS MINGW64 ~/Desktop/Assignment/cde-b1-assignments (main)
$ git commit -m "saylani 1st assinment"
[main a8f0fbd] saylani 1st assinment
 1 file changed, 951 insertions(+)
 create mode 100644 M_muzammil-340493/Assignment 01 (Python Basics).ipynb

Anwaar-ul-Karim Shah@MAAAKS MINGW64 ~/Desktop/Assignment/cde-b1-assignments (main)
$ git push -u origin
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 4.62 KiB | 1.16 MiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Muhammad-Muzammil-Shah/cde-b1-assignments.git
   0cd556a..a8f0fbd  main -> main
branch 'main' set up to track 'origin/main'.



# cde-b1-assignments

## Overview
This repository contains Python assignments for basic programming practice. It is designed for students to learn and demonstrate foundational Python skills.

---

## Assignment 01: Python Basics

**Topics Covered:**
- Variables and data types
- Print statements and escape sequences
- Arithmetic, comparison, logical, bitwise, and assignment operators
- Conditional statements (if, elif, else)
- User input and output
- Simple calculations (percentage, marks, bonus, voting eligibility, even/odd, divisibility, etc.)
- Grading system and attendance logic
- Leap year calculation
- Service placement logic based on age/gender
- Electricity bill calculation
- Finding oldest/youngest among three people

**How to Use:**
- Open the notebook `Assignment 01 (Python Basics).ipynb` in Jupyter or Google Colab.
- Follow each cell and run the code to see results and learn Python basics.
- Modify the code to practice and experiment with different inputs.

---

## Contributing
Contributions are welcome! Fork the repo and submit pull requests for improvements or new assignments.

---

## License
This project is licensed under the MIT License.

