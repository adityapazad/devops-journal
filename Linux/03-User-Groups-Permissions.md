# User, Groups & Permissions

## User
- A user is an individual or a system entity that can log in and access the system. Users in linux are manages through unique accounts with assigned user IDs, permissions and roles.

## Groups
- A group is a collection users. Instead of giving permission to each user individually, Linux allows you to give permission to a group.

## Permissions
- Linux permissions are rules that control who can read, write or execute a file or directory
   - Three permission groups :
      - `Owners (u)` : user who created the file
      - `Group (g)` : users in the same group
      - `Other (o)` : everyone else

## Permission Model
- `rwx` : read, write, execute. Every file has permission for user, groups and other.
- `reading permissions`
   - eg : "drwxrwxr-x 2 ubuntu ubuntu 4096 Oct 11:55 file.txt"
     - d = directory  ('-' instead of 'd'  = file, 'l' = link)
     - rwx = owner, rwx = group, r-x = All Users
     - when permission not given then '-' is given. eg: r-x at the end
     - '2' = number of links (link = another name pointing to same file)
     - ubuntu = owner name
     - ubuntu = group name
     - 4096 = file size in bytes
     - Oct 11:55 = last modified date & time
     - file.txt = file name

- `numeric permissions`
   - r = 4, w = 2, x = 1
   - permissions are added per user|group|others
   - eg: 774 permission
      - user = r + w + x = 7
      - group = rwx
      - others = r--

## Commands
- `sudo` : temporary admin power to do restricted tasks
- `whoami` : displays current logged-in user
- `id` : shows identity details in the system
- `adduser` : create new user account
- `usermod` : modifies an existing user account
- `groups` : shows groups to which a user belongs
- `chmod` : change file or directory permissions
- `chown` : change file or directory owenership
