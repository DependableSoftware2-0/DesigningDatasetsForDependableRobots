# Reviews

## Reviewer 1 

=
*** Paper “Desirable Characteristics of Datasets for Assessing Responsible Robots ***

The paper discusses some features that datasets used for training robot components should exhibit in order to satisfy some non-functional requirements.

The contribution of the paper is rather unconventional and consists in a list of general principles that should drive the creation of datasets for learning robot components.

One aspect that could be further discussed is the relationship between datasets and tasks. Usually datasets are built with a specific task (or set of tasks) in mind but they often appear (and are used) as more task-agnostic than they actually are.

In general, one of the biggest limitations to the use of datasets in robotics is that sequentiality matters for robots. In other words, data acquired by a robot at time t depend on the history up to t, namely on the observations obtained and actions performed up to t. This is hardly captured in datasets that usually record a single fixed history. This seems related to the discussion on spatio-temporal embodiment of Section III-C and could be expanded.

As future work it would be interesting to analyze some existing datasets and evaluate their compliance to the principles listed in the paper.

Typos and minor issues:
- page 1: need to be taken -> needs to be taken
- page 2: what does it mean that a dataset “is complete”?
=====

## Reviewer 2
The paper contributes to fundamental research in the field of smart robotics by providing guidelines on the selection of datasets and the setup of the training process. The authors put their focus on sketching out qualitative aspects of trustworthy/responsible robotics and pin down some methods and technical approaches to prevent errors, biases and faulty deployment of robots. 
By combining non-functional requirements (NFR) for learning-enabled components (LEC) that are oftentimes trained in closed, scope-limited or under-complex environments with common errors in the deployment of robots in real-world scenarios, the paper lays important groundwork in field of data quality, reliability and trustworthy machine-learning. It is written in a comprehensive, condensed and precise manner. The chosen format of „desirable characteristics“ is appealing and abstract enough for the early-stage of the research in this area.
By transferring findings about AI (ML lifecycle) to the specific challenges in the case of (mobile) robots, the authors contribute to the growing field of responsible robotics. The examples given in the paper serve well to bridge the overarching principles with concrete deployment challenges. The focus on variability, spatial-temporal embodiment, interaction failures and life-long learning is both convincing and enlightening for a reader.
From an interdisciplinary perspective I would suggest the following improvements which could especially include the ongoing regulatory efforts of the EU (Artificial Intelligence Act, AIA):
    • The collection of non-functional requirements for LEC in robotics could be better and more comprehensively be made transparent to readers: Which NFR are discussed and how are they defined? The parts of the paper where the desired characteristics are mapped to NFRs („The NFRs associated with these characteristics are…“) are merely presented as a result, yet lack the arguments and reasons for why and how e.g. „fault tolerance, safety, trust, reliability, and correctness“ are concerned. As a reader, I would appreciate an overview of all relevant NFR and their definition.
The paper could especially be based more intensely on literature from the fields of ethics and law. Both disciplines have contributed largely in categorizing and specifying overarching principles of trustworthy AI, such as explainability, transparency, non-bias etc. By focusing on just a few publications and mostly the aspects of safety, reliability and transparency, the paper falls short in giving a solid overview of qualitative requirements for trustworthy AI and smart robotics. As a short paper, it seems however reasonable to keep this aspect short and mostly refer to previous work. Yet, the quoted literature on these aspects seems a bit arbitrary. I would suggest to deepen the literature analysis on NFR further. 
    • In order to synchronize the technical research with ongoing regulatory efforts in the EU, the paper could specifically consider the legal requirements for so-called high-risk AI systems in the Proposal of the European Commission for an AI Act of the EU (Art. 10 ff. AIA). Especially the provision of Art. 10 AIA („data and data governance“) can serve as a reference to categorize the developed „desirable characteristics“ of datasets. Many of the aspects touched in the paper can be referenced and compared to the detailed provisions of the AI Act.
    • Since „harmonised standards“ are supposed to further specify the legal requirements of the AIA (see Art. 40 AIA), also literature and ongoing work in the field of technical standardization (ISO, CEN, DIN etc.) could be of use as references for the analysis in this paper. It would be interesting to see how the desirable characteristics map to ongoing efforts in the field of technical standardization of AI systems and robots – or how the desirable characteristics could be „translated“ to technical standards.
    • Part IV. appears a bit too superficial for me and could be strengthened. It is also not fully clear why the comparison to the „metricsproject“ and its benchmarks is necessary in the analyzed context. This part could be better integrated in the overall train-of-thought over the paper.
