# 记录python学习:

python 模块：

os模块:    

os.remove()         删除文件  

os.unlink()         删除文件     

os.rename()         重命名文件     

os.listdir()        列出指定目录下所有文件     

os.chdir()          改变当前工作目录    

os.getcwd()         获取当前文件路径    

os.mkdir()          新建目录    

os.rmdir()          删除空目录(删除非空目录, 使用shutil.rmtree())    

os.makedirs()       创建多级目录    

os.removedirs()     删除多级目录    

os.stat(file)       获取文件属性    

os.chmod(file)      修改文件权限    

os.utime(file)      修改文件时间戳    

os.name(file)       获取操作系统标识    

os.system()         执行操作系统命令    

os.execvp()         启动一个新进程    

os.fork()           获取父进程ID，在子进程返回中返回0    

os.execvp()         执行外部程序脚本（Uinx）    

os.spawn()          执行外部程序脚本（Windows）    

os.access(path, mode) 判断文件权限(详细参考cnblogs)    

os.wait()           暂时未知 

os.walk()            会列出当前目录下的子目录中的所有目录和文件，并递归遍历子目录。结果为generator对象

os.path模块：    

os.path.split(filename)         将文件路径和文件名分割(会将最后一个目录作为文件名而分离)    

os.path.splitext(filename)      将文件路径和文件扩展名分割成一个元组    

os.path.dirname(filename)       返回文件路径的目录部分    

os.path.basename(filename)      返回文件路径的文件名部分    

os.path.normcase(path)          转换path的大小写和斜杠    

os.path.isdir()                 判断name是不是一个目录，name不是目录就返回false    

os.path.isfile()                判断name是不是一个文件，不存在返回false   

os.path.islink()                判断文件是否连接文件,返回boolean    

os.path.ismount()               指定路径是否存在且为一个挂载点，返回boolean    

os.path.samefile()              是否相同路径的文件，返回boolean    

os.path.getatime()              返回最近访问时间 浮点型    

os.path.getmtime()              返回上一次修改时间 浮点型    

os.path.getctime()              返回文件创建时间 浮点型    

os.path.getsize()               返回文件大小 字节单位    

os.path.commonprefix(list)      返回list(多个路径)中，所有path共有的最长的路径    

os.path.lexists                 路径存在则返回True,路径损坏也返回True    

os.path.expanduser(path)        把path中包含的"~"和"~user"转换成用户目录    

os.path.expandvars(path)        根据环境变量的值替换path中包含的”$name”和”${name}”    

os.path.sameopenfile(fp1, fp2)  判断fp1和fp2是否指向同一文件    

os.path.samestat(stat1, stat2)  判断stat tuple stat1和stat2是否指向同一个文件    

os.path.splitdrive(path)        一般用在windows下，返回驱动器名和路径组成的元组    

os.path.walk(path, visit, arg)  遍历path，给每个path执行一个函数详细见手册    

os.path.supports_unicode_filenames()     设置是否支持unicode路径名
