## Welcome

My name is Kiley Hewitt. I am a Junior at Allegheny College double majoring in Computer Science and Biology. I am passionate about the interdisciplinary applications of different fields, scientific outreach, and being involved within my communities. As such, I am involved in various organizations such as Women in Science and the Association for Computing Machinery and actively seek out continuous opportunities to build myself as an individual and scientist.  

Coursework over my past two years at Allegheny College has introduced me to the many applications of Computer Science and Biology in this world, and also showed me the potential in the applications of computational methods to the natural sciences. Applying computational methods to immunology research at the University of Pittburgh and developing Bioinformatics applications as a software engineer at Allegheny College has given me baseline experience in these interdisciplinary applications that confirmed my interests in these areas. In the future, I am looking to expand my experience in these applications through work and research opportunities. I am particularly interested in opportunities surrounding genetic or immunology research, and am also looking for any opportunities to build my Computer Science skills through software engineering or cybersecurity.

## Projects

### [Chronic Disease Risk Calculator](https://github.com/Allegheny-Computer-Science-202-S2020/cs202s2020-final-project-hewittk)

For my algorithm analysis final, I built a series of algorithms that would calculate one's risk for different chronic diseases based on their health, genetic, and lifestyle factors. I worked to make the algorithms in this project efficient by streamlining the comparison of the answers to the user's health and lifestyle questionnare to the risk factors for each chronic disease by designing standing risk factor arrays for each disease that can be efficiently compared against a different array that stored the user's answers during the questionnare. 

![Chronic Disease Risk Array Flowchart](<./Chronic Disease Risk Flowchart Resized.png>)

### [Methods of Developing Causal Gene Regulatory Networks of Dynamic Single Cell Data](<./Kiley Hewitt TECBio Poster.pdf>)

My Summer 2020 research project was on developing and testing different methods of developing causal gene regulatory networks from dynamic single cell data. I used different methods to modify the genetic data's linear regression protocols to fit dynamic datasets and better account for nonlinear signaling connections between genes, and designed programs to quantify different aspects of the resembelance between the directed network graphs learned by the causal inference algorithms and the true graphs.

### [Metabolic Proteins in Climate Regulation](https://github.com/allegheny-bioinformatics-300-f2019/project-warbler/blob/master/writing/finalReport/finalReport.md)

For my Bioinformatics class final, my lab group and I investigated the genetic basis for invasive species of birds' adaptability to new climates. We conducted a BLAST analysis to find genetic similarities between birds

## Research

### TECBio REU: Challenging Assumptions of Causal Inference

Over the summer of 2020, I conducted Computational Biology research through the TECBio REU at the University of Pittsburgh. My project was to challenge existing methods of learning causal graphical models to better suit gene regulatory networks to be learned from the dynamic single cell data that gene expression tracking methods often provide. I did this by using various methods such as RNA velocity analysis, Graphical Lasso regression, and monitoring of accuracy through different correlation metrics to make undirected graphs with suitable connectivity to be learned by the lab’s causal inference algorithms.

The first causal inference assumption that I challenged was the assumption of stationarity stating that variables in a graph are in equilibrium and do not change over time which makes it traditionally unsuitable for learning gene regulatory networks of datasets with dynamic gene expression. I challenged this assumption by creating undirected graphs in which the latent time is seen as a dynamic variable and the expression of some genes in a pathway are mapped as a descendent of time. The second causal inference assumption that I challenged was the assumption of linearity stating that variables in a graph have only linear, monotonic relationships which is often untrue of the signaling effects between genes. I challenged this assumption by using Nonparanormal Data Transform to make any consistent increase or decrease shown in gene expression comprehensible by the linear regression tools that build the undirected graph.

![Flowchart](<./GRN Flowchart Resized.png>)

### Senior Project: Estrogen Depletion, Glucocorticoid Treatment, and the Cornea

For my Senior project, I am planning to conduct a project focused on the effect of glucocorticoids on cornea gene expression after estrogen depletion. The eyes have recently started to be viewed as an organ with sexual dimorphism and menopausal estrogen depletion leads to issues in the cornea such as tear film damage and decreased corneal thickness. Glucocorticoid steroid hormone treatment has a role in preventing and mitigating these same conditions. My research aims to derive corneal pathways affected by both glucocorticoids and estrogens using methods such as ordinary differential equation (ODE) analysis of RNA datasets and to test the possible role of local glucocorticoid repletion in reversing the corneal damage effects of estrogen depletion.


## Contact
[Linkedln](https://www.linkedin.com/in/kiley-hewitt-3babaa197/)

[Github](https://github.com/hewittk)

Email: hewittk@allegheny.edu

<script async src="https://www.googletagmanager.com/gtag/js?id=UA-21RZLWGDF-1"></script> <script> window.dataLayer = window.dataLayer || []; function gtag(){dataLayer.push(arguments);} gtag('js', new Date()); gtag('config', '{{ site.google_analytics }}'); </script>
