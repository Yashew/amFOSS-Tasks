Step1: 
$ git clone https://github.com/gauthamk02/TerminalHunt.git


Step2: 
$ mkdir solution


Step3: 
$ cat > part1.txt; echo '107' > part1.txt


Step4: 
$ cd ~/TerminalHunt/06 

$ cp 1.txt solution

$ mv -v solution part2.txt

$ mv -v ~/TerminalHunt/06/part2.txt ~/TerminalHunt/solution/part2.txt


Step5:
$ git log

$ cd ~/TerminalHunt/10

$ cp 1.txt part3.txt

$ mv -v ~/TerminalHunt/10/part3.txt ~/TerminalHunt/solution/part3.txt

Step6:
$ git add ~/TerminalHunt/solution/part1.txt

$ git add ~/TerminalHunt/solution/part2.txt

$ git add ~/TerminalHunt/solution/part3.txt

$ git commit -am "Committed changes"


Step7:
$ cd ~/TerminalHunt/

$ git branch -a

$ git checkout asia


Step8:
$ find -name athens.txt

Step9:
$ git checkout main

$ git merge asia

$ cp ~/TerminalHunt/NewFolder/Greek-Empire/athens.txt ~/TerminalHunt/solution/part4.txt


Step10:
$ cat part1.txt part2.txt part3.txt part4.txt >password.txt

The Final Password is:
107562749031
