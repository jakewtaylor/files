## Blank Lines

Matches blank lines that contain whitespace.

```RegEx
/(\S)?( |\t)+(\r\n|\r|\n)/g
```

Search and replace with: `$1$3` to remove the whitespace from the lines.

:snail:
