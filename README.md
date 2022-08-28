# Desirable Characteristics of Datasets for Assessing Responsible Robots

This repository accompanies the paper "Desirable Characteristics of Datasets for Assessing Responsible Robots" presented at the workshop [Responsible Robotics: Robots with and for Society](https://www.robotics4eu.eu/events/resp-r/) conducted within the [31st IEEE International Conference on Robot & Human Interactive Communication (RO-MAN)](http://www.smile.unina.it/ro-man2022/).

## Abstract
Learning-enabled components in robots must be assessed with respect to non-functional requirements (NFR) such as reliability, fault tolerance and adapability in order to ease the acceptance of robots into dynamic human-centered environments. While many factors impact NRFs, in this paper we focus on datasets which are used to train learning models used in robots. In particular, we describe desirable characteristics for robotics datasets, and identify the associated NRFs they affect. The characteristics are described in relation to the variability of the instances in the dataset, out-of-distribution data, the spatio-temporal embodiment of robots and interaction failures. We emphasize the need to include out-of-distribution and failure data in the datasets, both to improve the performance of learning models, and to allow the assessment of robots in unexpected situations. We also stress the importance of continually updating the datasets throughout the lifetime of the robot, and the associated documentation of the datasets for improved transparency and traceability.

## Desirable dataset characteristics and non-functional requirements
The table below is a summary of the desired characteristics for robotics datasets we identified and the associated non-functional requirements they impact. You are invited to submit pull requests to add to the list.

| **Dataset characteristic** | **Non-functional requirements** |
|----------------------------|---------------------------------|
| The dataset is accompanied by a datasheet which is updated along with dataset | Transparency, Traceability |
| The dataset contains instances collected over an extended period of time  | Adaptability, Completeness, Correctness, Portability |
| The dataset contains instances collected at several locations  | Adaptability, Completeness, Correctness, Portability |
| The dataset contains instances recorded with different sensors  | Adaptability, Completeness, Correctness, Portability |
| The dataset contains variation in other task-relevant independent variables  | Adaptability, Completeness, Correctness, Portability |
| The variability of independent variable is quantified in the datasheet  | Transparency, Traceability |
| The dataset includes miscellaneous instances not relevant for the target task  | Adaptability, Fault Tolerance, Reliability, Safety, Trust, Flexibility |
| The dataset includes noisy, erroneous instances |  Adaptability, Fault Tolerance, Reliability, Safety, Trust, Flexibility |
| The dataset includes task-relevant instances, but outside of the target domain  | Adaptability, Domain Adaptation, Reliability, Safety, Trust, Flexibility |
| The dataset consists of continuous streams of data |  Flexibility, Completeness |
| The dataset contains instances recorded from multiple viewpoints and orientations  | Flexibility, Completeness |
| The dataset includes a description of the robot and its sensors  | Completeness |
| The dataset includes proprioceptive data  | Completeness |
| The dataset includes naturally occurring failed interactions or unexpected situations  | Fault Tolerance, Safety, Trust, Flexibility, Testability |
| The dataset includes instances of failed interactions induced by fault injection  | Fault Tolerance, Safety, Trust, Flexibility, Testability |
| The dataset is continuously updated through the lifetime of the robot | Completeness, Domain Adaptation, Adaptability, Correctness, Maintainability, Trust, Flexibility |


## Contributing
In order to add to the list of desirable dataset characteristics for robotics datasets, submit a pull request with the following information:
* the desired characteristic
* the list of non-functional requirements that are impacted by this characteristic
* a short justification for why this is a desired characteristic, and why those particular NFRs are affected. You could also include citations to papers or datasets which support the justification.

## Citation
```
@inproceedings{thoduka2022respr,
Title = {{Desirable Characteristics of Datasets for Assessing Responsible Robots}},
Author = {Thoduka, Santosh and Nair, Deebul and Hochgeschwender, Nico and Pl{\"o}ger, Paul G.},
Booktitle = {RO-MAN Workshop on Responsible Robotics: Robots with and for Society (RESP-R)},
Address = {Naples, Italy},
Timestamp = {2022.08.20},
Year = {2022}
}
```
