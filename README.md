# BruteForceSSH
Brute Force SSH  &amp; Multithreading

- windows和linux均可运行

- 以上两个脚本在同一个文件夹下，并且当进入shell后，会在同文件夹下创建log.txt记录交互日志

- 用户名字典和密码字典默认路径是同一文件夹下的username_list.txt和username_list.txt

- shell对话依赖于interactive.py

- 爆破程序入口 start.py
```
PS F:\SSHBF> python .\start.py -h
Usage: Usage start.py -H <host_ip> -p <Post>

Options:
  -h, --help           show this help message and exit
  -H TGTHOST           target host ip 
  -p TGTPORT           target host port
  --uf=USERNAMES_FILE  usernames file, txt is adapted
  --pf=PASSWORDS_FILE  passwords file, txt is adapted
  --timeout=TIMEOUT    set timeout defalut 1
```

  
  
