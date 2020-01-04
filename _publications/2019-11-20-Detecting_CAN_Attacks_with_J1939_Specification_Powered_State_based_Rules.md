---
title: "Detecting CAN Attacks with J1939 Specification Powered State-based Rules"   
collection: publications
permalink: /publication/2019-11-20-J1939-IDS
date: 2019-11-20
paperurl: 'http://matthewrekos.github.io/files/Detecting_CAN_Attacks_with_J1939_Specification_Powered_State_based_Rules.pdf'
---
This paper is currently under review.

Abstract:    
 Millions of modern day industrial vehicles use J1939, a software standard operating on top of {CAN}. Having a software standard allows for interpreting the data field without extensive reverse engineering, making hacking the CAN Bus easier. In this paper we propose an adversarial model for CAN and J1939, a rules based intrusion detection system for any J1939 system, an evaluation study and a set of recommendations for defending systems that make use of CAN. The adversarial model shows what attacks an adverary is capable of with the J1939 specification, and how a defender can measure the impact of these attacks through capability degradation, covertness, access, and fleet scalability. When designing security around our adversarial model into the CAN Bus we sought to minimize additions to the system, and modifications to existing Electronic Control Units (ECUs). We propose an intrusion detection system which utilizes state-based static rules for comparison of arbitrary data from any J1939 message, and only requires one new device silently connected to the CAN Bus, ensuring it has no effect on CAN Bus bandwidth. We wrote over 30,000 rules to maintain the specification's restrictions on data values, watch for inconsistency, and detect rogue device transmissions. Our experiment consisted of injecting malicious messages, firmware upgrades, jamming attacks, and intentional data mistakes into a C7 Caterpillar Diesel Engine Control Module using a physical implant and testing against rental truck data. After adjustments to transmission intervals not exactly matching the specification, we have zero false positives on a 90 minute data capture from a rental truck, and detected transmitting rogue devices, such as physical implants, maintenance devices, and telematic pivots, for fixed-rate messages on our testbench. In this paper we demonstrate the effectiveness of data based analysis, and modify the threat model for J1939 systems from rogue devices to existing devices.

Download [here](https://matthewrekos.github.io/files/Detecting_CAN_Attacks_with_J1939_Specification_Powered_State_based_Rules.pdf) 
