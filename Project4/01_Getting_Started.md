# NERSC-HPC-Project 4

## Introduction

High-performance computing (HPC) has revolutionized various fields, from climate modeling to drug discovery and astrophysics. HPC allows researchers to simulate complex phenomena and systems, leading to significant scientific advances.
However, HPC systems require substantial power and generate large amounts of heat, which can be challenging. Addressing these challenges is critical for the sustainability of HPC systems, both from an environmental and a social justice perspective.

In this project you'll delve into the intersection of social justice, energy, and power sustainability in HPC. You'll explore the relationship between the location of HPC centers, their energy usage, and their impact on climate change indicators and low-income energy affordability data.


### Preliminary and Supportive Resources
Accessing NERSC Perlmutter: https://docs.nersc.gov/systems/perlmutter/


Compiling Code on Perlmutter: https://docs.nersc.gov/systems/perlmutter/#compilingbuilding-software


Accessing JupyterHub on Perlmutter: https://docs.nersc.gov/services/jupyter/


### Reading Resources on Ennergy Consumption and HPC


https://www.top500.org/static/media/uploads/methodology-2.0rc1.pdf


Using Thermosyphon Hybrid Cooling System to Optimize Data Center Water Efficiency, DOE Fact Sheet (2019). Avaialble at https://www.nrel.gov/docs/fy19osti/73644.pdf


Advanced Computing, Data Science, and Artificial Intelligence Research Opportunities for Energy-Focused Transportation Science, NREL Technical Report (2021) available at https://www.nrel.gov/docs/fy21osti/79589.pdf


Kocot B, Czarnul P, Proficz J. Energy-Aware Scheduling for High-Performance Computing Systems: A Survey. Energies. 2023; 16(2):890. https://doi.org/10.3390/en16020890 Available at:
https://www.mdpi.com/1996-1073/16/2/890


### Project Goal
By the end of this project, you'll gain insights into the environmental and social implications of HPC systems, explore energy efficiency assessments, analyze performance and power data, and develop recommendations for energy-sustainable HPC systems.


### Prerequisites
No prior HPC knowledge is required. We will guide you through all the necessary steps!


## Module 1: Introduction to HPC and Energy Efficiency


In this module, you'll be introduced to the concept of HPC and the challenges it presents in terms of power consumption and cooling requirements. You'll learn about the importance of energy efficiency in HPC systems and the potential impact of these systems on marginalized populations.


### Understanding Power and Energy Consumption in HPC


High Performance Computing (HPC) systems are at the forefront of scientific research, enabling complex simulations, data analysis, and solving intricate problems that are otherwise infeasible with conventional computing resources. However, the importance of power and energy consumption in HPC systems cannot be overstated. The massive computational power demanded by these systems leads to high energy requirements, resulting in significant environmental and economic implications. Efficient power management is crucial to ensure the sustainability of HPC centers and reduce their carbon footprint. Excessive power consumption not only escalates operational costs but also contributes to greenhouse gas emissions, impacting the environment and exacerbating climate change.


Efforts to optimize energy consumption in HPC systems can lead to energy justice and sustainability. Energy justice refers to the equitable distribution of benefits and burdens related to energy production and consumption. By addressing power efficiency in HPC, it becomes possible to reduce the strain on local power grids and alleviate the risk of energy shortages, which often disproportionately affect low-income communities. Additionally, improved energy efficiency can lower the overall cost of running HPC systems, making these resources more accessible to researchers and organizations with limited financial means. Striving for sustainability and energy justice in HPC not only benefits society by democratizing access to advanced computing capabilities but also aligns with global initiatives to mitigate the impacts of climate change.


Therefore, it is important to keep in mind that power and energy consumption are fundamental considerations in High Performance Computing systems. Enhancing energy efficiency in HPC is not only crucial for the sustainable operation of these systems but also plays a role in promoting energy justice and making advanced computational resources more accessible to all, including low-income communities. By prioritizing power optimization, HPC centers can contribute to a greener, more equitable future while continuing to drive scientific innovation and discovery.


## Module 2: Performance and Energy Efficiency Assessment of HPC Systems


