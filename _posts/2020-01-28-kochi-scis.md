---
title: 'SCIS in 高知!'
date: 2020-01-28
permalink: /posts/2020/01/kochi-scis/
tags:
 - conferences/workshops
---

My first time in Kochi (高知)!

I'm here to attend SCIS 2020 (https://www.iwsec.org/scis/2020/index.html), and Kurazumi, a student in our research group at Tokyo Tech, is here to present his work on multi-hop payment channels. 


His work develops on the work of Maravolta et al. (NDSS'19) which observes the weakness on HTLC based payment channels. The basic idea of the so called Warmhole attack is that during a payment channel composed by several hops, at least two nodes in the channel can collude and collect payment fees from all the nodes in between the two malicious nodes. Since the two nodes collude, they can share the pre-image value used in the HTLC. Maravolta et al. approach is to pick an independent value for any pairwise channel. 

Our approach is to improve in the computational complexity of the their protocol by substituting the used ECDSA protocol, by a newer and more efficient one, namely the one by  Doermer et al. (S&P'18). This substitution required a few adaptations from the original scheme from the multihop scheme in Maravolta et al., and this is our contribution. 

More than that, please wait for the full version yet to be submitted to an international conference. 

Instead you can enjoy the pictures of the event and the Kochi Castle nearby the venue.

<img src="/images/posts/2020-01-28/kochi-SCIS.jpg" width="500">

<img src="/images/posts/2020-01-28/kochi-SCIS-2.jpg" width="500">

<img src="/images/posts/2020-01-28/kochi-SCIS-3.jpg" width="500">

<img src="/images/posts/2020-01-28/kochi-SCIS-4.jpg" width="500">