---
title: " (Weighted) Threshold Signatures: 2020-03-10/17"
collection: teaching
type: "Seminar"
permalink: /teaching/2020-03-10
venue: "Tokyo Tech, Oookayama Campus"
date: 2020-03-10
location: "Tokyo, Japan"
---

We had a series of two seminars about threshold signatures conducted by myself.

Threshold cryptosystems system are heavily based on secret sharing schemes. The main idea is that a secret can be broken in n "pieces", in a way that each piece does not reveal any information of the secret, in fact any number of pieces that are less than t, does not reveal anything about the secret. The threshold is t. 

Going back to signature schemes, the secret key, needed to generate the signature, is broken into n pieces, in such a say that any group of participants of size t can jointly generate the signature. An implicit assumption is that each participant of the protocol receives only **one** share, or piece of the secret, this is equivalent to say the **weight** one. There are threshold schemes that have arbitrary **access structure**. For example, *any group of size t* is, arguably the most common access structure. Others exist, another example is the hierarchical, where the structure mimics the existing one in corporations and companies, e.g., one director, two managers are necessary to generate a signature.

It seems that a weighted version of threshold scheme, i.e., where the participants do not necessarily have only one share,  is  different from the hierarchical one. Furthermore, it seems there is not many weighted schemes in the literature. An example, is the scheme from [Dikshit and Singh](https://www.semanticscholar.org/paper/Weighted-threshold-ECDSA-for-securing-bitcoin-Dikshit-Singh/534b5c4bb1fa283cf223077b627c855fb7b7f3ec). 

In our series of two seminars, we started by reviewing [Dikshit and Singh](https://www.semanticscholar.org/paper/Weighted-threshold-ECDSA-for-securing-bitcoin-Dikshit-Singh/534b5c4bb1fa283cf223077b627c855fb7b7f3ec) on the first day 2020-03-10.

On the second day, 2020-03-17, we reviewed the regular, and more modern, threshold signature scheme by [Gennaro and Goldfeder](https://eprint.iacr.org/2019/114.pdf), and discussed on the trade-offs of introducing weights on this scheme. In particular the computational and communication overheads during the signature generation phase. 


<img src="/images/teaching/2020-03-10/weighted.jpg" width="500">
<em>Notes on the first day, describing a weighted signature scheme</em>

