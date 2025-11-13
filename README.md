#  Hi there 👋, I'm Star-CS <img src="https://media.giphy.com/media/mGcNjsfWAjY5AEZNw6/giphy.gif" width="50">

<table>
  <tr>
    <td><img src="https://github-readme-stats.vercel.app/api?username=star-cs&theme=prussian&show_icons=true" alt="Star-CS's GitHub stats"></td>
    <td><img src="https://github-readme-stats.vercel.app/api/top-langs/?username=star-cs&layout=compact&theme=prussian&size_weight=0.5&count_weight=0.5&hide=javascript,html,css,java" alt="Top Langs"></td>
  </tr>
</table>

# 关于我 👨‍💻
- 27 届双非硕 CPP 选手

# 技术栈 🔨
- C/C++  Linux
- ROS2 CyberRT 
- eBPF (libbpf)

# 项目介绍 🦉

#### [Linux 性能监控平台](https://github.com/star-cs/NodeMonitor)  
- 节点级监控，CPU，内存，存储，网络等性能指标
- 内核模块，eBPF，/proc
- 性能指标分析
- gRPC 通信
- Docker 容器化部署

#### [CyberRT-MX 分布式通信中间件](https://github.com/star-cs/CyberRT-MX)
- 重写 CyberRT 框架
- 原子变量和 CAS 操作实现 采用基础组件
- 设计实现 序列化协议，支持基础数据类型、复合数据类型以及自定义数据类型
- 日志系统，支持动态日志级别、文件自动轮转、流式接口
- 有向图 构建通信拓扑关系，以Node为图顶点，Channel为图边，去中心化广播角色的加入与离开
- 实现基于 FastRTPS 和 共享内存 的两种通信方式，进程间使用共享内存，不同主机间使用 FastRTPS
- 使用观察者模式设计并实现 信号槽 机制，在订阅端为监听的 Channel 绑定槽函数，通过信号槽机制进行回调

## 学习项目 📚
- [鱼香ros2 课程代码](https://github.com/star-cs/ros2bookcode) 
- [libbpf 实践 学习项目](https://github.com/star-cs/libbpf-ebpf-beginer)
- [dpdk 实践 学习项目](https://github.com/star-cs/dpdk-hands-on)
- [C++20协程学习，tinyCoroLab 协程库lab](https://github.com/star-cs/coro) [C++20 协程 +  liburing]  Lab地址[tinyCoroLab](https://github.com/sakurs2/tinyCoroLab)
- 即时聊天 [客户端 QT](https://github.com/star-cs/CChat_client)  [服务器端 Linux](https://github.com/star-cs/CChat_server) 恋恋风辰
- [sylar webserver](https://github.com/star-cs/webserver)
