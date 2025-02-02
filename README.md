难绷，才弄了就几个就发现人家官网有分类查询，建议直接去官网看：https://hellogithub.com/periodical

![image](https://github.com/user-attachments/assets/81b6b133-d80e-4470-915d-ec260c2d8749)


# HelloGithub-CPP
Summary of C++ Projects in the HelloGitHub Monthly Magazine by 521xueweihan
对 521xueweihan/HelloGitHub 中 C++ 项目汇总 

# HelloGitHub 月刊中 C++ 项目汇总
## 1. Ladybird
- **Star**: 1.2w
- **Fork**: 476
- **更新时间**: 15 天前
- **详情**: 真正独立的开源浏览器。该项目作者旨在从头构建一个真正独立的 Web 浏览器，他从自己编写的 SerenityOS 操作系统中分离出浏览器引擎部分，计划基于此打造一个全新、跨平台的开源浏览器。目前项目处于早期阶段，尚未发布可供下载的安装包。
## 2. Mosh
- **Star**: 1.2w
- **Fork**: 727
- **更新时间**: 15 天前
- **详情**: 适用于移动端的远程终端工具。这是一款专为移动和不稳定网络环境设计的远程终端工具，能够在网络切换、高延迟和 IP 变化的情况下，保持远程会话的稳定和快速响应，适用于 Android、iOS、Linux 和 macOS 等系统。
## 3. OpenArk
- **Star**: 8.4k
- **Fork**: 839
- **更新时间**: 15 天前
- **详情**: 专业的 Windows 恶意程序分析与清理工具。这是一款 Windows 平台上的对抗和清理 Rootkit（恶意程序）的工具，能够帮助用户发现系统中隐藏的恶意软件，支持查看进程、进程注入、内核驱动模式和扫描等功能。
## 4. Caesium-Image-Compressor
- **Star**: 3.3k
- **Fork**: 201
- **更新时间**: 1 个月前
- **详情**: 免费的图片压缩软件。这是一款用 C++ 编写的图片压缩工具，拥有简洁的中文界面，支持 JPG、PNG 和 WebP 格式的无损压缩，同时具备实时预览和批量处理功能。此外，还提供了 Windows、Linux 和 macOS 客户端，以及无需安装的 Web 版本。
## 5. Concurrentqueue
- **Star**: 9.5k
- **Fork**: 1.7k
- **更新时间**: 1 个月前
- **详情**: C++ 的高性能无锁并发队列。该项目使用 C++11 编写，是一个快速、无锁、并发的队列，支持多个线程同时进行生产者和消费者操作。它无需使用锁且只有一个头文件，适用于需要高性能并发处理的各种场景。
```cpp
#include "concurrentqueue.h"
moodycamel::ConcurrentQueue<int> q;
q.enqueue(25);
int item;
bool found = q.try_dequeue(item);
assert(found && item == 25);
```
## 6. Input-Overlay
- **Star**: 2.6k
- **Fork**: 238
- **更新时间**: 1 个月前
- **详情**: 显示用户操作输入的 OBS 直播插件。该项目用于在直播中显示键盘按键、鼠标移动和游戏手柄按钮的插件，适用于 Windows 和 Linux 上的 OBS 直播软件，可用于游戏直播和教学演示等场景。
## 7. Cppinsights
- **Star**: 3.9k
- **Fork**: 235
- **更新时间**: 2 个月前
- **详情**: 从编译器的视角看 C++ 的代码。这是一个基于 Clang 的开发工具，可以将源代码转化为编译器的推导结果，让用户从编译器的视角深入了解代码的内部机制，可以用来展示和讲解抽象语法树（AST）和 C++ 语言的新特性。
## 8. Stellarium
- **Star**: 7.3k
- **Fork**: 802
- **更新时间**: 2 个月前
- **详情**: 一款开源的天象模拟软件。该项目是天文爱好者的必备工具，能够精确地模拟/展示出头顶星空的景象，包括恒星、星座、行星、彗星等天体，支持选择时间和地点、放大观察、图解星座等功能，提供了 Windows、Linux、macOS、iOS 和 Android 等多个平台客户端。
## 9. VideoPipe
- **Star**: 1.2k
- **Fork**: 169
- **更新时间**: 2 个月前
- **详情**: 跨平台的视频结构化和分析框架。这是一个用于视频分析和结构化的框架，采用 C++ 编写、依赖少、易上手。它像管道一样，每个节点相互独立，可自行搭配构建出不同类型的视频分析管道，适用于视频结构化、图片搜索、人脸识别、安防领域的行为分析（如交通事件检测）等场景。
## 10. Ada
- **Star**: 1.3k
- **Fork**: 78
- **更新时间**: 3 个月前
- **详情**:

