---
title: Welcome to Re:Fault Archieve
---

![[banner.png]]
# 🚀 Current Focus

### Active Projects

- [[SECON2]]
    
- [[Wiegenlied]]
    
- [[RRR]]
    

### Current Tasks

-  Write Chapter
    
-  Character Design
    
-  Worldbuilding Revision
    

---

# ✍️ Create

### Writing

- [[Story Projects]]
    
- [[Writing Desk]]
    
- [[Scene Ideas]]
    
- [[Dialogue Collection]]
    

### Worldbuilding

- [[Characters]]
    
- [[Organizations]]
    
- [[Locations]]
    
- [[Events]]
    
- [[Power Systems]]
    

### Visual Design

- [[Character Designs]]
    
- [[Reference Board]]
    
- [[Moodboards]]
    

---

# 📚 Knowledge

### Research

- [[History]]
    
- [[Science]]
    
- [[Mythology]]
    
- [[Technology]]
    

### Inspirations

- [[Books]]
    
- [[Movies]]
    
- [[Games]]
    
- [[Anime]]
    

---

# 💡 Idea Garden

- [[Random Ideas]]
    
- [[Future Projects]]
    
- [[Unused Concepts]]
    
- [[Cool Names]]
    

---

# 📈 Project Tracker

```dataview
TABLE status, progress
FROM #project
SORT file.name ASC
```

---

# 🕒 Recently Modified

```dataview
TABLE file.mtime as Updated
SORT file.mtime DESC
LIMIT 10
```

---

# ⭐ Favorites

```dataview
LIST
FROM #favorite
```

---

# 📊 Vault Stats

- Projects: `$=dv.pages('#project').length`
    
- Characters: `$=dv.pages('#character').length`
    
- Locations: `$=dv.pages('#location').length`
    
- Ideas: `$=dv.pages('#idea').length`


