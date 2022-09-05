POSITION
- LEFT h
- RIGHT l
- UP k
- DOWN j

- NUMBER ACTION WITH NUMBER TIME OF ACTION
  example:
  press 5 and k
  will jump up 5 time

INSERT MODE
- i INSERT in cursor
- o INSERT with Enter
- a INSERT next word in cursor
- I INSERT start of line
- O INSERT top o line
- A INSERT end of line
- s INSERT mode and replace in cursor
- S INSERT and remove cursor line

MOVEMENT
- w skip forward
- e skip forward end of word 
- b skip backword 
- gg goto top of file 
- G goto bottom of line
- Shift + } skip forward where there is space 
- Shift + { skip backward where there is spsace 
- }} goto end of line
- {{ goto top of line

NORMAL MODE ACTION
- d DELETE 
- dd delete cursor line
- D DELETE from start cursor 
- di DELETE from cursor til next line
- dw DELETE from cursor will end of line
- diw DELETE word where in cursor
- c and C all action is the same with d but will ENTER INSERT MODE after done action
- x remove backward
- $ move to end of line
- 0 move to start of line
- f + {search text} move to search text match 
  example:
    string = "This is example text"
    f + l 
    will move to exmaple word where l contained
- yy copy line
- p paste in cursor
- P paste with new line
- . DO PREVIOUS ACTION

VISUAL MODE
- v ENTER select mode
- v + MOVEMENT + NORMAL ACTION MODE
