---
layout: research-line
title: "Software Refactoring"
description: "The investigation of automated techniques for software refactoring recommendation, the understanding of the role of software refactoring in large and complex software systems, and the investigation and the proposal of context-based software (anti-)patterns."
responsible: "Maurício Aniche"
---

**Modern software systems never stop to grow; and they grow fast.** To catch up with the speed of the highly dynamic and complex society we now live in, companies deliver new features to their software systems virtually at every second of the day. After all, the faster a new feature gets to the market, the better. 

Technically speaking, this means that software developers are adding (and modifying) a high number of lines of source code every day. In a perfect world, these modifications are done in an effective manner, as the internal structure of the software system is designed with evolution in mind.
However, it is easy to imagine that developers that are working under time pressure or on unclear requirements may not take optimal decisions. 

A series of "bad decisions" might make software simply harder to maintain and evolve. As a consequence, our society has to spend more money to keep evolving the software systems we so much rely on. The [Consortium for Information and Software Quality](https://www.it-cisq.org/the-cost-of-poor-quality-software-in-the-us-a-2018-report/The-Cost-of-Poor-Quality-Software-in-the-US-2018-Report.pdf) estimates that, in 2018, the US has spend around US$ 2.84 trillions due to poor software quality, where around 18% (or US$510 billions) due to technical debt and 21% due to challenges in legacy systems. 

Software tends to rot over time. [Lehman](https://ieeexplore.ieee.org/abstract/document/1456074) has indeed predicted that, without action, software systems tend to increase in complexity and suffer from a quality decline [1]. **Software refactoring techniques, or the act of improving the internal structure of the system in a way that future evolutions are easier and therefore less costly, are fundamental.** Software refactoring does pay off; [a study at Microsoft](https://ieeexplore.ieee.org/abstract/document/6802406), for example, showed that developers perceived better maintainability, readability, and even reduced time to markets in codebases that have gone through systematic refactoring. The same developers, however, also observed that refactoring might involve substantial costs and risks.

The goals of this line of research are:

* **To investigate automated techniques for software refactoring recommendation.** Deciding what to refactor is currently based on the developers' gut feelings. Little is decided by means of data-driven methods. Typical work in this line makes use of static analysis, data science, mining software repositories, and machine learning techniques. 
	* Some of our published work: ["The Effectiveness of Supervised Machine Learning Algorithms in Predicting Software Refactoring"](https://arxiv.org/abs/2001.03338).

* **To understand the role of software refactoring in large and complex software systems.** Developers are already aware of the well-known catalogue of refactoring proposed by Fowler in the early days. However, modern systems are more and more complex and large. Solid theories that help developers in understanding what the challenges of refactoring are, what factors influence the decision of refactoring a module (or not), what stakeholders are involved, the cost vs benefit of the refactoring, etc, enables researchers in devising approaches to support this complicated decision-making process. Typical work in this line makes use of theory-building and qualitative research methods.
	* Some of our published work: ["The Adoption of JavaScript Linters in Practice: A Case Study on ESLint"](https://pure.tudelft.nl/portal/en/publications/the-adoption-of-javascript-linters-in-practice-a-case-study-on-eslint(375bf549-f2a2-49a7-8d3d-a4489a579f4c).html), ["Developers' Perceptions on Object-Oriented Design and Architectural Roles"](https://ctreude.files.wordpress.com/2016/07/sbes16.pdf)

* **To investigate and propose context-based software (anti-)patterns**. Our community already has an extensive (and pragmatic) body of knowledge when it comes to software design best practices and anti-patterns. Developers are often aware of impact of traditional code smells, such as 'long methods' or 'God classes', in the future maintenance of their systems. However, these code smells and anti-patterns might not fully describe the types of code structure that hinders maintenance in the vast number of different architectures and platforms we have out there. As an example, an anti-pattern that might happen in a web application is far different from an anti-pattern that might emerge in a library. Understanding what types of anti-patterns emerge in specific types of architecture supports developers in having a more hollistic view of the possible challenges they might encounter in the future. Typical work in this like makes use of data science, mining software repositories, and qualitative research methods.
	* Some of our published work: ["Current Challenges in Practical Object-Oriented Software Design"](https://pure.tudelft.nl/portal/en/publications/current-challenges-in-practical-objectoriented-software-design(fb65f714-1771-4446-9114-73ee302d5693).html), ["Code smells for Model-View-Controller architectures"](https://pure.tudelft.nl/portal/en/publications/code-smells-for-modelviewcontroller-architectures(55788fc3-56ed-4756-8667-cbf3f1e885db).html), ["SATT: Tailoring Code Metric Thresholds for Different Software Architectures"](https://pure.tudelft.nl/portal/en/publications/satt-tailoring-code-metric-thresholds-for-different-software-architectures(3992a2cc-7002-44ed-8e58-f45027a81993).html), ["Improving Code Quality on Automated Tests of Web Applications: A Set of Patterns"](https://figshare.com/articles/Improving_Code_Quality_on_Automated_Tests_of_Web_Applications_A_Set_of_Patterns/11037230), ["An Empirical Catalog of Code Smells for the Presentation Layer of Android Apps"](https://pure.tudelft.nl/portal/en/publications/an-empirical-catalog-of-code-smells-for-the-presentation-layer-of-android-apps(e79aac89-295c-413b-9ca1-1140ddd3db14).html)
