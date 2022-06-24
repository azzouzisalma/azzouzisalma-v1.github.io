---
title: DSM Project
description: This is the description of our DSM Project
date: "2019-05-02T19:47:09+02:00"
jobDate: 2021-09 (5 months)
work: [Network programming, system programming]
techs: [C, Network programming]
designs: []
thumbnail: dsm/dsm_arch.png
projectUrl: https://github.com/azzouzisalma/DSM
---

This project aims to develop a shared and distributed memory system on networked machines. It is divided into two phases, the first of which aims to develop a **program launcher**, which has the task of launching different processes on remote machines via **SSH**, while retrieving and centralizing the standard and error outputs of these machines. This first program also sets up everything necessary for the **DSM** in the next step, such as setting up listening sockets leading to an interconnection of all processes between them.

 The second phase of this project aims to implement the DSM protocol thanks to everything that was put in place in the first phase. In this phase the exchange of pages and the management of memory accesses by the different processes in the network have been implemented. Here is the architecture explained in the figure above.

For more detail, please check the **Github link above**.