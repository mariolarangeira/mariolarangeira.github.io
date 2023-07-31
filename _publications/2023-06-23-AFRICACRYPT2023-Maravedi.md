---
title: "'Maravedí: A Secure and Practical Protocol to Trade Risk for Instantaneous Finality'  on AFRICACRYPT 2023"
collection: publications
permalink: /publication/2023-07-19-AFRICACRYPT2023-Maravedi
excerpt: 'A new way of implementing finality.'
date: 2023-06-23
venue: '14th International Conference on Cryptology AFRICACRYPT 2023'
paperurl: 'https://africacrypt2023.tn/'
citation: 'Maxim Jourenko and Mario Larangeira. (2023). &quot;Maravedí: A Secure and Practical Protocol to Trade Risk for Instantaneous Finality.&quot; <i>AFRICACRYPT 2023</i>.'
---

Our [Maravedí Protocol](https://eprint.iacr.org/2023/183)  will be presented at AFRICACRYPT'23!

Our protocol introduces a novel idea of trading risk for **instantaneous finality**.  As far as we know, this is the first protocol to propose this idea. The core is a protocol that coordinates a payment channel protocol, like Lightning Network,  and a slow regular ledger transaction.  The main model is similar to the credit card model. That is a customer buys from a merchant and a third player, guarantees that the merchant will receive, in case the ledger transaction is not confirmed. 

Our protocol guarantees that the merchant receives as long as the third player also receives. We have introduced a new use of the Hash Time Lock Contract (HTLC) which allows this *atomicity* property.


















