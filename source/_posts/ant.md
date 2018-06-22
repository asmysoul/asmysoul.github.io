---
title: ant
date: 2018-06-17 03:37:56
tags: [开源项目]
categories: 开源项目
---
## Ant

    ant can extract page in an easy way

    just do that 

        AntQueue antQueue = TaskQueue.of();
        antQueue.push(new Task("https://github.com/"));
        Ant ant = Ant.create().startQueue(antQueue).thread(1);
        AntMonitor.getInstance().regist(ant);
        ant.run();

you can download at    [https://github.com/asmysoul/ant](https://github.com/asmysoul/ant)
    

