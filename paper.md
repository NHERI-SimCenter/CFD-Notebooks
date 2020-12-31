---
title: 'CFD Notebooks: Learning OpenFOAM for HPC'
tags:
- Python
- CFD
- OpenFOAM
- numerical methods
- finite differences
authors:
- name: Ajay B. Harish
  orcid: 0000-0001-5234-7047
  affiliation: "1, 2"
- name: Frank McKenna
  affiliation: 2
- name: Sanjay Govindjee
  orcid: 0000-0003-0711-3633
  affiliation: "1, 2"

affiliations:
- name: Department of Civil and Environmental Engineering, University of California, Berkeley, CA (USA)
  index: 1
- name: NHERI SimCenter, University of California, Berkeley, CA (USA)
  index: 2
date: 25 Dec 2020
bibliography: paper.bib
---

# Summary

The **CFD Notebooks** are a set of Jupyter notebooks aimed at senior undergraduate and early graduate students who are interested in learning OpenFOAM. It is aimed to allow the learner to get started with the open-source CFD tool OpenFOAM and to run it on Designsafe. It provides a foundation for all aspects of OpenFOAM, from running cases to programming, so is useful to both new users and existing users wishing to broaden their basic knowledge of OpenFOAM. The learners are exposed to running exercises and simulating cases in OpenFOAM using a HPC computing platform, accessed directly through the Jupyter notebook. The Jupyter notebooks consist of video tutorials, DIY examples, and general reading materials. This learning tool is truly platform-independent and leverages the power of HPC. At present, CFD Notebooks are hosted and uses the Designsafe's supercomputing infrastructure at the Texas Advanced Computing Center, particularly the Stampede2 and Frontera clusters.

The notebooks are broken up into various editions, each with four lessons: Beginner / Intermediate / Expert / Professional. At present, only the beginner edition is available. The beginner edition of the notebook includes four lessons:

* Lesson 1 (Introduction to OpenFOAM and Designsafe): Introduces the learner to basic structure of OpenFOAM and Designsafe cyberinfrastructure. 

* Lesson 2 (Different solvers in OpenFOAM and which to use?): Helps learner identify different types of solvers in OpenFOAM (laminar vs. turbulent; steady-state vs. transient).

* Lesson 3 (Boundary conditions in OpenFOAM): While the number of boundary conditions are several, the lesson introduces the learner to the basic boundary conditions and their meaning.

* Lesson 4 (Meshing in OpenFOAM (blockMesh)): The lesson introduces the learner to the basics of blockMesh utility in OpenFOAM.

## Learning objectives

Upon completion of this beginner series, you should have the ability to:

- Modify the files and file directories of OpenFOAM
- Modify and setup boundary conditions
- Mesh using blockMesh utilities
- Run OpenFOAM jobs on supercomputing cluster Stampede2
- Be exposed to Agave API and Jupyter notebooks
- Visualize OpenFOAM results using Paraview

# Statement of need

There are several tutorials available on Youtube, particularly with regard to the usage of OpenFOAM for CFD. ThE CFD Notebooks are not an alternative to these video tutorials but as a complementary to convetional classroom and online Computational Fluid Dynamics (CFD) courses like ``CFD Python: the 12 steps to Navier-Stokes equations'' [@Barba2019].

Today, OpenFOAM is one of the widely used open-source tools for CFD modeling and simulation and in this regard. However, inspite of the several tutorials available out there, CFD Notebooks provide a structured course to help the students to learn OpenFOAM.



Further on, OpenFOAM simulations are, most often, prohibitively expensive to perform on a user’s local computer. However, it is hard for many student users to get access to HPC facilities, particularly a command line access (CLI) that provides for a full flexibility to use OpenFOAM. CFD Notebooks are seamlessly integrated to facilitate the learners to perform the computations remotely on the Teas Advanced Computing Center (TACC) super computing facility. The users of CFD Notebooks have access to the Stampede and Frontera clusters of the TACC. Today, Stampede and Frontera are among the top 20 supercomputers in the world. The access to the Texas Advanced Computing Center (TACC) is made available to the user through NHERI DesignSafe, the cyberinfrastructure provider for the distributed NSF funded Natural Hazards in Engineering Research Infrastructure (NHERI) facility. 

# Functionality and usage

Notes on instructions ot be added here

# Recent Uses

The CFD Notebooks are planned to be used in the classroom course on Fluid Mechanics at Stanford and UC Berkeley in the coming semester.

# References
