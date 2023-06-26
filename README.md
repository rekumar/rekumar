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

I'm actively seeking Data Scientist roles to apply my expertise and passion for data science, engineering, and leadership. Let's build together!

---

# Some of my Projects
## Job Scheduling for Robotic Laboratories 

_Python, linear programming with Google OR-Tools_ 


[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://www.github.com/rekumar/roboflo)

Robots are all the rage in materials science these days, as they can work around the clock with the high precision needed for science experiments. However, many systems are not used at their full capacity -- they do one thing at a time, which is like waiting for your chicken to cook before you chop your vegetables. Roboflo is a scheduling program that uses linear optimization to schedule jobs across a bunch of different robots/tools, allowing us to use our robots to their maximum potential! 


<p align="center">
  <img src="images/roboflo/exampleschedule.jpg"  width="800px">
</p>
In the schedule above, each row corresponds to an individual hardware "actor" within the robotic lab. The bars within the plot represent when each actor is being used, and each color represents a different sample being passed from one actor to the next. Below is a gif of the robots following the schedule above.

<p align="center">
  <img src="images/roboflo/roboflo_in_action.gif"  width="400px">
</p>

---

[Quantifying How Water Damages Solar Cells](./solar_cell_humidity.md)
_Python, data visualization, data analysis, experiments_