In this module, we will delve into the fascinating world of High Performance Computing (HPC) applications. Get ready for a hands-on experience where you will have the opportunity to execute and submit HPC applications, while also gaining valuable insights into the performance and power data associated with these systems for various workloads. By the end of this module, you will not only sharpen your technical skills but also develop a deeper understanding of the profound environmental and social implications of HPC systems.


### Introduction to HPC Applications and Scientific Domains


We kick off the module with an exploration of HPC applications and their significance in today's scientific and computational landscape. You will learn about the diverse range of problems that HPC can tackle, from complex simulations in physics, climate modeling, and engineering to data-intensive tasks in genomics and machine learning. Through interactive sessions and real-world case studies, you'll understand how HPC systems have revolutionized research and enabled breakthrough discoveries across various domains.


### Understanding Parallel Computing:


Parallel computing is a technique where multiple tasks are executed simultaneously to solve a problem faster. The NERSC Perlmutter system supports parallel computing through Message Passing Interface (MPI) for inter-process communication. Each application in this module utilizes parallelism to leverage the full potential of the supercomputing system.


### Performance Measurement and Optimization:
When working with HPC applications, it's essential to measure and optimize their performance. Performance measurement helps identify bottlenecks, understand resource utilization, and optimize the code for efficiency. Common metrics for performance measurement include execution time, scalability, and memory usage.


### Running Parallel Applications:

To execute parallel applications on NERSC Perlmutter, we use the SLURM workload manager. SLURM allows you to submit batch jobs to the system, allocate resources, and run tasks in parallel. The provided batch script is a template for running applications using SLURM.


#### Applications for Analysis

Optical Properties of Materials Workflow: https://gitlab.com/NERSC/N10-benchmarks/berkeleygw-workflow

Materials by Design Workflow: https://gitlab.com/NERSC/N10-benchmarks/exaalt

Lattice QCD Workflow: https://gitlab.com/NERSC/N10-benchmarks/lattice-qcd-workflow


#### Running Parallel Applications

To execute parallel applications on NERSC Perlmutter, we use the SLURM workload manager. SLURM allows you to submit batch jobs to the system, allocate resources, and run tasks in parallel. The provided batch script is a template for running applications using SLURM.


Steps to Run the Benchmarks:

Step 1: Copy the GitHub repositories for the three NERSC-10 Benchmarks (if not already done).

Step 2: Submitting the Benchmarks with SLURM:

### Module 2 Conclusion:

This module provides a foundation for working with HPC applications, parallel computing, and measuring performance on the NERSC Perlmutter supercomputing system. Understanding how to execute parallel applications efficiently and measure their performance will enable you to tackle more complex scientific simulations and data analysis in the future.

## Module 3: Analyzing NERSC Platform Performance and Power Analysis

In this module, you'll be introduced to data analysis in the context of HPC. Using provided data sets, you'll investigate the distribution of projects and users, resource allocations, utilization rates, and the relationships between various data fields. This will develop your skills in data analysis and interpretation, and encourage critical thinking and data visualization.


***Please click here to access the Juypter Notebook for this exercise ***


**** Optional Additional Supportive Resources will be added here ****


## Module 4: Analysis of NERSC Applications and HPC Systems in the Top 500 and Green500


Welcome to Module 4 of the Intro to High-Performance Computing (HPC) workshop! In this module, we will build on the knowledge gained from the previous sessions and shift our focus to analyzing and comparing the energy efficiency of HPC systems listed in the Top500 and Green500 rankings. As HPC continues to grow in scale and significance, understanding the energy efficiency of these systems becomes crucial due to their environmental and economic impact.

### Understanding the Top500 and Green500 Rankings:**

The Top500 and Green500 are internationally recognized lists that rank the most powerful and energy-efficient supercomputers, respectively. The Top500 ranks systems based on their performance, measured in floating-point operations per second (FLOPS). In contrast, the Green500 ranks systems based on their energy efficiency, measured in FLOPS per watt.

### Assessing Energy Efficiency of HPC Systems:**
In this module, we'll conduct an energy efficiency assessment of specific HPC systems or centers listed in the Top500 and Green500. We'll take into account various factors, including:


