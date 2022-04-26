# CD Module

## CD - Change Directory

| Command          | Description                                   | Flags                                                    |
| ---------------- | --------------------------------------------- | -------------------------------------------------------- |
| `cd /tmp`        | CD to specific directory                      |                                                          |
| `cd /tmp/data`   | CD to specific directory under /tmp           |                                                          |
| `cd`             | Just CD will take you to home dir             |                                                          |
| `cd ~ `          | Will take you back to home dir                | `~` = refers home dir associated with specified username |
| `cd ..`          | CD to parent dir of current working dir       | `..` = refers parent dir of current working dir          |
| `cd ../..`       | Navigates 2 step ahead of current working dir |                                                          |
| `cd ../../../..` | Switch four steps ahead.                      |                                                          |

# CAT Module

| Command               | Description                             |
| --------------------- | --------------------------------------- |
| `cat filename`        | view the file which is in same dir      |
| `cat /tmp/filename`   | view the file which is in different dir |
| `cat ../filename`     | view the file which is in parent dir    |
| `cat ../../filename ` | view a file which is two steps ahead    |