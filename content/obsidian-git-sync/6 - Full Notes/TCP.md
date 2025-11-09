---
aliases:
  - Transmission Control Protocol
---

tags: [[networking]], [[transporting protocols]]

TCP breaks up each message to a small elements (*segments*). They are numbered in sequence and passed to the IP process for assembly into packages.

TCP keeps track of the transmitted data segments,
acknowledges received data and retransmits unacknowledged data.

**Remark:**  TCP is slower than some other [[transporting protocols|protocols]] as a payoff for reliability 
![[Pasted image 20240809233118.png]]
