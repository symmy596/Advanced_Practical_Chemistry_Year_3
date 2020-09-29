# Lesson Plan

<br/>

This lesson plan is intended to be a suggestion of pace, please feel free to work through the material at your own pace. 
You have 10 weeks to complete this material. 

### Week 1 - Testing and Introduction to Molecular Dynamics

The first week of this practical will be focused on ensuring all of the programs necessary to perform simulations and analysis throughout this course are correctly installed. The students will then run a quick molecular dynamics simulation on generated structures of simple materials using <code>DL_POLY</code>.

#### Learning Outcomes

- Familarise themselves with the <code>Anaconda Prompt</code>, <code>Jupyter Notebooks</code>, <code>Microsoft Teams</code>, <code>DL_POLY</code>, <code>METADISE</code>, <code>VESTA</code>, and <code>VMD</code>.
- Utilise the molecular dynamics software package <code>DL_POLY</code> to perform a simple ideal gas simulation.
- Modify <code>DL_POLY</code> input files and examine <code>DL_POLY</code> output files.
- Utilise <code>VMD</code> to perform simple analysis of system properties.

#### Lesson Plan

The students will ensure the necessary software is correctly installed using an interactive Jupyter notebook. The students will then continue to perform short molecular dynamics simulations on generated structures of simple materials. The students will manipulate the input files to examine how modifying simulation parameters such as temperature and statistical ensemble influence system properties such as energy, volume and structure.

### Week 2 - Introduction to Molecular Dynamics

Computational chemistry is often used in undergraduate laboratory exercises as a "black box". However, this is likely to reduce student engagement, as while the application is clear, the unlying mechanics are not. 

The second week of this practical will be focused on refreshing material from the second year "Introduction to computational chemistry" (CH20238) lecture module by allowing the students to interact directly with atomistic molecular dynamics simulations using the <code>pylj</code> software [1].

#### Learning Outcomes

- Understand the concepts of the Lennard-Jones potential and how it can be used in the modeling of atomic particles.
- Describe the Coulomb potential, and its importance in the modeling of ionic systems.
- Recognise the *recipe* associated with a molecular dynamics simulation.
- Be able to build a molecular dynamics simulation, using the <code>pylj</code> framework.
- Utilise the molecular dynamics simulation to study a system deviating from ideal gas behaviour.

#### Lesson Plan

The will be a self-led workshop where students will (in their own time) be able to work through an interactive <code>Jupyter notebook</code>, which will detail the mechanism of atomistic simulation. At the end, the students will use the <code>pylj</code> framework to build a simple molecular dynamics simulation and use this to preform a straight-forward application of molecular dynamics. This application will involve running simulations at a series of different atomic densities to reflect on the effect of density on a *typical* ideal gas system.

This will likely take three quarters of the day and students are welcome to begin the week 3 tutorial. 

##### Assesment

- This week will form the basis for the methodology portion of the students report.

### Week 3 - Introduction to Transport Properties

The transport proerties of a material are crucial for many modern technologies, from batteries/fuel cells to nuclear materials. Week three of this practical will allow students to apply their understanding of molecular dynamics simulations, from week two, and apply it to some *real world* applications. The students will run molecular dynamics simulations on fluorite (CaF<sub>2</sub>), and analyse the transport properties of the material to determine temperature range when CaF<sub>2</sub> is superionic and to find the activation energy for F migration in this range.

#### Learning Outcomes

- Understanding of the importance of mean squared displacement, and its relavance to molecular simulation.
- Application of first year kinetics to computational chemistry, by the investigation of the Arrhenius relation for transport in CaF<sub>2</sub>.

#### Lesson Plan

The students will run a molecular dynamics simulation of CaF<sub>2</sub> before running through a <code>Jupyter notebook</code> tutorial detailing how a mean squared displacment may be determined. Following this the molecular dynamics simulation will be repeated at a series of different temperatures, with the mean square displacement determined each time and the data used to investigate the Arrhenius relationship. 

#### Assesment

- Mean squared displacement and Arrhenius relationship theory will form part of the methodology portion of the students report.
- The data measured will form components of the students' results.

### Weeks 4 and 5 - Defect Chemistry

As with people, no material is without defects. There are two main types of defect that exist in materials,
- Frenkel defects -- an atom is displaced in the lattice to an interstitial site; creaing a vacancy,
- Schottky defects -- a formula unit is missing from the lattice, creating (usually) a pair of vacancies.

Week 4 will see the students introducing Schottky defects to their CaF<sub>2</sub> configurations from the previous week. They will determine the effect that these defects have on the transport properties studied previously. In this week the students are expected to apply the skills that they have learned in weeks 2 and 3 to design their own simulations.

Week 5 will see the students introducing Frenkel defects to their CaF<sub>2</sub> configurations from the previous week They will determine the effect that these defects have on the transport properties studied previously. In this week the students are expected to apply the skills that they have learned in weeks 2 and 3 to design their own simulations.

#### Learning Outcomes

- Understanding of the nature of Frenkel and Schottky defects.
- Rationisation of the effect that such defects have on the transport properties of a material.

#### Lesson Plan

This process of this week ultimately lays with the student. However, the expectation is that the students will add cation Frenkel defects to the CaF<sub>2</sub> in different quantities assessing the impact on transport properties. The same will then be conducted with Schottky defects.

#### Assesment

- Key Report Question - How do Frenkel/Schottky defects affect the transport properties?

### Weeks 6 and 7 - Dopants

The doping of a material with different elements in order to obtain a desired property is now common practice, particularly for fuel cell materials, for example CeO<sub>2</sub> is doped with Gd<sup>3+</sup> to improve the oxygen transport, and therefore conductivity of the material. In this final data generation week, students will investigate how the doping of cations into the CaF<sub>2</sub> structure affects the transport properties. Is it possible to increase the diffusion coefficient over the undoped material.

#### Learning Outcomes

- Assess the effect of dopant atoms on the properties of CaF<sub>2</sub>.
- Understand the role of the computational scienctist in materials discovery and development.

#### Lesson Plan

As with weeks four and five, this process ultimately lays with the student. The expectation is that the student will select four or five relevant cations to add to the CaF<sub>2</sub> structure and determine the diffusion coefficient of each.

#### Assesment

- Key Report Question - How do dopants affect the tranport properties?   


### Week 8 - Data Collection

This week allows the students to collate the data collected by the group and to perform any remaining calculations necessary. 

### Week 9 - Report Writing

This week allows the student to write up the bulk of their report.

### Summary

Over the 9 weeks, the students will transition from a being lead through and introduction to molecular dynamics and shown how to run molecular simulation to being able to research independently the properties of a material. Week one will focus on an introduction to molecular dynamics, week two will introduce the underlaying theory of molecular simulation, week three will introduce the students to the process of running molecular dynamics simulations. While, in weeks four through seven the students are expected to independently apply this knowledge to design simulation that answer questions common to computational chemists.

### References

1. McCluskey et al., (2018). pylj: A teaching tool for classical atomistic simulation . Journal of Open Source Education, 1(2), 19, https://doi.org/10.21105/jose.00019
