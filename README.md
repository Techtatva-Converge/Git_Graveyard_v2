# 🕵️‍♂️ Challenge: The Lost Commits 

---

## 📜 Description

This repository looks empty — almost *too* empty.  
No code, no branches, no tags… but something doesn’t add up.  

Git claims the repository is “clean,” yet the object count is far higher than it should be.  
It’s almost as if **someone committed something important**, then tried to **erase all traces of it**.  

The truth?  
Not everything is gone. Some fragments still linger in the shadows of the Git object store — **pieces of data that Git can’t reach through normal commands.**  

Your mission is to **recover those hidden fragments** and reconstruct what was lost.  

---

## 💡 Hints

- The flag is not in the visible working directory — you’ll need to explore *beyond* `git log`.  
- Some **unreachable commits** still contain **small `.b64` files** — maybe hundreds of them.  
- Git never truly forgets; it just marks objects as *dangling*.  
- Try verifying the repository’s integrity or searching for lost objects.  
- Once you recover all `.b64` fragments, you might find a way to **combine and decode** them.  

---



