# GitHub Mein Project History Dekhne Ka Tarika

GitHub par kisi project ki complete history dekhne ke liye bahut saare options hain. Ismein commit history, individual contributions, code changes tracking aur bahut kuch shamil hai. Yahan main features ki detail mein jaankari di gayi hai.

## 1. Commits History Dekhna

### Repository mein commits dekhna
```
   _____                           _ _       
  / ____|                         (_) |      
 | |     ___  _ __ ___  _ __ ___  _| |_ ___ 
 | |    / _ \| '_ ` _ \| '_ ` _ \| | __/ __|
 | |___| (_) | | | | | | | | | | | | |_\__ \
  \_____\___/|_| |_| |_|_| |_| |_|_|\__|___/
```

1. Kisi bhi repository par jaayein
2. "Code" tab ke bagal mein "Commits" ya clock icon par click karein
3. Aapko poore project ki commit history mil jayegi, chronological order mein
4. Har commit ke saath ye information milegi:
   - Commit message
   - Author ka naam
   - Date and time
   - Commit hash (unique identifier)

### Specific branch ki commits dekhna
1. Repository mein jaayein
2. Branch selector dropdown se desired branch select karein
3. Phir "Commits" tab par click karein

## 2. Individual Contributors Ki Jaankari

```
   _____            _        _ _           _                 
  / ____|          | |      (_) |         | |                
 | |     ___  _ __ | |_ _ __ _| |__  _   _| |_ ___  _ __ ___ 
 | |    / _ \| '_ \| __| '__| | '_ \| | | | __/ _ \| '__/ __|
 | |___| (_) | | | | |_| |  | | |_) | |_| | || (_) | |  \__ \
  \_____\___/|_| |_|\__|_|  |_|_.__/ \__,_|\__\___/|_|  |___/
```

### Contributors summary dekhna
1. Repository mein "Insights" tab par click karein
2. Left sidebar mein "Contributors" option select karein
3. Aapko ek graph milega jo dikhata hai ki kaun kitna contribute kar raha hai

### Specific user ke contributions dekhna
1. Repository mein "Insights" tab par click karein
2. "Contributors" section mein us user ke naam par click karein
3. Ya phir user ke profile par jakar "Contributions" section check karein

## 3. Code Changes Ka Detail (Diffs)

### Individual commit mein kya change hua, ye dekhna
1. Kisi bhi commit par click karein
2. Aapko line-by-line changes dikhenge:
   - Green highlighted lines: Added code
   - Red highlighted lines: Removed code
   - Unchanged code bhi context ke liye dikhega

### Do versions ke beech comparison
1. Repository mein "Pull requests" tab par jaayein
2. "New pull request" click karein
3. Base aur compare branches ko select karein
4. "Compare" button click karein

## 4. File History Dekhna

```
  _______ _        _    _ _     _                   
 |__   __(_)      | |  | (_)   | |                  
    | |   _ _ __  | |__| |_ ___| |_ ___  _ __ _   _ 
    | |  | | '__| |  __  | / __| __/ _ \| '__| | | |
    | |  | | |    | |  | | \__ \ || (_) | |  | |_| |
    |_|  |_|_|    |_|  |_|_|___/\__\___/|_|   \__, |
                                               __/ |
                                              |___/ 
```

1. Repository mein, file par click karein jiska history dekhna hai
2. File view mein "History" button par click karein (right side)
3. Aapko us file ke saare commits dikhenge

## 5. Git Blame - Kaun Si Line Kisne Likhi

1. Repository mein, file par click karein
2. File view mein "Blame" button par click karein
3. Har line ke saath author name, commit hash aur time stamp dikhega

## 6. GitHub Insights for Analytics

```
    ___                _       _     _       
   |_ _|_ __  ___(_) __ _| |__ | |_ ___ 
    | || '_ \/ __| |/ _` | '_ \| __/ __|
    | || | | \__ \ | (_| | | | | |_\__ \
   |___|_| |_|___/_|\__, |_| |_|\__|___/
                    |___/               
```

1. Repository mein "Insights" tab par click karein
2. Aapko multiple options milenge:
   - "Pulse" - Overall activity overview
   - "Contributors" - Kon kitna contribute kar raha hai
   - "Community" - Community health analysis
   - "Traffic" - Repo visits and clones
   - "Commits" - Commit frequency graph
   - "Code frequency" - Additions vs. deletions over time
   - "Dependency graph" - Dependencies visualization

## 7. Command Line Se History Check Karna

Agar aap GitHub repository ko local machine par clone kar chuke hain, to git commands se bhi history check kar sakte hain:

```
# Basic commit history
git log

# Short, one-line history
git log --oneline

# Graph view with branches
git log --graph --oneline --all

# History for specific file
git log --follow filename.txt

# See who changed each line
git blame filename.txt

# See changes between commits
git diff commit1..commit2
```

## 8. External Tools (Optional)

GitHub ki built-in functionality kaafi powerful hai, lekin kuch advanced analysis ke liye ye third-party tools bhi useful ho sakte hain:

1. **GitLens** (VS Code extension) - Code history ko editor mein hi display karta hai
2. **Git Kraken** - Visual Git client with powerful history visualization
3. **GitHub Desktop** - Simple GUI for basic Git operations
4. **SourceTree** - Visual Git client with detailed history view

---

GitHub project history track karna kaafi simple hai aur ismein external tools ki zaroorat nahi hai. GitHub interface se hi saari important information mil jaati hai. Lekin complex projects ke liye, kuch external tools extra insights de sakte hain.
