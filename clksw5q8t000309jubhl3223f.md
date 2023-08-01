---
title: "The Cyber Kill Chain: Decoding the Anatomy of a Cyber Attack"
seoTitle: "The Cyber Kill Chain: How the hackers plan and execute their attack"
datePublished: Tue Aug 01 2023 22:49:20 GMT+0000 (Coordinated Universal Time)
cuid: clksw5q8t000309jubhl3223f
slug: the-cyber-kill-chain
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1690926294789/98ff83df-55d1-4c5d-9293-b23058c47bfd.jpeg
tags: security, beginner, cybersecurity

---

The U.S. military has a methodical approach called the "Kill Chain" for targeting and engaging an opponent to achieve specific outcomes. The process involves six steps known as F2T2EA: find, fix, track, target, engage, and assess. The first step is to find suitable targets for engagement, followed by locating and fixing their position, monitoring and tracking the target, selecting an appropriate weapon or asset to achieve the desired effects, engaging the opponent, and evaluating the results. The process is called a "chain" because it's an end-to-end, cohesive approach, and a single flaw can disrupt the entire process.

The Cyber Kill Chain framework, developed by Lockheed Martin (2022), explains how attackers move through networks to identify vulnerabilities that they can then exploit. Attackers use the steps in the Cyber Kill Chain when conducting offensive operations in cyberspace against their targets. If you’re responsible for defending a network, this model can help you understand the stages of a cyberattack and the measures you can take to prevent or intercept each step.

The cyber kill chain is a 7-step process to hack into targets. Examples of targets might include devices, networks, or organizations. Just as how computer networking has a conceptual model of layers(OSI model), hacking has phases. The cyber kill chain is defined as reconnaissance, weaponization, delivery, exploitation, installation, command and control (C2), and actions on objectives. It all starts off with:

## Reconnaissance

The process involves researching and identifying targets through crawling websites such as conference proceedings and mailing lists. This helps in finding email addresses, social connections, and information related to specific technologies.

There's never enough scouting and research to prep in advance before an engagement. It include methods of Open Source Intelligence(OSINT), in-person scouting, and pattern-of-life analysis. The more diligence performed at the recon stage, the easier it is to hack later on in the cyber kill chain.

## Weaponization

This might be the most involved stage of the cyber kill chain. To hack, you need both an exploit and a payload. The exploit lets you take control over the thread of execution for a victim process. The payload is the code you want to run on top of the hijacked process.

It is becoming more common to use an automated tool (known as a weaponizer) to combine a remote access trojan with an exploit and create a deliverable payload. This payload is often in the form of client application data files like Adobe Portable Document Format (PDF) or Microsoft Office documents.

## Delivery

Putting more effort into recon is going to make this phase a whole lot easier. The delivery of weapons to a specific environment can be done through various methods. These forms of delivery methods are, in order of scale and difficulty: Client-side, Service-side, and Supply-chain attacks

According to the Lockheed Martin Computer Incident Response Team (LM-CIRT) from 2004-2010, the most common ways that these threat actors deliver weaponized payloads are through email attachments, websites, and USB removable media.

## Exploitation

Once the weapon is delivered to the victim host, the intruders' code is triggered, usually targeting an application or operating system vulnerability. However, it could also exploit users or utilize an operating system feature that automatically executes code. The code execution point is crucial for the hack's success, but it is not a singular event. A lot of engineering time is required to transform a proof-of-concept into a reliable tool, including feats like bypassing memory protections or sandboxing methods.

## Installation

Hacking is much more than remote access. It means maintaining persistence so you can access on-demand. Hand-in-hand with installation in the cyber kill chain is maintaining persistence. To survive a reboot or even re-format is important to make sure the previous steps don't go to waste. Persistence does increase the potential for detection though. Memory-only installation, rootkits, and encrypted virtual file systems are some ways to maintain stealth.

## Command & Control(C2)

Typically, compromised hosts must beacon outbound to an Internet controller server to establish a C2 channel. Malware(APT) especially requires manual interaction rather than conducting activity automatically. Once the C2 channel establishes, intruders have “hands on the keyboard” access inside the target environment.

The C2 aspect of the cyber kill chain determines successful follow-on objectives. If you can’t communicate without detection, it'll be a short-lived hacking operation.

## Actions on the Objective

This is sometimes referred to as the post-exploitation stage. Real hacking always has a purpose to it. There’s little point in all the hard work of Steps 1-6 of the cyber kill chain if there’s no end-state to achieve.

Typically, the objective is data exfiltration which involves collecting, encrypting and extracting information from the victim environment; violations of data integrity or availability are potential objectives as well. Alternatively, the intruders may access the initial victim box to serve as a hop point to compromise additional systems inside the network.

# Conclusion

As a security enthusiast or professional, knowing the cyber kill chain can help in mitigating threats of various forms. This is more emphasized when one is red teaming or blue teaming. Also, know that knowing the action on objective goes a long way to give one a clear purpose for the hack.

Despite some shortcomings, the Cyber Kill Chain plays an important role in helping organizations define their cybersecurity strategy. As part of this model, organizations must adopt services and solutions that allow them to:

* Detect attackers within each stage of the threat lifecycle with threat intelligence techniques
    
* Prevent access from unauthorized users
    
* Stop sensitive data from being shared, saved, altered, exfiltrated or encrypted by unauthorized users
    
* Respond to attacks in real-time
    
* Stop the lateral movement of an attacker within the network
    

# Resources

[Intelligence-Driven Computer Network Defense Informed by Analysis of Adversary Campaigns and Intrusion Kill Chains](https://www.lockheedmartin.com/content/dam/lockheed-martin/rms/documents/cyber/LM-White-Paper-Intel-Driven-Defense.pdf) by Lockheed Martin Corporation

[Real Hacking: Learn The Cyber Kill Chain](https://www.youtube.com/watch?v=oCUrkc_0tmw)