---
title: "Hands on Lab MPLS"
date: 2018-01-28
tags: [MPLS, Mikrotik]
header:
  image: "/images/mpls/mpls.jpg"
excerpt: "BGP, Mikrotik"
mathjax: "true"
---

## Workshop Switching, Routing, dan MPLS

MPLS  adalah  teknologi  penyampaian  paket  pada  jaringan  backbone  berkecepatan  tinggi  yang menggabungkan  beberapa  kelebihan  dari  sistem  komunikasi  circuit‐switched  dan  packet‐switched  yang  melahirkan teknologi yang lebih baik. Yang dimaksud circuit‐switched dan packet‐switched adalah sebagai berikut: 

* Circuit‐switched adalah model jaringan yang menerapkan sebuah jalur komunikasi yang dedicated antara 2 station. 
* Packet‐switched adalah metode komunikasi jaringan digital yang ditransmisikan semua data yang terlepas dari struktur paket.  

MPLS Label dapat membangun pemetaan label‐to‐label antar router. Label ini melekat pada paket IP yang memungkinkan  router  untuk  meneruskan  jalur  lalu lintas  dengan  melihat  label  dan  bukan  alamat  IP tujuan.  Paket  yang  diteruskan  oleh  Label  Switching  bukan  IP  Switching.  Teknik  Label  Switching  bukanlah hal yang baru. Teknologi yang sebelumnya yaitu Frame Relay dan ATM teknologi tersebut dapat digunakan untuk  memindahkan  frame  seluruh  jaringan.  Pada  Frame  Relay,  framenya  bisa  menjadi  sedikit  panjang. Sedangkan Asynchronous Transfer Mode (ATM), mempunyai FixedLength yang terdiri dari 5 header byte dan payload 48 byte. Header pada ATM dan Frame Relay dapat mengacu pada virtual circuit yang berada pada  frame.  Frame  Relay  dan  ATM  mempunyai  kesamaan  yaitu  setiap  hop  diseluruh  jaringan  dan  nilai label  dalam  header  dapat  berubah.  Hal ini  berbeda  dari  paket  forwarding,  ketika  sebuah  router menforward paket IP, nilai yang berkaitan dengan tujuan dari paket tidak merubah alamat IP tujuan. Fakta bahwa MPLS Label digunakan untuk meneruskan paket‐paket. (Ghein, 2007)
