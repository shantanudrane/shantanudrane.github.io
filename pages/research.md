---
layout: page
title: research
description: Shantanu Rane's Research 
---

<div class="navbar">
    <div class="navbar-inner">
        <ul class="nav">
            <li><a href="#cpssecurity">CPS security</a></li>
            <li><a href="#privacy">privacy</a></li>
            <li><a href="#biometrics">biometrics</a></li>
            <li><a href="#embeddings">embeddings</a></li>
        </ul>
    </div>
</div>


### <a name="cpssecurity"></a>CPS security


### <a name="privacy"></a>data privacy 
This research is concerned with inferring knowledge from data in such a way that 
the data, or the algorithm, or the inference have to be protected from adversaries. 
The approaches followed depend upon the kinds of security and privacy guarantees 
desired and the strength of the adversary. We employ computationally secure 
primitives, such as homomorphic encryption, for manipulating data in the 
encrypted domain. We also investigate unconditionally secure approaches such as 
secret sharing, and statistically private mechanisms based on differential 
privacy.

**Some representative publications:**
1. S. Rane and P. Boufounos, Privacy-Preserving Nearest Neighbor Methods, IEEE Signal
 Processing Magazine, Vol. 30, No. 2, pp. 18--28, March 2013. 
([link](https://ieeexplore.ieee.org/document/6461631))  
2. S. Rane, J. Freudiger, A. Brito, E. Uzun, Privacy, Efficiency and Fault Tolerance
 in Aggregate Computations on Massive Star Networks, IEEE Workshop on Information 
Forensics and Security (WIFS 2015), Rome, Italy, November 2015. ([paper]())

### <a name="biometrics"></a>biometrics

This work encompasses the theory, software implementation, and standardization of secure 
fingerprint-based biometric recognition systems. As a biometric is an irreplaceable attribute
 of a person, loss or theft of the biometric leaves her vulnerable to spoofing, identity theft 
and loss of sensitive data. To insulate a user from such vulnerabilities, we construct biometric
 recognition methods that do not require the system to store a person's biometric (or biometric 
features) in the clear. This work is interdisciplinary. It involves the use of image processing 
and machine learning to identify and extract discriminative features from human biometrics. 
To prevent the extracted features from being accessed by adversaries while also allowing the 
comparisons of test biometrics against the enrolled biometric identities, we have employed 
information-theoretic primitives, such as fuzzy vaults, and cryptographic primitives, such 
as homomorphic encryption.

**Some representative publications:**
1. S. Rane, Y. Wang, S. C. Draper and P. Ishwar, Secure Biometrics: Concepts, Authentication 
Architectures, and Challenges, IEEE Signal Processing Magazine, Vol. 30, No. 5, pp. 51--64, 
September 2013. ([link](https://ieeexplore.ieee.org/document/6582729))
2. Y. Wang, S. Rane, S. C. Draper and P. Ishwar, A Theoretical Analysis of Authentication, 
Privacy and Reusability Across Secure Biometric Systems, IEEE Trans. Information Forensics 
and Security, Vol. 7, No. 6, pp. 1825--1840, December 2012. ([link](https://arxiv.org/abs/1112.5630))

### <a name="embeddings"></a>signal embeddings

This research was concerned with efficient machine learning operations on high-dimensional signals, such as 
images and videos. The philosophy is to map high-dimensional signals into a low-dimensional vector space 
such that some aspects of the signal geometry are preserved without necessarily targetting faithful recovery
of the signals themselves. Most of the work that we have done so far has centered around distance-preserving 
embeddings based on the Johnson-Lindenstrauss Lemma. Particularly, to communicate the signal embeddings from 
a client to a database server, it is necessary to first quantize them. We have extended the Johnson-Lindenstrauss 
Lemma to quantized embeddings. Furthermore, by carefully designing the quantizer, some embeddings can be endowed
with an interesting information-theoretic privacy property. This makes them useful in the design of privacy-aware
nearest neighbor protocols.

**Some representative publications:**
1. M. Li, S. Rane and P. Boufounos, Quantized Embeddings of Scale-Invariant Image Features for Mobile Augmented 
Reality, IEEE International Workshop on Multimedia Signal Processing (MMSP 2012), Banff, Canada, September 2012.
 ([paper](http://www.merl.com/publications/TR2012-073)) 
2. P. Boufounos and S. Rane, Secure Binary Embeddings for Privacy-Preserving Nearest Neighbors, IEEE International 
Workshop on Information Forensics and Security (WIFS 2011), Iguazu Falls, Brazil, November 2011. 
([paper](http://www.merl.com/publications/TR2011-077))
