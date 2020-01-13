Open file:  
-a option means "open the file argument with the **n'a'med application**":  
open -a TextEdit file.txt

-e option means "open the file argument with the **Text'E'dit application**":  
open -e file.txt

-t option means "open the file with the default application for editing text files, as determined via LaunchServices". By default, this will be /Applications/TextEdit.app; however, it's possible for this setting to get overridden:  
open -t file.txt
