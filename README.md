# 2021q3 Homework3 (vpoll)
contributed by < `blue76815` >
[第 4 週測驗題](https://hackmd.io/@sysprog/linux2021-summer-quiz4)


## To do list
- [x] 架設完 quiz4-1 的 debug mode 環境
- [x] **整理程式碼流程，原理**
- [x] 使用 Ftrace 分析
- [ ] 分析 [memory-barriers.txt](https://github.com/torvalds/linux/blob/master/Documentation/memory-barriers.txt) 功能(先翻譯讀完裡面的文章介紹)
並整理出以下API的功能
    - [ ] [並行程式設計: Atomics 操作]
- [ ] 修改 `vpoll `核心模組，實作效能評比的特別模式，從而分析 `epoll` 效能 
    - [ ] 參閱 [Epoll Kernel Performance Improvements](https://events19.linuxfoundation.org/wp-content/uploads/2018/07/dbueso-oss-japan19.pdf)
    - [ ] 參閱 [linux-ipc-benchmarks](https://github.com/kamalmarhubi/linux-ipc-benchmarks)    
## 預備知識
目的: 檢驗學員對 

- [ ] 1. [Atomics 操作](https://hackmd.io/@sysprog/concurrency-atomics) 
- [ ] 2. [Lock-Free Programming](https://hackmd.io/@sysprog/concurrency-lockfree) 
- [ ] 3. [事件驅動伺服器：原理和實例](https://hackmd.io/@sysprog/event-driven-server) 
- [ ] 4. [The Linux Kernel Module Programming Guide](https://sysprog21.github.io/lkmpg/)
- [ ] 5. 研究 [memory-barriers.txt](https://github.com/torvalds/linux/blob/master/Documentation/memory-barriers.txt)


---
## 程式碼原理分析
[quiz4 vpoll 操作方式和程式解析](https://hackmd.io/@blue76815/quiz4_vpoll_trace_code)

## ftrace 分析
[(總結) quiz4 vpoll ftrace分析](https://hackmd.io/@blue76815/quiz4_vpoll_ftrace)