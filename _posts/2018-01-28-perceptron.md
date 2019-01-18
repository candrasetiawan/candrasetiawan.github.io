---
title: "BGP with Vyatta and Mikrotik"
date: 2018-01-28
tags: [BGP, Vyatta, Mikrotik, VMWare]
header:
  image: "/images/bgp/bgpvyatta.jpg"
excerpt: "BGP, Vyatta, Mikrotik, VMWare"
mathjax: "true"
---

## Permodelan routing BGP sederhana menggunakan Vyatta dan Mikrotik dengan Private
AS pada Jaringan Intranet

BGP atau Border Gateway Protocol routing Protocol yang menghubungkan antar AS (autonomous System) yang sama IBGP (Interior Border Gateway Protocol) atau antar AS yang berbeda EBGP (Exterior Border Gateway Protocol). BGP telah terbukti scalable, stabil dan menyediakan mekanisme yang diperlukan untuk mendukung routing yang kompleks. Pada permodelan kali ini kita akan menggunakan BGP dengan redistribute OSPF dan untuk Autonomous System Number yang dipergunakan maka kita akan menggunakan Private AS 64512 sampai 65534 yang dapat digunakan untuk tujuan pribadi seperti halnya Private IP address.

