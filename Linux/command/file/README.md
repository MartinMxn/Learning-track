### Open file:  
-a option means "open the file argument with the **n'a'med application**":  
open -a TextEdit file.txt

-e option means "open the file argument with the **Text'E'dit application**":  
open -e file.txt

-t option means "open the file with the default application for editing text files, as determined via LaunchServices". By default, this will be /Applications/TextEdit.app; however, it's possible for this setting to get overridden:  
open -t file.txt

### mkdir
make new dictionary with space:  
#### mkdir name\ with\ space  
or  
#### mkdir 'name with space'

### rm
```
-f ：就是force的意思，忽略不存在的文件，不会出现警告消息
-i ：互动模式，在删除前会询问用户是否操作
-r ：递归删除，最常用于目录删除
```
rm -f dif 保险
rm -fr dir 删除文件夹下所有

### kill 
```
1：SIGHUP，启动被终止的进程
2：SIGINT，相当于输入ctrl+c，中断一个程序的进行
9：SIGKILL，强制中断一个进程的进行
15：SIGTERM，以正常的结束进程方式来终止进程
17：SIGSTOP，相当于输入ctrl+z，暂停一个进程的进行
```
kill 9 PID stop some process

