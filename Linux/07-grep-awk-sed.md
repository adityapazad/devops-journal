# grep, awk, sed

## Regex
Regex is a pattern language for text used inside grep, awk sed. It makes searching powerful.
### Symbols
- `^` : start of line
- `$` : end of line
- `.` : any character
- `*` : 0 or more
- `[abc]` : a or b or c
- `[0-9]` : any digit

### Mental Model
`grep` : find
`awk` : extract
`sed` : modify

## Commands
- `grep` : used to search for specific words, pattern, phrases inside text files
    - `grep -i` "error" file    # ignore case
    - `grep -n` "error" file    # show line numbers
    - `grep -v` "error" file    # show lines NOT matching
    - `grep -r` "text" folder/  # recursive search

- `awk` : column-based text processor for structured logs
    - `{print $1}`
    - `{print $1, $3}`
    - `-F` to change delimiter
    - `eg` : awk -F ":" '{print $1}' /etc/passwd

- `sed` : steam editor, it modify text
    - `s/old/new/` = substitute
    - `g` = global
    - `-i` = modify file directly
    - `eg` : sed 's/text1/text2/g'
