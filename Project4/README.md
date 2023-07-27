# NERSC-HPC-Project 1



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

## Add your files

- [ ] [Create](https://docs.gitlab.com/ee/user/project/repository/web_editor.html#create-a-file) or [upload](https://docs.gitlab.com/ee/user/project/repository/web_editor.html#upload-a-file) files
- [ ] [Add files using the command line](https://docs.gitlab.com/ee/gitlab-basics/add-file.html#add-a-file-using-the-command-line) or push an existing Git repository with the following command:

```
cd existing_repo
git remote add origin https://gitlab.com/nersc-hpc/NERSC-HPC-Projects.git
git branch -M main
git push -uf origin main
```

## Integrate with your tools

- [ ] [Set up project integrations](https://gitlab.com/nersc-hpc/NERSC-HPC-Projects/-/settings/integrations)

## Collaborate with your team

- [ ] [Invite team members and collaborators](https://docs.gitlab.com/ee/user/project/members/)
- [ ] [Create a new merge request](https://docs.gitlab.com/ee/user/project/merge_requests/creating_merge_requests.html)
- [ ] [Automatically close issues from merge requests](https://docs.gitlab.com/ee/user/project/issues/managing_issues.html#closing-issues-automatically)
- [ ] [Enable merge request approvals](https://docs.gitlab.com/ee/user/project/merge_requests/approvals/)
- [ ] [Set auto-merge](https://docs.gitlab.com/ee/user/project/merge_requests/merge_when_pipeline_succeeds.html)

## Test and Deploy

Use the built-in continuous integration in GitLab.

- [ ] [Get started with GitLab CI/CD](https://docs.gitlab.com/ee/ci/quick_start/index.html)
- [ ] [Analyze your code for known vulnerabilities with Static Application Security Testing(SAST)](https://docs.gitlab.com/ee/user/application_security/sast/)
- [ ] [Deploy to Kubernetes, Amazon EC2, or Amazon ECS using Auto Deploy](https://docs.gitlab.com/ee/topics/autodevops/requirements.html)
- [ ] [Use pull-based deployments for improved Kubernetes management](https://docs.gitlab.com/ee/user/clusters/agent/)
- [ ] [Set up protected environments](https://docs.gitlab.com/ee/ci/environments/protected_environments.html)

***

# Editing this README

When you're ready to make this README your own, just edit this file and use the handy template below (or feel free to structure it however you want - this is just a starting point!). Thank you to [makeareadme.com](https://www.makeareadme.com/) for this template.

## Suggestions for a good README
Every project is different, so consider which of these sections apply to yours. The sections used in the template are suggestions for most open source projects. Also keep in mind that while a README can be too long and detailed, too long is better than too short. If you think your README is too long, consider utilizing another form of documentation rather than cutting out information.

## Name
Choose a self-explaining name for your project.

## Description
Let people know what your project can do specifically. Provide context and add a link to any reference visitors might be unfamiliar with. A list of Features or a Background subsection can also be added here. If there are alternatives to your project, this is a good place to list differentiating factors.

## Badges
On some READMEs, you may see small images that convey metadata, such as whether or not all the tests are passing for the project. You can use Shields to add some to your README. Many services also have instructions for adding a badge.

## Visuals
Depending on what you are making, it can be a good idea to include screenshots or even a video (you'll frequently see GIFs rather than actual videos). Tools like ttygif can help, but check out Asciinema for a more sophisticated method.

## Installation
Within a particular ecosystem, there may be a common way of installing things, such as using Yarn, NuGet, or Homebrew. However, consider the possibility that whoever is reading your README is a novice and would like more guidance. Listing specific steps helps remove ambiguity and gets people to using your project as quickly as possible. If it only runs in a specific context like a particular programming language version or operating system or has dependencies that have to be installed manually, also add a Requirements subsection.

## Usage
Use examples liberally, and show the expected output if you can. It's helpful to have inline the smallest example of usage that you can demonstrate, while providing links to more sophisticated examples if they are too long to reasonably include in the README.

## Support
Tell people where they can go to for help. It can be any combination of an issue tracker, a chat room, an email address, etc.

## Roadmap
If you have ideas for releases in the future, it is a good idea to list them in the README.

## Contributing
State if you are open to contributions and what your requirements are for accepting them.

For people who want to make changes to your project, it's helpful to have some documentation on how to get started. Perhaps there is a script that they should run or some environment variables that they need to set. Make these steps explicit. These instructions could also be useful to your future self.

You can also document commands to lint the code or run tests. These steps help to ensure high code quality and reduce the likelihood that the changes inadvertently break something. Having instructions for running tests is especially helpful if it requires external setup, such as starting a Selenium server for testing in a browser.

## Authors and acknowledgment
Show your appreciation to those who have contributed to the project.

## License
For open source projects, say how it is licensed.

## Project status
If you have run out of energy or time for your project, put a note at the top of the README saying that development has slowed down or stopped completely. Someone may choose to fork your project or volunteer to step in as a maintainer or owner, allowing your project to keep going. You can also make an explicit request for maintainers.
