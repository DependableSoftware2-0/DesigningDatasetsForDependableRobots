# Desirable Characteristics of Datasets for Assessing Responsible Robots


## Santosh Thoduka and Deebul Nair and Nico Hochgeschwender and Paul G. Plöger
Department of Computer Science, Hochschule Bonn-Rhein-Sieg, Grantham-Allee 20, Sankt Augustin
53757, Germany 

## Abstract 
Learning-enabled components in robots must be assessed with respect to non-functional requirements (NFR)
such as reliability, fault tolerance and adapability in order to
ease the acceptance of robots into dynamic human-centered environments. While many factors impact NRFs, in this paper we
focus on datasets which are used to train learning models used in robots. In particular, we describe desirable characteristics for
robotics datasets, and identify the associated NRFs they affect. The characteristics are described in relation to the variability
of the instances in the dataset, out-of-distribution data, the spatio-temporal embodiment of robots and interaction failures.

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
