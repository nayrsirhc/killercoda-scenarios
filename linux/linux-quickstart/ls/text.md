
<br>

### Cheat Sheet
| **Command** | **Description** |
| --- | --- |
| `ls` | List files in the current directory |
| `ls -l` | List files in the current directory in long format |
| `ll` | Short hand for `ls -l` on some systems |
| `ls -a` | List all files in the current directory, including hidden files |
| `ls -la` | List all files in the current directory in long format |
| `ls -lah` | List all files in the current directory in long format, in human readable format |
| `ls -ltr` | List all files in the current directory in long format, sorted by time modified, newest first |

### Solution
Use `ls` to help see whats in the filesystem


We can list the current directory using

```bash
ls
```{{exec}}


We can add parameters to a linux command to change its behaviour, lets try

`-l` - long listing format (Think "long" or "list")
```bash
ls -l
```{{exec}}
`-a` - all files (Think "all")
```bash
ls -a
```{{exec}}
**Note: now you can see my hidden agenda**

You can combine parameters to get the desired output, I like reading out the parameters as a sentence to help remember them

For exmaple lets see a "list" of "all"
```bash
ls -la
```{{exec}}
`-h` - human readable

So lets "list" "all" "human readable"
```bash
ls -lah
```{{exec}}
`-t` - sort by time modified, newest first

Or "list" "all" "human readable" by "time"
```bash
ls -laht
```{{exec}}
`-r` - reverse order

Lets "list" by "time" in "reverse"
```bash
ls -ltr
```{{exec}}
