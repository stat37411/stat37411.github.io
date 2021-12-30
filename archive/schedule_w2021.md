# Schedule - Winter 2021

This course follows a Tuesday/Thursday Schedule.  There is a section for each day, with materials for that day.  This schedule is subject to change before a class is held.

Links to readings can be found on the [resources page](resources.md).

## Day 00 - 1/12

Introduction to topological data analysis.  [Recorded Lecture](https://uchicago.zoom.us/rec/share/w4WMi_dlxqB7C5nfz1pYgEEyBZh0pcrzXUUENLXVfHqD-HB44ecci0sA-YToOmiD.vTGMYldNFJT6VOcl)

__Reading:__
* Introduction of Oudot,
* peruse Chapter 2 of Ghrist,
* peruse "Topological pattern recognition for point cloud data" by Carlsson.

## Day 01 - 1/14

Preliminaries: Graphs, Clustering, Disjoint Set/Union-find, the Graph Laplacian.  [Recorded Lecture](https://uchicago.zoom.us/rec/share/k_nuilYG5XrCMhX-MZjfvJGbg6fRVjIhlwRetZLMDTUzB0XvRjcm4YWD50Mcwbny.PvsSiwIc-iQoLrOU?startTime=1610656367000)

__Code:__
* [`union_find.hpp`](https://github.com/stat37411/tda/blob/main/include/union_find.hpp)

__Reading:__
* (Optional) "A tutorial on spectral clustering" by von Luxburg.
* (Optional) You can also find some notes on spectral clustering in Python [here](https://caam37830.github.io/book/05_graphs/spectral.html).

## Day 02 - 1/19

Basic Topology (spaces, maps, homotopy).  Simplicial Complexes.  Simplicial Maps.  Constructions. [Recorded Lecture](https://uchicago.zoom.us/rec/share/VvVcgh7o9TDx7i2h6FCFi56dWnZy0Exq6OACFvEV2N_3NcVDNfLlZZrvGA3CTHGQ.dPCal4NBqzvTsp3o)

__Reading:__
* Ghrist: Preface and Chapter 2.
* (Optional): Munkres Sections 1.1 and 1.2.
* (Optional): Hatcher Chapter 0.


## Day 03 - 1/21

Nerve of a cover, witness complexes, Mapper algorithm. Tries.  [Recorded Lecture](https://uchicago.zoom.us/rec/share/czlhI9x7l0f9AlQhlEgaINyKBY6YD_qHGehce-plbK3UaMSqplaCLc6l0quvuyRy.-ZvI3JcBzgPo4gSI)

__Code:__ [`trie.py`](https://github.com/stat37411/tda/blob/main/tda/trie.py)  [`simplicial_complex.py`](https://github.com/stat37411/tda/blob/main/tda/simplicial_complex.py)  [demo notebook](https://github.com/stat37411/tda/blob/main/ipynb/simplex.ipynb)

For an open-source Mapper implementation (in Python), check out [Kepler Mapper](https://kepler-mapper.scikit-tda.org/en/latest/).

__Reading:__
* "Topological Estimation Using Witness Complexes" by V. de Silva and G. Carlsson.
* "Topological Methods for the Analysis of High Dimensional Data Sets and 3D Object Recognition" by G. Singh, F. Memoli, and G. Carlsson.
* (Optional) "The Simplex Tree: An Efficient Data Structure for General Simplicial Complexes" by J.D. Boissonnat and C. Maria.
* (Optional) "Extracting insights from the shape of complex data using topology" by P. Y. Lum et al.
* (Optional) "Identification of type 2 diabetes subgroups through topological analysis of patient similarity" by L. Li et al.

## Day 04 - 1/26

(Cellular) chain complexes, (Cellular) homology, reduction algorithm.  [Recorded Lecture](https://uchicago.zoom.us/rec/share/uZOra3c8RTQWEvkAq1F_LwM0DPj7lkpo1aNqVvKEfhTRujlPQlLZaodAFfuAi2k7.ZtFvpOW4cuttUFpb?startTime=1611693061000)

__Code:__

__Reading:__
* Ghrist Chapter 4
* "Computing Persistent Homology" by A. Zomorodian and G. Carlsson.
* (Optional) "Persistent and Zigzag Homology: A Matrix Factorization Viewpoint" by G. Carlsson, A. Dwarkanath, and B.J. Nelson, sections 2.2-2.5
* (Optional) Hatcher Chapter 2 (2.2 is most relevant)
* (Optional) "Topological Persistence and Simplification" by H. Edelsbrunner, D. Letscher and A. Zomorodian.


## Day 05 - 1/28

Filtrations, persistent homology. [Recorded Lecture](https://uchicago.zoom.us/rec/share/P9LrbpHyZd2QbIDQBQCR7TIncsmbbC_aIakHtN00mx7ucEddpzQRLQ5fwEPz3mpI.6S0jrVUHU6qgrXNQ?startTime=1611866220000)

__Code:__

__Reading:__
* Oudot Chapter 2
* "Computing Persistent Homology" by A. Zomorodian and G. Carlsson.
* (Optional) "Persistent and Zigzag Homology: A Matrix Factorization Viewpoint" by G. Carlsson, A. Dwarkanath, and B.J. Nelson, sections 2.6, 2.7
* (Optional) For some nice visualizations, see Anjan Dwaraknath's Slides: [Link](https://anjandn.github.io/quivertalkslides/)


## Homework 1

Due noon on Feb. 5, 2021.
[Link to assignment](homework/Homework_1.pdf)  [Demo mapper graph](extras/chemdiab_keplermapper_output.html)

## Day 06 - 2/2

Pairs, barcodes, diagrams, bottleneck distance, features.  [Recorded Lecture](https://uchicago.zoom.us/rec/share/TTpfIhLRMsulKsVqKU-2oWUrL565aZFPu0TZVoH8hJv33tArsVi5lfqqpcLfCWBI.1WLf0xDjPHBuYFda?startTime=1612298099000),  [PDF of iPad notes](lectures/Lecture7.pdf) - note that I also showed some figures from the papers below.

__Code__:

__Reading__:
* Oudot Chapter 3, Section 1.1
* (Optional) "Stability of Persistence Diagrams" by  S. Cohen-Steiner, H. Edelsbrunner, and J. Harer.
* (Optional) "Gromov-Hausdorff Stable Signatures for Shapesusing Persistence" by F. Chazal, D. Cohen-Steiner, L.J. Guibas, F. Mémoli, and S.Y. Oudot.
* (Optional) "The Ring of Algebraic Functions on Persistence Bar Codes" by A. Adcock, E. Carlsson, and G. Carlsson.
* (Optional) "Statistical Topological Data Analysis using Persistence Landscapes" by P. Bubenik.

## Day 07 - 2/4

Quiver Representations, Zigzag Homology. [Recorded Lecture](https://uchicago.zoom.us/rec/share/bfa0j6qgkmIMOnyN6qouzc3Gf3lVqPv6FhIEovekrObFLTmK3jPm6mFtP-1X34Tt.VnSA0eB5oG4rfI40),  [PDF of iPad notes](lectures/Lecture8.pdf).

__Code__:

__Reading__:
* Oudot Chapter 1
* Ghrist Chapters 5.13, 5.15
* (Optional) "Zigzag Persistence" by G. Carlsson and V. de Silva.
* (Optional) "Zigzag Persistent Homology and Real-valued Functions" by G. Carlsson, V. de Silva, and D. Morozov.
* (Optional) "Persistent and Zigzag Homology: A Matrix Factorization Viewpoint" by G. Carlsson, A. Dwarkanath, and B.J. Nelson.

## Homework 2

Due noon on Feb. 19, 2021.
[Link to assignment](homework/Homework_2.pdf)
[Link with corrections](homework/Homework_2_corrected.pdf)

## Day 08 - 2/9

Interleavings, Interleaving Distance, Isometry Theorem.
[Recorded Lecture](https://uchicago.zoom.us/rec/share/cae4KfdKCQJAE8G0Oo_jD68rAXojQXd5aZfCE7_Qi6o5C9Rv1ebhnnR0feZHqSiX.Og-7M2Es8tdY5WEg),  
[PDF of iPad notes](lectures/Lecture9.pdf).

__Reading__:
* Oudot Chapter 3
* Ghrist Chapter 10.6
* (Optional) "Metrics for Generalized Persistence Modules" by P. Bubenik, V. de Silva, and J. Scott.

## Day 09 - 2/11

Reach, Weak Feature Size, Sampling. [Recorded Lecture](https://uchicago.zoom.us/rec/share/uggZOFeAdD7WlI1THq4IINANgkEF8KZeBMfY7gKqlPm_u8IWrNMGZ9oZaNCfDvvo.cbywEoqHnVkv3aap?startTime=1613075840000),
[PDF of iPad Notes](lectures/Lecture10.pdf).

__Reading__:
* Oudot Chapter 4
* (Optional) "Finding the Homology of Submanifolds with High Confidence from Random Samples" by P. Niyogi, S. Smale, S. Weinberger.
* (Optional) "A Sampling Theory for Compact Sets in Euclidean Space" by F. Chazal, D. Cohen-Steiner & A. Lieutier.

## Day 10 - 2/16

Klein bottle in Image Patches.
[Recorded Lecture](https://uchicago.zoom.us/rec/share/9WqiXu1GytTCRD042sAvAmO5XzPVcgMscEeBvtDr4QVvfsiho2zqXKc3IeO46BZ9.MfTk7GKIBOACzdH5),
[PDF of iPad Notes](lectures/Lecture11.pdf).

__Reading__:
* Ghrist Chapter 5.14
* Oudot Chapter 5.5
* (Optional) "On the Local Behavior of Spaces of Natural Images" by G. Carlsson, T. Ishkhanov, V. de Silva & A. Zomorodian.
* (Optional) "Topological Estimation Using Witness Complexes" by V. de Silva and G. Carlsson.

## Day 11 - 2/18

Outliers.  Metric Measure Spaces, Distance-to-Measure.
[Recorded Lecture](https://uchicago.zoom.us/rec/share/lu8S-ONjAsGw5TMCs89j_ZfHSvTvsSyElyF9o19OaJf29EtUMKH5xwttT6O9Acm4.Irx-_SCdUak65qNI),
[PDF of iPad Notes](lectures/Lecture12.pdf).

__Reading__:
* Oudot Chapter 5.6
* (Optional) "Topological consistency via kernel estimation" by O.  Bobrowski, S. Mukherjee, J. E. Taylor.
* (Optional) "Geometric Inference for Probability Measures" by F. Chazal, D. Cohen-Steiner & Q. Mérigot.
* (Optional) "Efficient and robust persistent homology for measures" by M. Buchet, F. Chazal, S.Y. Oudot, D.R. Sheehy.

## Day 12 - 2/23

Persistent homology optimizations: cohomology algorithm, clearing, compression.
[Recorded Lecture](https://uchicago.zoom.us/rec/share/Yg3f0XR3O9hzdfqEEVL59CzwUxddcGuSU3MP-sdiDnBJAeNcC1lEHaVN7Ezb5JEC.yxbFgsDgxrvhvvSi ),
[PDF of iPad Notes](lectures/Lecture13.pdf).

__Code__: [BATS reduction](https://github.com/bnels/BATS/blob/master/include/homology/reduction.hpp)

__Reading__:
* Oudot Chapter 2.2 (especially 2.2.2)
* (Recommended) "A roadmap for the computation of persistent homology" by N. Otter, M.A. Porter, U. Tillmann, P. Grindrod & H.A. Harrington.
* (Optional) "Persistent Cohomology and Circular Coordinates" by V. de Silva, D. Morozov, and M. Vejdemo-Johansson.
* (Optional) "Dualities in persistent (co)homology" by
V. de Silva, D. Morozov, and M. Vejdemo-Johansson.
* (Optional) "Persistent Homology Computation with a Twist" by C. Chen and M. Kerber.
* (Optional) "Clear and Compress: Computing Persistent Homology in Chunks" by U. Bauer, M. Kerber, and J. Reininghaus.

## Day 13 - 2/25

Homotopy. Discrete Morse theory and simplification.
[Recorded Lecture](https://uchicago.zoom.us/rec/share/hs0S71rG6QI4G3XjtRV_Omh-_Gwg5L01U6RvpgpNWa-8BXGeCMCNobqd1mMjlbgQ.vv7LaXcWp4xSqgqC),
[PDF of iPad Notes](lectures/Lecture14.pdf).

__Reading__:
* Ghrist Chapter 7, especially 7.8
* (Optional) Hatcher Chapter 2.1 (Homotopy Invariance)
* (Optional) "Morse Theory for Filtrations and Efficient Computation of Persistent Homology" by K. Mischaikow and V. Nanda.

## Day 14 - 3/2

Zigzag zoo, sparse filtrations.
[Recorded Lecture](https://uchicago.zoom.us/rec/share/w94RJ05FKPhFvlZpDm0eY7HIetdoVwBUBSTrjVj06-OHx4oquOe3nhfjGHnSpdJs.XhU25WmgXl9jj2ib),
[PDF of iPad Notes](lectures/Lecture15.pdf).

__Reading__:
* Oudot 5.3, 5.4, 7.5.2
* (Optional) "Zigzag Zoology: Rips Zigzags for Homology Inference" by S.Y. Oudot, D.R. Sheehy.
* (Optional) "Linear-Size Approximations to the Vietoris–Rips Filtrations" by D.R. Sheehy.

## Day 15 - 3/4

Applications to clustering and regularization.
[Recorded Lecture](https://uchicago.zoom.us/rec/share/cjEwoDWl-0oA27t8b1Cib9e9dZDYsEEDceMWnAjjN3wQbaksZiahACw35Q296dYN.wUu9CPmzwBsZxSIZ),
[PDF of iPad Notes](lectures/Lecture16.pdf).

__Reading__:
* Oudot Chapter 6
* (Optional) "Persistence-Based Clustering in Riemannian Manifolds" by F. Chazal, L.J. Guibas, S.Y. Oudot, and
P. Škraba.
* (Optional) "A Topological Regularizer for Classifiers via Persistent Homology" by C. Chen, X. Ni, Q. Bai, Y. Wang.
* (Optional) "A Topology Layer for Machine Learning" by R. Brüel-Gabrielsson, B.J. Nelson, A. Dwaraknath, P. Skraba, L.J. Guibas, and G. Carlsson.

## Day 16 - 3/9

Multidimensional and Generalized Persistence.

__Reading__:
* Oudot Chapters 8 & 9
* (Optional) "The Theory of Multidimensional Persistence" by G. Carlsson and A. Zomorodian.
* (Optional) "The Theory of the Interleaving Distance on Multidimensional Persistence Modules" by M. Lesnick.
* (Optional) "Metrics for Generalized Persistence Modules" by P. Bubenik, V. de Silva, and J. Scott.

## Day 17 - 3/11

Project presentations.

## Reading Period

[Reading Period is 3/13-3/15](https://www.uchicago.edu/academics/calendar/)

## Finals Period

Final project report will be due in finals period.  Date TBD.
