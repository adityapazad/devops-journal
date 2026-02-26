# Bash Scripting

### Shebang
First line of the script that tells system which interpreter should execute this file.
`flags` 
    - #!/bin/bash
    - ./script.sh = runs file

### Variables in bash
Variable stored the data.
`flags` 
    - name="John" = Syntax (no space arounf =) 
    - echo $name  = $ is used to access value

### if condition
Allows decision making.
`flags`
    - if [ $age -gt 18]
      then
            command
      fi                    = Syntax
    - fi    = end of if statement
    - -eq   = equal
    - -nq   = not equal
    - -gt   = greater than
    - -lt   = less than

### for loop
Repeat commands multiple times.
`flags`
    - for i in 1 2 3
      do
         echo $i
      done               = Syntax
    - done  = end of loop

### Exit codes
Every commands returns a number after execution. '0' means Success, 'non-zero' means failure.
`flags`
    - $? = stores last command status

### Making script executable
Linux uses permission bits. Without execute permission, OS blocks execution.
`flags`
    - script.sh             = file created
    - chmod +x script.sh    = makes files executable
    - ./script.sh           = runs the file
