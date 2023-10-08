# Site Reliability Engineer (SRE) 面试准备指南

该repository旨在整合有用的面试资源。

## 贡献

参看 [contribution guidelines](CONTRIBUTING.md) .
欢迎提交更新!

## 基础知识

- [ ] 简单: [当你在浏览器中键入“www.cnn.com”时会发生什么?](https://syedali.net/2013/08/18/what-happens-when-you-type-in-www-cnn-com-in-your-browser)
- [ ] 详细: [当你在浏览器的地址框中键入google.com并按enter键时会发生什么?](https://github.com/alex/what-happens-when)

## Linux

- [ ] [每个SRE都应该了解GNU/Linux shell相关：文件描述符、管道、终端、用户会话、进程组和守护进程](https://biriukov.dev/docs/fd-pipe-session-terminal/0-sre-should-know-about-gnu-linux-shell-related-internals-file-descriptors-pipes-terminals-user-sessions-process-groups-and-daemons)

### 启动过程

- [ ] [Linux引导和启动过程简介](https://opensource.com/article/17/2/linux-boot-and-startup)
- [ ] [当我们开机时会发生什么?](https://www.cdn.geeksforgeeks.org/what-happens-when-we-turn-on-computer)
- [ ] [当我们开机时会发生什么?](https://leetcode.com/discuss/interview-question/125107/What-happens-when-we-turn-on-computer)
- [ ] [从启动到登录提示](http://www.scott-a-s.com/files/linux_boot.pdf)

### 文件系统

- [ ] [理解Inodes](https://syedali.net/2015/02/08/understanding-inodes)
- [ ] [通过示例理解 UNIX / Linux Inodes 基础](https://www.thegeekstuff.com/2012/01/linux-inodes)
- [ ] [理解 proc filesystem](https://syedali.net/2013/08/20/understanding-proc-filesystem)
- [ ] [常见的挂载选项](https://syedali.net/2015/01/06/common-mount-options)
- [ ] [理解 Linux 文件系统: ext4](https://opensource.com/article/18/4/ext4-filesystem)

### 内核

- [ ] [Linux内核基础知识详解](http://learnlinuxconcepts.blogspot.com/2014/03/explain-basics-of-linux-kernel.html)
- [ ] [内核空间和用户空间](http://learnlinuxconcepts.blogspot.com/2014/02/kernel-space-and-user-space.html)
- [ ] [Linux内核之进程管理](http://learnlinuxconcepts.blogspot.com/2014/03/process-management.html)
- [ ] [Linux寻址](http://learnlinuxconcepts.blogspot.com/2014/02/linux-addressing.html)
- [ ] [Linux内核之内存管理](http://learnlinuxconcepts.blogspot.com/2014/02/linux-memory-management.html)
- [ ] [栈和堆](http://learnlinuxconcepts.blogspot.com/2014/02/stack-and-heap.html)
- [ ] [分页和分段](http://learnlinuxconcepts.blogspot.com/2014/02/paging-and-segmentation.html)
- [ ] [Linux内核之系统调用](http://learnlinuxconcepts.blogspot.com/2014/02/system-calls.html)
- [ ] [虚拟文件系统](http://learnlinuxconcepts.blogspot.com/2014/10/the-virtual-filesystem.html)
- [ ] [并发和竞态条件](http://learnlinuxconcepts.blogspot.com/2014/07/concurrency-and-race-conditions.html)
- [ ] [内存泄露](https://stackoverflow.com/questions/312069/the-best-memory-leak-definition)
- [ ] [什么是内核错误?](http://learnlinuxconcepts.blogspot.com/2014/07/what-is-kernel-panic.html)
- [ ] [Linux内核启动](https://0xax.gitbooks.io/linux-insides/content)

### 故障定位

- [ ] [Linux 故障定位工具](https://syedali.net/2013/08/20/linux-troubleshooting-tools)
- [ ] [Linux 性能分析in 60,000 Milliseconds](https://medium.com/netflix-techblog/linux-performance-analysis-in-60-000-milliseconds-accc10403c55)
- [ ] [strace](https://www.dedoimedo.com/computers/strace.html)
- [ ] [lsof](https://www.dedoimedo.com/computers/lsof.html)
- [ ] [Linux系统debug](https://www.dedoimedo.com/computers/linux-system-debugging-super.html)
- [ ] [在SaaS上测试用户故障定位能力](https://sadservers.com)

## 网络

- [ ] [从第一性原则解释网络](https://explained-from-first-principles.com/internet)
- [ ] [编程人员需要了解的网络协议](https://www.destroyallsoftware.com/compendium/network-protocols?share_key=97d3ba4c24d21147)
- [ ] [Linux虚拟网络接口介绍](https://developers.redhat.com/blog/2018/10/22/introduction-to-linux-interfaces-for-virtual-networking)
- [ ] [Multi-tier Linux负载均衡](https://vincent.bernat.ch/en/blog/2018-multi-tier-loadbalancer)
- [ ] [现代网络负载均衡和代理介绍](https://blog.envoyproxy.io/introduction-to-modern-network-load-balancing-and-proxying-a57f6ff80236)
- [ ] [负载均衡算法](https://syedali.net/2013/08/22/load-balancing-algorithms)

## 容器

- [ ] [Docker和容器介绍](http://container.training/intro-selfpaced.yml.html)
- [ ] [Containers Patterns](https://l0rd.github.io/containerspatterns)
- [ ] [Docker Container Anti Patterns](https://blog.couchbase.com/docker-container-anti-patterns/)
- [ ] [Anti-Patterns When Building Container Images](https://jpetazzo.github.io/2021/11/30/docker-build-container-images-antipatterns)

## Kubernetes

- [ ] [使用Docker和Kubernetes部署和扩容微服务](http://container.training/kube-selfpaced.yml.html)
- [ ] [揭开Kubernetes冰山的神秘面纱](https://asankov.dev/blog/2022/05/15/demystifying-the-kubernetes-iceberg-part-1)
- [ ] [What happens when ... Kubernetes edition!](https://github.com/jamiehannaford/what-happens-when-k8s/blob/master/README.md)
- [ ] [Kubernetes生产模式](https://github.com/gravitational/workshop/blob/master/k8sprod.md)
- [ ] [Kubernetes生产环境最佳实践](https://learnk8s.io/production-best-practices)
- [ ] [Kubernetes网络模型指南](https://sookocheff.com/post/kubernetes/understanding-kubernetes-networking-model)
- [ ] [了解47件事情变成Kubernetes专家](https://ymmt2005.hatenablog.com/entry/k8s-things)
- [ ] [Kubernetes最佳实践101](https://github.com/diegolnasc/kubernetes-best-practices)
- [ ] [每个开发人员需要了解的15个Kubernetes最佳实践](https://spacelift.io/blog/kubernetes-best-practices)
- [ ] [KUBERNETES网络指南](https://www.tkng.io)
- [ ] [Kubernetes中DNS查询的生命周期](https://www.nslookup.io/learning/the-life-of-a-dns-query-in-kubernetes)

## 基础设施作为代码和配置管理

- [ ] [Terraform](https://learn.hashicorp.com/terraform)
- [ ] [Terraform综合指南](https://blog.gruntwork.io/a-comprehensive-guide-to-terraform-b3d32832baca)
- [ ] [Ansible](https://github.com/leucos/ansible-tuto)
- [ ] [Getting Started With Terraform on AWS](https://spacelift.io/blog/terraform-tutorial)
- [ ] [Google Cloud: Terraform最佳实践](https://cloud.google.com/docs/terraform/best-practices-for-terraform)

## 数据库

- [ ] [数据库应知应会](https://architecturenotes.co/things-you-should-know-about-databases)
- [ ] [7个数据库范式](https://youtu.be/W2Z7fbCLSTw)
- [ ] [CAP定理](https://en.wikipedia.org/wiki/CAP_theorem)
- [ ] [数据库设计进化](https://martinfowler.com/articles/evodb.html)
- [ ] [ACID vs BASE in Databases](https://medium.com/geekculture/acid-vs-base-in-databases-1bcad774da26)
- [ ] [理解数据库分片](https://www.digitalocean.com/community/tutorials/understanding-database-sharding)
- [ ] [数据库复制]](https://galeracluster.com/library/documentation/tech-desc-introduction.html#database-replication)
- [ ] [SQL vs. NoSQL Database: When to Use, How to Choose](https://towardsdatascience.com/datastore-choices-sql-vs-nosql-database-ebec24d56106)
- [ ] [数据库索引如何生效?](https://planetscale.com/blog/how-do-database-indexes-work)
- [ ] [Redis Explained](https://architecturenotes.co/redis)
- [ ] [Database Sharding Explained](https://architecturenotes.co/database-sharding-explained)

## CI/CD

- [ ] [7 Pipeline Design Patterns for Continuous Delivery](https://www.singlestoneconsulting.com/blog/7-pipeline-design-patterns-for-continuous-delivery)
- [ ] [CI/CD patterns](https://continuousdelivery.com/implementing/patterns)
- [ ] [6个应用部署策略](https://thenewstack.io/deployment-strategies)

## 公有云

- [ ] [The Open Guide to Amazon Web Services](https://github.com/open-guides/og-aws)
- [ ] [Learning Azure](https://docs.microsoft.com/en-us/learn/azure/)
- [ ] [Hands-On Training with GCP](https://cloud.google.com/training/badges)

## 编程

### Python

- [ ] [Python基础](https://pythonbasics.org/)
- [ ] [Python For Everyone](https://www.py4e.com/)
- [ ] [Complete Python Tutorial](https://www.scaler.com/topics/python/)

### Go (Golang)

- [ ] [Go教程](https://tour.golang.org)
- [ ] [Go示例](https://gobyexample.com)
- [ ] [Go教程和示例](https://gosamples.dev)
- [ ] [Learn Go with Tests](https://quii.gitbook.io/learn-go-with-tests/)
- [ ] [Getting up and running with Go](http://www.golangprograms.com)
- [ ] [Go高效编程](https://golang.org/doc/effective_go.html)
- [ ] [Go设计模式](https://github.com/tmrts/go-patterns)
- [ ] [Go内存管理](https://povilasv.me/go-memory-management)
- [ ] [Go代码规范](https://google.github.io/styleguide/go/guide)
- [ ] [Style Decisions](https://google.github.io/styleguide/go/decisions)
- [ ] [Go最佳实践](https://google.github.io/styleguide/go/best-practices)
- [ ] [50 Shades of Go: Traps, Gotchas, and Common Mistakes for New Golang Devs](https://devs.cloudimmunity.com/gotchas-and-common-mistakes-in-go-golang)

### Big O Notation, Algorithms and Data Structures

- [ ] [AlgoExperts](https://www.algoexpert.io)
- [ ] [Hacking a Google Interview – Handout 1](http://courses.csail.mit.edu/iap/interview/Hacking_a_Google_Interview_Handout_1.pdf)
- [ ] [Hacking a Google Interview – Handout 2](http://courses.csail.mit.edu/iap/interview/Hacking_a_Google_Interview_Handout_2.pdf)
- [ ] [Hacking a Google Interview – Handout 3](http://courses.csail.mit.edu/iap/interview/Hacking_a_Google_Interview_Handout_3.pdf)

## 系统设计

- [ ] [SystemsExpert course from AlgoExpert](https://www.algoexpert.io/se/product)
- [ ] [Grokking the System Design Interview](https://www.educative.io/collection/5668639101419520/5649050225344512)
- [ ] [系统设计入门](https://github.com/donnemartin/system-design-primer)
- [ ] [突破系统设计面试](https://www.puncsky.com/blog/2016/02/14/crack-the-system-design-interview)
- [ ] [IT公司系统设计面试](https://github.com/checkcheckzz/system-design-interview)
- [ ] [网站架构 101](https://medium.com/storyblocks-engineering/web-architecture-101-a3224e126947)
- [ ] [What's in a Production Web Application?](https://web.archive.org/web/20210106095747/http://stephenmann.io/post/whats-in-a-production-web-application)
- [ ] [分布式系统](http://book.mixu.net/distsys/single-page.html)
- [ ] [故障容错](https://blog.alexewerlof.com/p/failover)

### 系统设计示例

- [ ] [设计 WhatsApp](http://highscalability.com/blog/2022/1/3/designing-whatsapp.html)
- [ ] [设计 Uber](http://highscalability.com/blog/2022/1/25/designing-uber.html)
- [ ] [设计 Tinder](http://highscalability.com/blog/2022/1/17/designing-tinder.html)
- [ ] [设计 Instagram](http://highscalability.com/blog/2022/1/11/designing-instagram.html)
- [ ] [设计 Netflix](http://highscalability.com/blog/2021/12/13/designing-netflix.html)

## 监控

- [ ] [SLOs & You: A Guide To服务等级目标](https://www.circonus.com/2018/07/a-guide-to-service-level-objectives)
- [ ] [Setting up Service Monitoring — The Why’s and What’s](https://amitosh.medium.com/the-whys-and-what-s-of-setting-up-service-monitoring-cc1c165ee088)
- [ ] [How NOT to Measure Latency](https://youtu.be/lJ8ydIuPFeU)
- [ ] [The four Golden Signals of Kubernetes monitoring](https://sysdig.com/blog/golden-signals-kubernetes)

### Prometheus

- [ ] [Introduction to Prometheus](https://training.promlabs.com/training/introduction-to-prometheus/training-overview/introduction)
- [ ] [Prometheus Relabeling Training](https://training.promlabs.com/training/relabeling/training-overview/prerequisites)
- [ ] [Avoid These 6 Mistakes When Getting Started With Prometheus](https://promlabs.com/blog/2022/12/11/avoid-these-6-mistakes-when-getting-started-with-prometheus)
- [ ] [A Deep Dive Into the Four Types of Prometheus Metrics](https://www.timescale.com/blog/four-types-prometheus-metrics-to-collect)
- [ ] [How Prometheus Querying Works](https://www.timescale.com/blog/how-prometheus-querying-works-and-why-you-should-care)
- [ ] [PromQL Cheat Sheet](https://promlabs.com/promql-cheat-sheet)

## Processes

- [ ] [The practical guide to incident management](https://incident.io/guide)
- [ ] [Incident Response](https://response.pagerduty.com)
- [ ] [Postmortems](https://postmortems.pagerduty.com)
- [ ] [Runbooks](https://www.transposit.com/devops-blog/itsm/what-makes-a-good-runbook)
- [ ] [Identifying and tracking toil using SRE principles](https://cloud.google.com/blog/products/management-tools/identifying-and-tracking-toil-using-sre-principles)
- [ ] [Building SRE from Scratch](https://medium.com/ibm-garage/building-sre-from-scratch-485e23985bbd)
- [ ] [SRE at Google: Our complete list of CRE life lessons](https://cloud.google.com/blog/products/devops-sre/sre-at-google-our-complete-list-of-cre-life-lessons)
- [ ] [Incident Management vs. Incident Response - What's the Difference?](https://rootly.io/blog/incident-management-vs-incident-response-what-s-the-difference)
- [ ] [Practical Guide to SRE: Using SLOs to Increase Reliability](https://rootly.io/blog/practical-guide-to-sre-using-slos-to-increase-reliability)
- [ ] [Practical Guide to SRE: Automating On-Call](https://rootly.io/blog/practical-guide-to-sre-automating-on-call)
- [ ] [从小白到SRE](https://www.squadcast.com/blog/going-from-zero-to-sre)
- [ ] [An Incident Command Training Handbook](https://blog.danslimmon.com/2019/06/24/an-incident-command-training-handbook)
- [ ] [Howie guide to post‑incident investigations](https://www.jeli.io/howie/welcome)
- [ ] [LinkedIn’s SRE实践详解](https://www.srepath.com/rundown-of-linkedins-sre-practices)
- [ ] [Uber’s SRE实践详解](https://www.srepath.com/rundown-of-uber-sre-practice)
- [ ] [现实世界的SRE](https://blog.relyabilit.ie/sre-in-the-real-world)
- [ ] [SRE Engagement Models](https://certomodo.substack.com/p/sre-engagement-models)
- [ ] [SRE检查清单](https://github.com/bregman-arie/sre-checklist)
- [ ] [为啥要区分SLI和SLO](https://blog.alexewerlof.com/p/why-bother-with-sli-and-slo)
- [ ] [系统弹性金字塔](https://www.codereliant.io/the-system-resiliency-pyramid)

## 简历

- [ ] [SRE 简历优化指南](https://rootly.com/blog/sre-complete-resume-writing-guide)

## 面试

### SRE 面试过程

- [ ] [如何招聘SRE人才](https://syedali.net/2014/04/01/how-to-hire-talent)
- [ ] [谷歌SRE招聘流程](https://web.archive.org/web/20220328124724/http://lambda-startup.com/recruitment-process-for-a-google-job-sre-site-reliability-engineer)

### 面试问题

- [ ] [SRE 面试问题集](https://github.com/michael-kehoe/sre-interview)
- [ ] [SRE 面试问题](https://syedali.net/engineer-interview-questions)
- [ ] [系统管理员 Test Questions](https://github.com/trimstray/test-your-sysadmin-skills)
- [ ] [Kubernetes job 面试问题](https://enterprisersproject.com/article/2019/2/kubernetes-job-interview-questions-how-prepare)
- [ ] [DevOps 指南](https://github.com/Tikam02/DevOps-Guide)
- [ ] [我在SRE面试中问的问题](https://dev.to/logan/questions-i-ask-in-sre-interviews-a9j)
- [ ] [DevOps 路线图: 如何成为 DevOps 工程师 或 SRE](https://roadmap.sh/devops)
- [ ] [The Must-Know Terraform 面试问题](https://devopsknowledge.hashnode.dev/the-must-know-terraform-interview-questions)

### 博客

- [ ] [SRE Interviews in Silicon Valley](http://blog.marc-seeger.de/2015/05/01/sre-interviews-in-silicon-valley)
- [ ] [SRE面试准备](https://blog.balthazar-rouberol.com/preparing-the-sre-interview)
- [ ] [如何成为SRE](https://blog.alicegoldfuss.com/how-to-get-into-sre)
- [ ] [Google面试记录](https://catonmat.net/my-job-interview-at-google)
- [ ] [成为运维管理者路径](https://danrl.com/srm)
- [ ] [如何成为SRE](https://www.tik.dev/blog/becoming-an-sre)
- [ ] [我是如何获得Google SRE offer](https://fabrizio2210.medium.com/how-i-get-a-job-at-google-as-sre-83d44aef7859)
- [ ] [Become A DevOps Engineer in 2023: [Detailed Guide]](https://devopscube.com/become-devops-engineer)
- [ ] [如何获得一份SRE工作](https://certomodo.substack.com/p/how-to-get-an-sre-role)

## 书籍

### SRE书籍

- [ ] [网站可靠性工程](https://sre.google/sre-book/table-of-contents)
- [ ] [网站可靠性工作手册](https://sre.google/workbook/table-of-contents)
- [ ] [Seeking SRE](https://books.google.ru/books?id=tmhqDwAAQBAJ)
- [ ] [打造安全可靠的系统](https://sre.google/books/building-secure-reliable-systems)
- [ ] [落地服务等级目标](https://learning.oreilly.com/library/view/implementing-service-level/9781492076803)

### Linux

- [ ] [Linux内核开发 (第三版)](https://www.amazon.com/Linux-Kernel-Development-Robert-Love/dp/0672329468)
- [ ] [UNIX 和 Linux 系统管理员手册 (第5版)](https://www.amazon.com/UNIX-Linux-System-Administration-Handbook/dp/0134277554)
- [ ] [Linux 口袋手册, 第三版](http://shop.oreilly.com/product/0636920040927.do)

### 网络

- [ ] [TCP/IP Illustrated, Volume 1](https://www.amazon.com/TCP-Illustrated-Protocols-Addison-Wesley-Professional/dp/0321336313)

### 故障定位和性能

- [ ] [Systems Performance: Enterprise and the Cloud](https://www.amazon.com/Systems-Performance-Enterprise-Brendan-Gregg/dp/0133390098)
- [ ] [Systems Performance, 2nd Edition](https://www.informit.com/store/systems-performance-9780136820154?ranMID=24808)

## 课程

- [ ] [Site Reliability Engineering: Measuring and Managing Reliability](https://www.coursera.org/learn/site-reliability-engineering-slos)
- [ ] [Linkedin SRE学校](https://linkedin.github.io/school-of-sre)
