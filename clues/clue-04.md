# 🔍 Clue 04 - The Log File Confession

Every action on a Linux server is logged...
The thief forgot to delete the logs!

## 🧩 Your Task

Run these commands:
mkdir -p /mystery/room4
echo "User: alex - logged in at 23:58" > /mystery/room4/server.log
echo "User: alex - deleted secret.txt at 00:01" >> /mystery/room4/server.log
echo "User: bob - logged in at 08:00" >> /mystery/room4/server.log

Now find who was active at midnight!

## 💡 Hint
Search for the time pattern "00:0" inside the log file...

## ✅ Command to Learn
grep "00:0" /mystery/room4/server.log

## ➡️ Almost there!
Count how many crimes were committed!
Go to 👉 [clue-05.md](clue-05.md)
