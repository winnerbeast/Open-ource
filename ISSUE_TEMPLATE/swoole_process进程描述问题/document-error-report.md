---
name: Document error report  
about: Create a report to help us improve  
title: "[SWOOLE_PROCESS](https://wiki.swoole.com/#/learn?id=diff-process)"
labels: documentation  
assignees: sy-records

---

* 文档链接: `https://wiki.swoole.com/#/learn?id=diff-process`  
* 实际内容: 
![错误描述](./img\swoole_process.png)
* 期望内容:   
  
- Swoole的Master是单进程多线程的模式，那在Swoole_Process模式下，客户端发送的TCP连接应该是和Master进程内部的Reactor线程建立TCP连接。 这样就不会涉及到进程管理和进程间的通信。多线程里面一般不是共享进程资源吗？    
 

