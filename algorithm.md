# Algorithm Pseudocode

## Algorithm Task(s)

For a set of publications, determine the (1) number of collaborators and (2) collaboration types.

### Task 1 Code
```
PROGRAM collabNum:  

Open dataset.csv  
Read column authorName
Create column collabNum
Set position to 0  

WHILE (position < length - 1)  
    if (author_count == 1)
        set collabNum[position] to "solo"
        set position to position + 1 
    elseif (author_count == 2)
        set collabNum[position] to "pair"
        set position to position + 1
    else
        set collabNum[position] to "group"
        set position to position +1
```

### Task 2 Code
```
PROGRAM collabType:

Read column collabNum
Read column authorAffiliation
Read column authorCountry
Create column collabType
Set position to 0

WHILE (position < length - 1)
    if (collabNum == "solo")
        set collabType[position] to "solo"
        set position to position +1
    elseif (collabNum == "pair")
        if ()

```