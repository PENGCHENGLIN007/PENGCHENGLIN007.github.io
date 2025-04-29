---
title: iptables
date: 2025-04-24 08:49:05
tags: network
---
# introduction
  iptables 全称netfilter/iptables，是linux的包过滤防火墙，iptables主要负责用户交互，并将用户的配置
转换为netfilter可接受的信息。netfilter工作在网络层，针对IP数据包。netfilter是内核的一部分，属于内核态，
iptables属于用户态。

# data send and receive
![](images/data_send_simple.png)
![](images/data_send.png)
![](images/data_receive.png)

# 四表五链

raw:
manage:
nat:
filter:

PREROUTING:
INPUT:
OUTPUT:
FORWARD:
POSTROUTING:

处理流程图：
![](images/iptables_process.png)