# Lab 01 - HCI-CG
## Short-Term Memory Limits & Interface Design

<img width="950" height="448" alt="netflix" src="https://github.com/user-attachments/assets/35bfaad6-07ae-480f-a807-ce21b02a8f3f" />


## Activity 2: Interface Chunking Observation

### Netflix
![Netflix Annotated](netflix_annotated.png)

**Chunking Strategies observed:**
- Top navigation bar (Home, Series, Films, Games, New & Popular, My List) 
  acts as one chunk — limits items to 7 following Miller's Law
- "Only on Netflix" carousel groups multiple titles into one category chunk
- "Top 10 Films in Pakistan Today" is a separate ranked chunk
- Each row acts as a single unit, reducing hundreds of titles into ~5-6 visible groups

---

### YouTube
<img width="951" height="445" alt="youtube" src="https://github.com/user-attachments/assets/6e112df6-586d-4492-be4b-80ffe6a83e48" />


**Chunking Strategies observed:**
- Top navigation bar groups Search, Upload, Notifications into one chunk
- Left sidebar menu groups links into sections (Home, Shorts, Subscriptions)
- Homepage divides videos into rows by topic/category
- Each video card groups thumbnail + title + channel name + views as one chunk

---

## Conclusion
Both Netflix and YouTube use chunking to reduce cognitive load on users.
Instead of showing raw lists of hundreds of items, they group content into
meaningful categories. This respects Miller's Law (7±2 items per chunk),
making interfaces easier to navigate and remember.



---

## Activity 3: STM Experiment (Miller's Law)

### What is Miller's Law?
Miller's Law states that the average person can only hold **7 (plus or minus 2)** 
items in their short-term memory at once.

### Console Demo
![Miller's Law Demo](millers_law.png)

### Results
| Version | Items Shown | Recall Difficulty |
|---------|-------------|-------------------|
| Ungrouped | 5 2 9 1 7 4 6 8 | Hard — 8 separate items |
| Chunked | 529  174  68 | Easy — only 3 chunks |

### Real UI Examples that respect Miller's Law
- **Phone numbers:** 0321-4567890 (grouped, not 03214567890)
- **Credit cards:** 4111 1111 1111 1111 (4 groups of 4)
- **Netflix navbar:** only 6 menu items (Home, Series, Films, Games, New & Popular, My List)
- **YouTube sidebar:** grouped into sections, not one long list
