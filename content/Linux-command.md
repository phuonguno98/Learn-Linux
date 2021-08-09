<a href="https://www.facebook.com/phuonguno.vn" target="_blank"><img src="../img/facebook-link.PNG" alt="Nguyen Thanh Phuong" style="height: 41px !important;width: 174px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" ></a>

<p align="center">
    <br/>
    <a href="https://github.com/phuonguno98/Learn-Linux/content/Linux-command.md">	
        <img src="../img/Linux_command.PNG" alt="Linux command">
    </a>
</p>



# Brief description of linux commands



### *File Commands*

|Command|Description|
|:----:|----|
|ls|Directory listing|
|ls -al|Formatted listing with hidden files|
|cd `dir`|Change directory to `dir`|
|cd|Change directory to home|
|pwd|Show current directory|
|mkdir `dir`|Create a directory `dir`|
|rm `file`|Delete `file`|
|rm -r `dir`|Delete directory `dir`|
|rm -f `file`|Force remove `file`|
|rm -rf `dir`|Force remove directory `dir`|
|cp `file1` `file2`|Copy `file1` to `file2`|
|cp -r `dir1` `dir2`|Copy `dir1` to `dir2`; create `dir2` if it doesn't exist|
|mv `file1` `file2`|Rename or Remove `file1` to `file2`; if `file2` is an exist directory, moves `file1` into directory `file2`|
|ln -s `file` `link`|Create symbolic link: `link` to `file`|
|touch `file`|Create a plain `file` or Update the timestamp of `file`|
|cat > `file`|Places standard input to `file`|
|more `file`|Output the contents of `file`|
|head `file`|Output the first 10 lines of `file`|
|tail `file`|Output the last 10 lines of `file`|
|tail -f `file`|Output the contents of `file` as it grows, starting with 10 lines|

### *Process Management*

|Command|Description|
|:----:|----|
|ps|Display your currently active processes|
|top|Display all running processes|
|kill `pid`| Kill process id `pid`|
|killall `proc`|Kill all processes named `proc`|
|bg|Lists stopped or background jobs; resume a stopped job in the background|
|fg|Brings the most recent job to foreground|
|fg `job`|Brings `job` to foreground|

### *File Permissions*

|**chmod** `octal` `file`|
|:----:|

Change the permissions of `file` to `octal`, which can be found separately for user, group and world by adding:
* 4 - read (r)
* 2 - write (w)
* 1 - execute (x)

### *SSH*

|Command|Description|
|:----:|----|
|ssh `user@host`|Connect to `host` as `user`|
|ssh -p `port` `user@host`|Connect to `host` on port `port` as `user`|
|ssh-copy-id `user@host`|Add your key to `host` for `user` to enable a keyed or passwordless login|

### *Searching*

|Command|Description|
|:----:|----|
|grep `pattern` `files`|Search `pattern` in `files`|
|grep -r `pattern` `dir`|Search recursively for `pattern` in `dir`|
|`command` \| grep `pattern`|Search for `pattern` in the output of `command`|
|locate `file`|Find all instances of `file`|


## [Back to main page](../README.md)
## License

UNO &copy; [Nguyen Thanh Phuong](https://www.github.com/phuonguno98)
