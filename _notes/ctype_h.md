
## without ctype.h
To identify a letter:
```
if ('A' <= c && c <= 'Z' || 'a' <= c && c <= 'z')
```
To identify a letter:
```
if ('0' <= c && c <= ' 9 ' )
```

To identify white-space
```
  if (c==' ' || c=='\t' || c=='\n')s
```

## ctype.h

iscntrl(int c)
isalnum(int c)
isalpha(int c)
isdigit(int c)
tolower(int c)
toupper(int c)
