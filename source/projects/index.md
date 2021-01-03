---
title: Recent Project
comments: false
---

## I4: Incremental Inference of Inductive Invariants for Verification of Distributed Protocols

Designing and implementing distributed systems correctly is a very challenging task. Formal verification has been successfully used to prove the correctness of distributed systems. At the heart of formal verification lies a computer-checked proof with an inductive invariant. Finding this inductive invariant, however, is the most difficult part of the proof. Alas, current proof techniques require inductive invariants to be found manually---and painstakingly---by the developer. In this project we propose a new approach, Incremental Inference of Inductive Invariants (I4), to automatically generate inductive invariants for distributed protocols. The essence of our idea is simple: the inductive invariant of a finite instance of the protocol can be used to infer a general inductive invariant for the infinite distributed protocol. In I4, we create a finite instance of the protocol; use a model checking tool to automatically derive the inductive invariant for this finite instance; and generalize this invariant to an inductive invariant for the infinite protocol. Our experiments show that I4 can prove the correctness of several distributed protocols like Chord, 2PC, and Transaction Chains with little to no human effort.

### Publications
<font size="3">Haojun Ma, Aman Goel, Jean-Baptiste Jeannin, Manos Kapritsos, Baris Kasikci, Karem A. Sakallah, *I4: Incremental Inference of Inductive Invariants for Verification of Distributed Protocols*, 27th ACM Symposium on Operating Systems Principles (SOSP '19) [[pdf](/files/i4-sosp19.pdf)] [[Video](https://sosp19.rcs.uwaterloo.ca/videos/D2-S3-P3.mp4)] [[Slides](https://sosp19.rcs.uwaterloo.ca/slides/ma.pdf)]</font>

<font size="3">Haojun Ma, Aman Goel, Jean-Baptiste Jeannin, Manos Kapritsos, Baris Kasikci, Karem A. Sakallah, *Towards Automatic Inference of Inductive Invariants*, 17th Workshop on Hot Topics in Operating Systems (HotOS '19) [[pdf](/files/i4-hotos19.pdf)]</font>