---
layout: post
date: 2019-07-19 10:20
categories: [Burning Platform]
tags: [Burning Platform, Decentralization, PKI]
author: Dominic Letz
image: Kazhakstan0.png
---

__OMG! So it happens again. PKI the Public Key Infrastructure is a centrally rooted security infrastructure to encrypt nearly all of todays internet traffic. And is being used to crack all traffic in Kazakhstan.__ 

Yesterday on the 18h July 2019, the state-owned telecommunications organization of Kazakhstan started to misuse this central infrastructure in the states initiative against free speech. The now dictatorship of Kazakhstan is forcing its users to install a custom Kazakhstan root certificate. With this certificate in place the government is able to read, intercept & change all traffic send from those internet users to public websites. This is a general _Man-In-The-Middle attack on all citizens_ including destinations such as facebook.com or gmail.com giving and the government wide access to their citizens most personal data. 

![alt_text](/images/blog/Kazhakstan1.png "image_tooltip"){: .center-block }

The government certificate can be obtained from [http://qca.kz](http://qca.kz/) and citizens are required to install it from their ISPs. The certificate is already valid since February 1st but to our knowledge only enforced since yesterday. The Firefox maker Mozilla already has a [new bug report to categorically deny this new state-issued certificate](https://bugzilla.mozilla.org/show_bug.cgi?id=1567114). This might either increase the pressure on the regime to cut back with their efforts to decrypt all traffic or lead to a ban of Firefox in the country.

At the core of the problem is though the central organization of the PKI infrastructure. Even the current "proper" [root authorities have their places just for historical reasons](https://diode.io/burning-platform-pki/why-there-are-3652-organizations-that-can-read-everyones-encrypted-traffic-19098/). This central infrastructure is becoming a single point of failure (SPOF) for security. We just saw [DarkMatter the UAE spy organization](https://diode.io/burning-platform-pki/darkmatter-and-industrial-iot-security-19027/) having valid intermediate certificates and even trying to become a root authority. This centralized infrastructure is becoming a major weakness of the internets global security. But this can be changed. At Diode we believe that the future of PKI is [decentralized PKI](https://hackernoon.com/decentralized-public-key-infrastructure-dpki-what-is-it-and-why-does-it-matter-babee9d88579). When you check your email and gmail.com or send messages to your friends via facebook.com encryption should be end2end and not signed-off by a ominous third party.