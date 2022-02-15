# Schedule - Winter 2022

**Note that the start of classes has been delayed 1 week**

This course follows a Monday/Wednesday Schedule.  There is a section for each day, with materials for that day.  This schedule is subject to change before a class is held.

Links to readings can be found on the [resources page](resources.md).

Schedule Archives: [Winter 2021](archive/schedule_w2021.md)

## Day 00 - 1/10

Introduction to topological data analysis.  

[Lecture Recording](https://uchicago.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=21ece05a-0e31-4689-ab28-ae1a0062c213) / [iPad Notes](lectures/Lecture_01.pdf) / [Transcribed Notes](notes/Topological_Data_Analysis_STAT37411_notes.pdf#chapter.1)

__Code:__
* [Demo Notebook for Class](https://github.com/stat37411/lectures/blob/main/winter2022/Lecture%201.ipynb)

__Reading:__
* Introduction of Oudot,
* peruse Chapter 2 of Ghrist,
* peruse "Topological pattern recognition for point cloud data" by Carlsson.

## Day 01 - 1/12

Preliminaries: Graphs, Clustering, Disjoint Set/Union-find, the Graph Laplacian.

[Lecture Recording](https://uchicago.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=5a5a21b0-3d49-4c74-8113-ae1b0139e0f5) / [iPad Notes](lectures/Lecture_02.pdf) / [Transcribed Notes](notes/Topological_Data_Analysis_STAT37411_notes.pdf#chapter.1)

__Code:__
* [`union_find.hpp`](https://github.com/stat37411/tda/blob/main/include/union_find.hpp)
* [Notebook on Spectral Clustering](https://github.com/stat37411/lectures/blob/main/winter2022/Lecture%202.ipynb)

__Reading:__
* (Recommended) "An Impossibility Theorem for Clustering" by Jon Kleinberg: [link](An Impossibility Theorem for Clustering)
* (Optional) "A tutorial on spectral clustering" by von Luxburg.
* (Optional) You can also find some notes on spectral clustering in Python [here](https://caam37830.github.io/book/05_graphs/spectral.html).

## Day 02 - 1/17

**MLK Day. No Class**

## Day 03 - 1/19

Basic Topology (spaces, maps, homotopy).  Simplicial Complexes.  Simplicial Maps.  Constructions.

[Lecture Recording](https://uchicago.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=dd368457-38ed-4039-b22b-ae22013a3f6d) / [iPad Notes](lectures/Lecture_03.pdf)

__Code:__
* [Demo Notebook for Class](https://github.com/stat37411/lectures/blob/main/winter2022/Lecture%203.ipynb)

__Reading:__
* Ghrist: Preface and Chapter 2.
* (Optional): Munkres Sections 1.1 and 1.2.
* (Optional): Hatcher Chapter 0.


## Day 04 - 1/24

Nerve of a cover, witness complexes, Mapper algorithm. Tries.

[Lecture Recording](https://uchicago.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=ef3e8e79-ac56-4cf2-9a00-ae2701352cd4) / Zoom dropped the call for the final 20 minutes, which was a discussion of use of Mapper by Li et al. in the readings below, and a brief overview of the trie data structure.

__Code:__ [`trie.py`](https://github.com/stat37411/tda/blob/main/tda/trie.py)  [`simplicial_complex.py`](https://github.com/stat37411/tda/blob/main/tda/simplicial_complex.py)  [demo notebook](https://github.com/stat37411/tda/blob/main/ipynb/simplex.ipynb)

For an open-source Mapper implementation (in Python), check out [Kepler Mapper](https://kepler-mapper.scikit-tda.org/en/latest/).

__Reading:__
* "Topological Estimation Using Witness Complexes" by V. de Silva and G. Carlsson.
* "Topological Methods for the Analysis of High Dimensional Data Sets and 3D Object Recognition" by G. Singh, F. Memoli, and G. Carlsson.
* (Optional) "The Simplex Tree: An Efficient Data Structure for General Simplicial Complexes" by J.D. Boissonnat and C. Maria.
* (Optional) "Extracting insights from the shape of complex data using topology" by P. Y. Lum et al.
* (Optional) "Identification of type 2 diabetes subgroups through topological analysis of patient similarity" by L. Li et al.

## Homework 1

Due 10:30am on Feb. 9, 2022. [Link](homework/Homework_1.pdf)

## Day 05 - 1/26

(Cellular) chain complexes, (Cellular) homology, reduction algorithm.  

[Lecture Recording](https://uchicago.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=40b97ce2-fdaa-4ab5-8eea-ae29012f23da)

__Code:__ [chain.ipynb](https://github.com/stat37411/tda/blob/main/ipynb/chain.ipynb)

__Reading:__
* Ghrist Chapter 4
* "Computing Persistent Homology" by A. Zomorodian and G. Carlsson.
* (Optional) "Persistent and Zigzag Homology: A Matrix Factorization Viewpoint" by G. Carlsson, A. Dwarkanath, and B.J. Nelson, sections 2.2-2.5
* (Optional) Hatcher Chapter 2 (2.2 is most relevant)
* (Optional) "Topological Persistence and Simplification" by H. Edelsbrunner, D. Letscher and A. Zomorodian.


## Day 06 - 1/31

Reduction algorithm, persistent homology.

[Lecture Recording](https://uchicago.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=de85d7a9-32e1-4e5d-93ee-ae2e01326ee4)

__Code:__

__Reading:__
* Oudot Chapter 2
* "Computing Persistent Homology" by A. Zomorodian and G. Carlsson.
* (Optional) "Persistent and Zigzag Homology: A Matrix Factorization Viewpoint" by G. Carlsson, A. Dwarkanath, and B.J. Nelson, sections 2.6, 2.7
* (Optional) For some nice visualizations, see Anjan Dwaraknath's Slides: [Link](https://anjandn.github.io/quivertalkslides/)


## Day 07 - 2/2

(Persistent) homology wrap-up, basic implementation, clearing & compression optimizations.

[Lecture Recording](https://uchicago.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=6cde2e4c-49d2-48f3-b8b2-ae3100f7da91) / [iPad Notes](lectures/Lecture_07.pdf)

__Code:__
[filtration.ipynb](https://github.com/stat37411/tda/blob/main/ipynb/filtration.ipynb),
[reduction.py](https://github.com/stat37411/tda/blob/main/tda/reduction.py),
[chain.py](https://github.com/stat37411/tda/blob/main/tda/chain.py),
[BATS reduction](https://github.com/bnels/BATS/blob/master/include/homology/reduction.hpp),
[Reduction options in BATS](https://bats-tda.readthedocs.io/en/latest/tutorials/Rips.html)

__Reading:__
* "Computing Persistent Homology" by A. Zomorodian and G. Carlsson.
* Oudot Chapter 2.2 (especially 2.2.2)
* (Recommended) "A roadmap for the computation of persistent homology" by N. Otter, M.A. Porter, U. Tillmann, P. Grindrod & H.A. Harrington.
* (Optional) "Persistent Homology Computation with a Twist" by C. Chen and M. Kerber.
* (Optional) "Clear and Compress: Computing Persistent Homology in Chunks" by U. Bauer, M. Kerber, and J. Reininghaus.


## Day 08 - 2/7

Pairs, barcodes, diagrams, bottleneck distance, features.

[Lecture Recording](https://uchicago.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=127e86b6-0b99-45ac-a96a-ae35013e325a)

__Code__: [notebook on diagrams and distances](https://github.com/stat37411/tda/blob/main/ipynb/persistence_diagrams_and_distances.ipynb)

__Reading__:
* Oudot Chapter 3, Section 1.1
* (Optional) "Stability of Persistence Diagrams" by  S. Cohen-Steiner, H. Edelsbrunner, and J. Harer.
* (Optional) "Gromov-Hausdorff Stable Signatures for Shapesusing Persistence" by F. Chazal, D. Cohen-Steiner, L.J. Guibas, F. Mémoli, and S.Y. Oudot.
* (Optional) "The Ring of Algebraic Functions on Persistence Bar Codes" by A. Adcock, E. Carlsson, and G. Carlsson.
* (Optional) "Statistical Topological Data Analysis using Persistence Landscapes" by P. Bubenik.

## Day 09 - 2/9

Quiver Representations, Zigzag Homology.

[Lecture Recording](https://uchicago.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=1dc98354-cba2-4f42-8368-ae380055ae04)

__Code__: [Algorithm in BATS](https://github.com/CompTop/BATS/blob/master/include/quiver/sparse.hpp#L106)

__Reading__:
* Oudot Chapter 1
* Ghrist Chapters 5.13, 5.15
* (Optional) "Zigzag Persistence" by G. Carlsson and V. de Silva.
* (Optional) "Zigzag Persistent Homology and Real-valued Functions" by G. Carlsson, V. de Silva, and D. Morozov.
* (Optional) "Persistent and Zigzag Homology: A Matrix Factorization Viewpoint" by G. Carlsson, A. Dwarkanath, and B.J. Nelson.


## Day 10 - 2/14


Interleavings, Interleaving Distance, Isometry Theorem.

[Lecture Recording](https://uchicago.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=535e16f1-3583-44e8-9e03-ae3c0175ad7e)

__Reading__:
* Oudot Chapter 3
* Ghrist Chapter 10.6
* (Optional) "Metrics for Generalized Persistence Modules" by P. Bubenik, V. de Silva, and J. Scott.


## Day 11 - 2/16

Interleavings Part II

## Day 11 - 2/16

Reach, Weak Feature Size, Sampling.

__Reading__:
* Oudot Chapter 4
* (Optional) "Finding the Homology of Submanifolds with High Confidence from Random Samples" by P. Niyogi, S. Smale, S. Weinberger.
* (Optional) "A Sampling Theory for Compact Sets in Euclidean Space" by F. Chazal, D. Cohen-Steiner & A. Lieutier.

## Day 12 - 2/21

Klein bottle in Image Patches.


__Reading__:
* Ghrist Chapter 5.14
* Oudot Chapter 5.5
* (Optional) "On the Local Behavior of Spaces of Natural Images" by G. Carlsson, T. Ishkhanov, V. de Silva & A. Zomorodian.
* (Optional) "Topological Estimation Using Witness Complexes" by V. de Silva and G. Carlsson.

## Day 13 - 2/23

Outliers.  Metric Measure Spaces, Distance-to-Measure.

__Reading__:
* Oudot Chapter 5.6
* (Optional) "Topological consistency via kernel estimation" by O.  Bobrowski, S. Mukherjee, J. E. Taylor.
* (Optional) "Geometric Inference for Probability Measures" by F. Chazal, D. Cohen-Steiner & Q. Mérigot.
* (Optional) "Efficient and robust persistent homology for measures" by M. Buchet, F. Chazal, S.Y. Oudot, D.R. Sheehy.

## Day 14 - 2/28

Cohomology, Applications

__Code__:

__Reading__:
* (Optional) "Persistent Cohomology and Circular Coordinates" by V. de Silva, D. Morozov, and M. Vejdemo-Johansson.
* (Optional) "Dualities in persistent (co)homology" by
V. de Silva, D. Morozov, and M. Vejdemo-Johansson.

## Day 15 - 3/2

Homotopy. Discrete Morse theory and simplification.

__Reading__:
* Ghrist Chapter 7, especially 7.8
* (Optional) Hatcher Chapter 2.1 (Homotopy Invariance)
* (Optional) "Morse Theory for Filtrations and Efficient Computation of Persistent Homology" by K. Mischaikow and V. Nanda.

## Day 16 - 3/7

Zigzag zoo, sparse filtrations.

__Reading__:
* Oudot 5.3, 5.4, 7.5.2
* (Optional) "Zigzag Zoology: Rips Zigzags for Homology Inference" by S.Y. Oudot, D.R. Sheehy.
* (Optional) "Linear-Size Approximations to the Vietoris–Rips Filtrations" by D.R. Sheehy.

## Day 17 - 3/9

Applications to clustering and regularization.

__Reading__:
* Oudot Chapter 6
* (Optional) "Persistence-Based Clustering in Riemannian Manifolds" by F. Chazal, L.J. Guibas, S.Y. Oudot, and
P. Škraba.
* (Optional) "A Topological Regularizer for Classifiers via Persistent Homology" by C. Chen, X. Ni, Q. Bai, Y. Wang.
* (Optional) "A Topology Layer for Machine Learning" by R. Brüel-Gabrielsson, B.J. Nelson, A. Dwaraknath, P. Skraba, L.J. Guibas, and G. Carlsson.

## Day 18

Multidimensional and Generalized Persistence.

__Reading__:
* Oudot Chapters 8 & 9
* (Optional) "The Theory of Multidimensional Persistence" by G. Carlsson and A. Zomorodian.
* (Optional) "The Theory of the Interleaving Distance on Multidimensional Persistence Modules" by M. Lesnick.
* (Optional) "Metrics for Generalized Persistence Modules" by P. Bubenik, V. de Silva, and J. Scott.

## Day 18

Project presentations.

## Reading Period

[Reading Period is 3/12-3/14](https://www.uchicago.edu/academics/calendar/)

## Finals Period

Final project report will be due in finals period.  Date TBD.
