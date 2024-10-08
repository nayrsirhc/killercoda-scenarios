
# Navigation | `ls`

<br>

### Cheat Sheet
| **Command** | **Description** |
| --- | --- |
| `ls` | List files in the current directory |
| `ls -l` | List files in the current directory in long format |
| `ls -a` | List all files in the current directory, including hidden files |

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
