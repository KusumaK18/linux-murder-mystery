# 🔍 Clue 02 — The Secret Message

The thief left a message - but it's buried inside a file!

## 🧩 Your Task

Run these commands:
mkdir -p /mystery/room2

echo "The culprit is... keep looking!" > /mystery/room2/note.txt

echo "Suspect: MR. GREP" >> /mystery/room2/note.txt

echo "Alibi: was editing files all night" >> /mystery/room2/note.txt

Now search for the word **"Suspect"** inside the file!

## 💡 Hint
You need a command that searches for patterns inside files...

## ✅ Command to Learn
grep "Suspect" /mystery/room2/note.txt

## ➡️ Next Lead
The suspect was modifying files at midnight!
Go to 👉 [clue-03.md](clue-03.md)
