# url_sniffer
A url finder from any text/plain file 

## Blog:
https://technotronsite.wordpress.com/2018/06/30/url_sniffer-the-blog/

## Credits:
The regex used has been blindly copied from GeeksforGeeks' regex example (https://www.geeksforgeeks.org/tag/python-regex/)  
So, major credit goes to them.  
This is just a CLI app for the same.  

## Dependency:
Only one that Python3 is installed and all the standard Libraries are available.  
If not please go ahead and install.  
A Note to Windows users: Make sure Python is added to path


## Usage:
### Installation: 
#### (Linux users only):  
```$ git clone https://github.com/t3chn0tr0n/url_sniffer.git && cd url_sniffer && chmod +x setup.py && ./setup.py && cd .. && rm -rf url_sniffer && exit```   


From next time just use `sniffurl` followed by the "path/to/file" you want to sniff for urls, like:    
```$ sniffurl path/to/file```  


You can either save the output in a file, or the result will be displayed anyway!  


### Uninstallation
Just using this command should do the trick:  
```cd ~/.url_sniffer/url_sniffer/ && chmod +x uninstaller.sh && ./uninstaller.sh && exit```


#### Windows users:
Sorry, but no installation available for you guys!  
Download the zip file.  
Now extract it where you want to use/keep!  
If you have Python3 installed and added to path, open cmd.exe, and type:  
```> cd path/where/you/extracted/ && python sniff.py path/to/file```   


## Few known bugs and solutions:  
1. Any emoticon symbols may cause error! remove the manually if so!
2. Since it was developed over Windows and Linux platform, problems with encoding may arrise, esp. for Linux Users    
   Use a program called 'dos2unix' to fix it! Use:  
   ```$ dos2unix ~/.url_sniffer/url_sniffer/sniff.py```
3. `sniffurl` may not be found by the shell if you are using a non-login terminal  
    By default "Run command as Login Shell" is checked, and you can varify yours:  
    `fire-up Gnome terminal > Edit > Preferences > default profile(one with a tick mark) > Command > Run command as Login Shell`

## Last Things last
This piece of software is still in development!  
Expect bugs!  
Please comment if any bug is found! 
