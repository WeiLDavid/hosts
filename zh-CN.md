Need English Version? <a href="https://github.com/WeiLDavid/hosts/blob/Wiki/en-US.md">Click here</a>.

# 总览
<br>用于自由在网络冲浪的工具
<br>
# 安装方法
<br><b>- Windows系统</b>
<br>   1. 拷贝"<a href="https://raw.githubusercontent.com/WeiLDavid/hosts/yt/README.md">yt</a>", "<a href="https://raw.githubusercontent.com/WeiLDavid/hosts/psd/README.md">psd</a>", "<a href="https://github.com/racaljk/hosts/raw/master/hosts">main</a>(<a href="https://coding.net/u/scaffrey/p/hosts/git/raw/master/hosts">mirror</a>)"以及 "<a href="https://github.com/WeiLDavid/hosts/raw/dm/dm">dm</a>"到"%windir%\system32\driver\etc\"中的"<b>hosts</b>"文件<br>

#### <a href="###">注意: 一定要按照顺序添加, 不要更换顺序(即:yt-psd-main-dm)</a>

<br>   2. 按"WinKey-R"然后运行"ipconfig /flushdns"
<br>    
<br><b>- Linux系统</b>
<br>    直接拷贝到"/etc/hosts"
<br>  <b>或遵循以下方法</b>
<br>    1.创建一个文件, 将hosts中的内容拷贝进去
<br>    2.按下"Ctrl-T".
<br>    3.输入 "sudo -s" 然后输入用户密码并遵循步骤 4-1 (不要理会 4-2)
<br>      或输入 "su <用户名>" 然后输入密码并跳到 4-1 不要管 4-2.
<br>      或跳到 4-2 不要管 4-1.
<br>    4-1.输入 "mv <你在第一步创建的文件的绝对路径> /etc/hosts"
<br>    4-2.输入 "sudo mv <你在第一步创建的文件的绝对路径> /etc/hosts" 并输入密码
<br>    5. 重新启动计算机.
<br>  
<br>  
<br>  <b>- 其他操作系统</b> (such as Android, Mac OSX, etc.) 
<br>     删除原hosts文件再拷贝新文件
<br>
# 版权
  <br>Main : Created by <a href="https://github.com/racaljk">racaljk</a> (Project <a href="https://github.com/racaljk">racaljk</a>/<a href="https://github.com/racaljk/hosts">hosts</a>)
  <br>YouTube : Created by WeiLDavid
  <br>Playstore Download: Created by WeiLDavid
<br>
# 如果在替换后出现无效情况, 请按以下步骤操作
将原"main"文件源替换成<a href="https://github.com/WeiLDavid/gohosts-file-mirror/raw/master/hosts">备用源</a>(来自<a href="https://play.google.com/store/apps/details?id=com.lerist.go_hosts">Go Hosts</a>)
