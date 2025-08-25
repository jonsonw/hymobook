---
title: Welcome to hymobook, It's a book for hybrid modularity
---
**<font color="#FF0000">Hy</font>brid <font color="#FF0000">Mo</font>dularity : Balance in Standardization and Customization**

Traditional modularization​​, implemented through ​​Offsite Fabrication + Onsite Integration​​, which prioritizes physical-layer. In practice, constrained by the ​​process specificity​​ of process industries, ​​diversity of specialized equipment​​, ​​complexity of construction site conditions​​, and ​​transportation limitations​​, traditional modular approaches often stall at the feasibility stage. Or ttempts to "forcibly implement" incur high risks and uncertainties due to compromised engineering integrity.

​​Hybrid Modularity​​ aims to optimize this paradigm by ​​enhancing efficiency and cost-effectiveness through standardized modules​​, while ​​preserving adaptability via customized modules/skids/process units​​. By implementing ​​unified interface spanning both physical and cyber-physical layers, it ​​organically integrates standardized and bespoke components​​, thereby resolving the ​​high-risk rigidity of full-customization​​ and the ​​inflexibility of standardization​​. Its essence lies in: ​​"***Decoupling complexity through modularization, accommodating diverse demands via hybrid integration***"​​.

This book, is planning to share the lessons learnt on the modular implementation, which aim to implement the Hybrid Modularity to the project for process industry. 

Thinking Hybrid Modularity, the core feature, or so-called value/priciple/concept as following, with all the features, it can be recognized as the **HyMo**<sup>TM</sup>.  

- [[Functional Encapsulation]]  
- [[Interface Standardization]]  
- [[​​Plug-and-Play (PnP) Integration​​]]  
- [[​​High Extensibility​​]] 

And in this book, we'd like to suggest and/or introduce the highlight for each phase at following normal flowchart for the Hybrid Modularity implementation in process industries project, which could be helpful for the exactly project execution:

```mermaid
%%{ init: { 'theme': 'default', 'themeVariables': { 'fontSize': '11px', 'primaryTextColor': '#333', 'primaryColor': '#f0f0f0' }, 'sequence': { 'useMaxWidth': true, 'diagramMarginX': 10, 'diagramMarginY': 10, 'boxMargin': 1 } } }%%
sequenceDiagram
	actor A as Owner
	participant B as HyMo
	participant C as Site
	
	A-->>+B:Project Request
	B-->>-A:Modularity Scheme
	A-->>+B:Scheme Accept
	B-->>+C:Engineering Input & Condition
	C-->>C:Building & Foundation
	A-->>B:FAT
	B->>-C:Module Shipping & Transportation
	A-->>C:SAT
	B->>C:Commissioning
	C-->>-B:Start-up
	B->>+A:Handover
```

The Book, it's definitly open source under the MIT license. you can fork the entire book to your work and/or company without any limitation. while, you can also be an hornourable contributor to this book by following GitHub link at the footer.


