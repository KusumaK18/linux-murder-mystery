# 🔍 Clue 03 - Midnight Modifications

The thief modified a file exactly at midnight to cover their tracks!

## 🧩 Your Task

Run these commands:
mkdir -p /mystery/room3
touch /mystery/room3/evidence.txt
touch /mystery/room3/fakefile.txt

Now find which file was most recently modified!

## 💡 Hint
You need a command that finds files and sorts by time...

## ✅ Command to Learn
find /mystery/room3 -type f -newer /mystery/room3/fakefile.txt

## ➡️ Next Lead
The thief left their name inside a log file!
Go to 👉 [clue-04.md](clue-04.md)
