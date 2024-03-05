# archive

## bash directory bookmarking tool

**Idea:** 
Be able too quickly navigate between often used directories via bash

**Implementation:**
* Add current directory via ```brb -a```
* Go to directory via ```brb``` which shows a fuzzy search implemented with ```fzf```

**Limitations:**
* Manually bookmarking directories is burdensome

**Improvement:**
* Catch and store directories automatically in a database
* Weight entries according to how often they are accessed

**Similar Tools:**
* https://github.com/wting/autojump
