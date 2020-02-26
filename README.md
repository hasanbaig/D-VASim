![Image of D-VASim](https://github.com/hasanbaig/D-VASim/blob/master/D-VASim.png)


**For Developers**
You need to have LabVIEW 2014 and the latest JAVA Development kit running on your system. 
Once installed, run the D-VASim project file (_D-VASim_v26.lvproj_) which should load all the dependencies in the project. Now you may start developing and playing around with the D-VASim source. 

**About D-VASim**

D-VASim (Dynamic Virtual Analyzer and Simulator) version 1.3 currently supports all of the major components (of latest SBML l3v1) required to simulate any SBML model except the following:

* RulesDefinition
* InitialAssignment
* Constraints

D-VASim v1.3 doesn't support the following (known) functions in kinetic mathematical equations:

* Piecewise linear function
* Logical function

D-VASim is tested with the first 400 cases of SBML Benchmark suite and produced correct results (for the supported SBML components in D-VASim v1.2) for all of them except the following 5 cases:
1.	Case 00204
2.	Case 00369
3.	Case 00370
4.	Case 00372
5.	Case 00373

These cases will be fixed in D-VASim v2.0.

**New in D-VASim v1.3**

In this upgrade, the threshold value and timing analysis algorithms are improved.  Some minor bugs are fixed. The GUI of stochastic simulation environment is also improved. 

The video demo can be seen at: https://bda.compute.dtu.dk/user-manuals/. This video demonstration is prepared using D-VASim v1.1, which performs the threshold value analysis for upper threshold level only. However, the methodology is same and the purpose of video demo is to get an idea of how D-VASim can be used to perform virtual laboratory experimentations and timing analyses. 


**Sample SBML Models**

Sample SBML models of genetic logic circuits (developed by other researchers) and some randomly chosen from SBML Test Suite are included in the installation package. For more information, please go through “Read Me” file enclosed in Sample-Test-Models folder.

**Quick Start Guide**

Quick start guide of D-VASim can be downloaded from http://bda.compute.dtu.dk/user-manuals/. 


For any help, please contact

Hasan Baig (haba@dtu.dk) 

Rao Sanaullah (mr.raosanaullah@gmail.com)
