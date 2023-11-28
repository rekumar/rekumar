<!-- <div align="center">
    <img align="center" src="https://github-readme-stats.vercel.app/api?username=rekumar&show_icons=true&count_private=true&hide_border=true" alt="rekumar's Github Stats"></img>
</div>
 -->
---

# About Me

[![Twitter](https://img.shields.io/badge/Twitter-%231DA1F2.svg?style=for-the-badge&logo=Twitter&logoColor=white)](https://twitter.com/rekumar_)
[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rekumar/)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:re.kumar@icloud.com)
[![Google Scholar](https://img.shields.io/badge/Google%20Scholar-4285F4?style=for-the-badge&logo=google-scholar&logoColor=white)](https://scholar.google.com/citations?user=nVzy5csAAAAJ&hl=en)
![Visitors](https://api.visitorbadge.io/api/visitors?path=github.com%2Frekumar%2Frekumar&labelColor=%23d9e3f0&countColor=%23697689)

Depending on who you ask, I'm the "coding guy", the "stats guy", or the "robot guy" These days I am building [self-driving laboratories](https://newscenter.lbl.gov/2023/04/17/meet-the-autonomous-lab-of-the-future/) that autonomously plan experiments, execute them with robots, then analyze the results in a closed loop. My robots have found new materials for solar cells and batteries!

A big believer in open source, I maintain code that supports automated labs across the country. These projects include [graph databases for experimental data](https://www.github.com/rekumar/labgraph), [job scheduling](https://www.github.com/rekumar/roboflo) for collaborative robots, and graph optimizers to [plan volume transfers for complex liquid handling routines](https://www.github.com/rekumar/mixsol).
---

# Some of my Projects

[ALabOS: A Framework for Automated Laboratories](https://github.com/CederGroupHub/alab_management)
ALabOS is a batteries-included open-source framework for automated laboratories. Today, this framework supports the [ALab](https://newscenter.lbl.gov/2023/04/17/meet-the-autonomous-lab-of-the-future/), a $2m platform at Lawrence Berkeley National Lab that makes battery materials. Users can implement Devices and Tasks in pure Python. ALabOS provides an API for users to submit Tasks, a scheduler to execute these Tasks across the fleet of Devices, and a dashboard to monitor and interact with ongoing Tasks. Furthermore, ALabOS provides first-class support for human-robot collaboration within Tasks! 

[Labgraph: A Graph Database for Experimental Data](https://www.github.com/rekumar/labgraph)
Labgraph is a graph database that stores experimental data in a flexible yet disciplined way that makes it easy to query and visualize. Science experiments generate a lot of data. The tricky part is that experiments change all the time as we get new equipment or develop new procedures; a typical database would need constant refactoring that gets ugly. Labgraph provides a solution to store this data for human scientists to analyze and train ML models, and for robotic labs to interact with to execute and plan experiments.  

[Roboflo: Job Scheduling for Collaborative Robots](https://www.github.com/rekumar/roboflo)
Roboflo is a scheduling program that uses linear optimization to schedule jobs across a bunch of different robots/tools, allowing us to use our robots to their maximum potential! Robots are all the rage in materials science these days, as they can work around the clock with the high precision needed for science experiments. However, many systems are not used at their full capacity -- they do one thing at a time, which is like waiting for your chicken to cook before you chop your vegetables. 

[PASCAL: the Perovskite Automated Solar Cell Assembly Line](https://www.github.com/fenning-research-group/PASCAL) I built this robotic laboratory to make and test thin films. It can run in a closed loop using active learning to iteratively plan, execute, and analyze experiments. This link is to the codebase that drives this laboratory!

<p align="center">
  <img src="images/roboflo/roboflo_in_action.gif"  width="400px">
</p>

PASCAL is an automated platform for spin coating and annealing thin films onto small (>2x2 cm) substrates, aimed af increasing experimental throughput in the pursuit of designing better perovskite solar cells. Perovskite solar cells are infinitely tunable, as they can be formed with combinations of nearly half of the periodic table. With PASCAL, we aim to increase our experimental search rate by orders of magnitude, enabling a more systematic and exhaustive approach toward exploring the vast compositional space of interest for solar cell design.


[MixSol: A Graph Optimizer for Liquid Handling](https://www.github.com/rekumar/mixsol)
MixSol is a volume transfer planner that, given a set of stock solutions and a set of desired solutions, outputs a plan for how to mix them. Liquid handling robots are the workhorses of lab automation, but typically used in pretty basic ways -- linear or logarithmic dilutions to test a regular grid of mixtures. If we want an irregular spacing of specific mixtures (as often generated by machine learning algorithms that don't care about how simple the dilutions are), its much harder to plan the volume transfers to mix or dilute our stock solutions. This is especially important for robotic labs that need to plan volume transfers on the fly, like PASCAL!

<!-- 
---

[Quantifying How Water Damages Solar Cells](./solar_cell_humidity.md)
_Python, data visualization, data analysis, experiments_ -->

