---
title: "Server"
description: ""
lead: ""
date: 2023-01-27T08:02:39-05:00
lastmod: 2023-01-27T08:02:39-05:00
draft: true
images: []
menu:
  docs:
    parent: "configuration"
    identifier: "server-80dae5de0613ffb085c54841ceaa1bc5"
weight: 109
toc: true
---
I repurposed an old Mac Mini (*circa 2014*). 

* Dual-core Intel i5 (Haswell ULT), at 2.7 GHz
* 4 GB RAM
* 1 TB SSD (Samsung SSD 860 QVO)

It runs [Proxmox VE](https://www.proxmox.com/en/proxmox-ve), an open-source Virtualization Platform, on a skeletal Debian.  The Home Assistant runs in a container, with no restrictions on CPU, Memory, or disk space utilization. Along with this I run [WeeWx weather server](http://www.weewx.com/)  on  another. 
