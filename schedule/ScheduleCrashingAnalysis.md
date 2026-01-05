|**Activity**|**Duration**|**Predecessor**|**ES**|**EF**|**LS**|**LF**|
|-----------|-----------|-----------|-----------|-----------|-----------|-----------|
|A | 3 | — | 0 | 3 | 0 | 3 |
|B | 5 | A | 3 | 8 | 3 | 8 |
|C | 4 | B | 8 | 12 | 8 | 12 |
|D (Crashed) | 4 | C | 12 | 16 | 12 | 16 |
|E | 3 | D | 16 | 19 | 16 | 19 |
|F (Crashed) | 2 | E | 19 | 21 | 19 | 21 |
|G | 3 | F | 21 | 24 | 21 | 24 |
|H | 6 | G | 24 | 30 | 24 | 30 |

New project duration: 28 days

New critical path: A-B-C-D-E-G-H

Was crashing effective? Why or why not? Crashing was partially effective. Shortening Activity D reduced the total project time because it is on the critical path, but crashing Activity F did not help the final deadline since the project is still constrained by the longer duration of path D-E. Activity F now has "slack," meaning it could have been finished later without delaying the project.
