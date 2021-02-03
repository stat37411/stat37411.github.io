# Schedule

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

Pairs, barcodes, diagrams, bottleneck distance, features.  [Recorded Lecture](https://uchicago.zoom.us/rec/share/TTpfIhLRMsulKsVqKU-2oWUrL565aZFPu0TZVoH8hJv33tArsVi5lfqqpcLfCWBI.1WLf0xDjPHBuYFda?startTime=1612298099000)  [PDF of iPad notes](lectures/Lecture7.pdf) - note that I also showed some figures from the papers below.

__Code__:

__Reading__:
* Oudot Chapter 3, Section 1.1
* (Optional) "Stability of Persistence Diagrams" by  S. Cohen-Steiner, H. Edelsbrunner, and J. Harer.
* (Optional) "Gromov-Hausdorff Stable Signatures for Shapesusing Persistence" by F. Chazal, D. Cohen-Steiner, L.J. Guibas, F. Mémoli, and S.Y. Oudot.
* (Optional) "The Ring of Algebraic Functions on Persistence Bar Codes" by A. Adcock, E. Carlsson, and G. Carlsson.
* (Optional) "Statistical Topological Data Analysis using Persistence Landscapes" by P. Bubenik.

## Day 07 - 2/4

Quiver Representations, Zigzag Homology.

__Code__:

__Reading__:
* Oudot Chapter 1
* Ghrist Chapters 5.13, 5.15
* (Optional) "Zigzag Persistence" by G. Carlsson and V. de Silva.
* (Optional) "Zigzag Persistent Homology and Real-valued Functions" by G. Carlsson, V. de Silva, and D. Morozov.
* (Optional) "Persistent and Zigzag Homology: A Matrix Factorization Viewpoint" by G. Carlsson, A. Dwarkanath, and B.J. Nelson.


## Reading Period

[Reading Period is 3/13-3/15](https://www.uchicago.edu/academics/calendar/)

## Finals Period

Final project report will be due in finals period.  Date TBD.