1. Power Consumption: We'll analyze the power consumption of HPC systems to understand their energy requirements. Power consumption data is crucial for assessing the operational costs and environmental impact of these systems.

2. Cooling Mechanisms: Efficient cooling is essential to maintain the optimal performance and longevity of HPC systems. We'll explore the cooling mechanisms employed by the listed systems to manage heat dissipation effectively.

3. Location Details: The geographical location of HPC centers can significantly impact their energy consumption. We'll examine how different locations influence the energy efficiency of these systems.

4. Performance Metrics: Energy efficiency is not solely about power consumption. We'll consider performance metrics like FLOPS and memory bandwidth to assess how efficiently the systems handle computational workloads.


#### Hands-on Analysis:
To gain a practical understanding of energy efficiency analysis, we'll work on real-world case studies involving specific HPC systems or centers. We'll use available data from the Top500 and Green500 lists, along with other relevant sources.


#### Discussion and Insights:**
During the analysis, we'll engage in discussions about the findings, exploring reasons for variations in energy efficiency among different systems. We'll consider factors such as hardware architecture, system design, cooling strategies, and power management techniques.


#### Implications and Future Directions:**
Energy-efficient HPC systems have a positive impact on both the environment and the operational costs for organizations. We'll discuss the implications of our analysis and consider future trends and innovations in HPC system design to achieve even higher energy efficiency.


### Module 4 Conclusion
This module will equip you with valuable insights into the energy efficiency of HPC systems listed in the Top500 and Green500 rankings. By analyzing real-world case studies, you'll develop a better understanding of the environmental and economic implications of these high-performance computing machines. The knowledge gained in this module will help you make informed decisions in the design and deployment of HPC systems in your future endeavors.


Let's dive into the exciting world of energy-efficient HPC systems and explore the trends shaping the future of supercomputing!

## Module 5: Recommendations for Energy-Sustainable HPC Systems at Department of Energy Labs
In the final module, you'll synthesize your insights from the previous modules and develop recommendations for energy-sustainable HPC systems at Department of Energy (DOE) labs. You'll consider energy-efficient hardware technologies, power management techniques, integration of renewable energy sources, optimization of cooling mechanisms, and collaborations with energy and sustainability experts.

Supportive Resources will be added here


## Module 5 Conclusion
By the end of this tutorial, you'll have a deeper understanding of the environmental and social implications of HPC systems. You'll have hands-on experience with analyzing performance and power data and developing recommendations for energy-sustainable HPC systems. This knowledge will contribute to a more environmentally conscious and socially responsible approach to computing.


## Authors and acknowledgment
- Daniel Fulton, NERSC/Lawrence Berkeley National Laboratory https://www.nersc.gov/about/nersc-staff/data-analytics-services/daniel-fulton/
- - Lipi Gupta, NERSC/Lawrence Berkeley National Laboratory https://www.nersc.gov/about/nersc-staff/user-engagement/lipi-gupta/
-Rebecca Hartman-Baker, NERSC/Lawrence Berkeley National Laboratory https://www.nersc.gov/about/nersc-staff/user-engagement/rebecca-hartman-baker/
- 
- Helen He, NERSC/Lawrence Berkeley National Laboratory https://www.nersc.gov/about/nersc-staff/user-engagement/yun-helen-he/
- 
- Charles Lively, NERSC/Lawrence Berkeley National Laboratory https://www.nersc.gov/about/nersc-staff/user-engagement/charles-lively/
- 
- Rollin Thomas, NERSC/Lawrence Berkeley National Laboratory https://www.nersc.gov/about/nersc-staff/programming-environments-and-models/rollin-thomas/


https://shinstitute.org/intro-to-hpc-bootcamp/


## License
For open source projects, say how it is licensed.


## Project status
If you have run out of energy or time for your project, put a note at the top of the README saying that development has slowed down or stopped completely. Someone may choose to fork your project or volunteer to step in as a maintainer or owner, allowing your project to keep going. You can also make an explicit request for maintainers.



