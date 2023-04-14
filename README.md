# ipspy

```
D:\ipspy.exe -h
https://github.com/ipspy
ipspy 0.1

NAME:
   ipspy - Niubility IP address scanning spy tool

USAGE:
   ipspy [global options] command [command options] [arguments...]

COMMANDS:
   spyipc, ipc  specify all protocol to spy ipc
   spyips, ips  specify all protocol to spy ips
   help, h      Shows a list of commands or help for one command

GLOBAL OPTIONS:
   --thread value, -t value   number of concurrency (default: cpu * 20)
   --timeout value, -m value  packet sending timeout millisecond (default: 500)
   --help, -h                 show help (default: false)
```

- ipspy.exe ipc 
  - 一键扫描存活的IP段，如果存在ipb.txt则扫描自定义的B段中存活的C段。否则扫描整个默认内网IP网段。
- ipspy.exe ips
  - 一键扫描ipc.txt中存活的单个IP地址。
- 程序运行后自动对ipc.txt和ips.txt去重。

**Todo**

- 提升扫描速度
- 添加多种识别协议
- 经过多次实战的洗礼