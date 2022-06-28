

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->

StaRMAP (Staggered grid Radiation Moment Approximation) is a simple method to solve spherical harmonics moment systems, 
such as the the time-dependent PN and SPN equations, of radiative transfer. The approach works for arbitrary moment order N, 
making use of the specific coupling between the moments in the PN equations and 1D to 3D spatial geometries. The method allows for an efficient implementation in Matlab.

# Gallery of Examples 

Numerical convergence analysis using manufactured solution in 2D. 

<img src="profile/images/fig_2d_ex_mms.jpg" alt="2D MMS Example" width="90%" align="center"/>

Temporal evolution of discrete L2 norm of numerical solution in 2D.

<img src="profile/images/fig_2d_ex_l2norm.jpg" alt="2D L2 Norm Example" width="90%" align="center"/>

2D Checkerboard test case with various momnet orders (P<sub>3</sub>, P<sub>5</sub>, P<sub>15</sub>, P<sub>39</sub>)

<img src="profile/images/fig_2d_ex_lattice_p03.jpg" alt="2D Checkerboard Example P3" width="49%" align="center"/>  <img src="profile/images/fig_2d_ex_lattice_p05.jpg" alt="2D Checkerboard Example P5" width="49%" align="center"/>  

<img src="profile/images/fig_2d_ex_lattice_p15.jpg" alt="2D Checkerboard Example P15" width="49%" align="center"/>  <img src="profile/images/fig_2d_ex_lattice_p39.jpg" alt="2D Checkerboard Example P39" width="49%" align="center"/> 

3D Lattice test case with P<sub>7</sub>.

<img src="profile/images/lattice3d_p7.jpg" alt="3D Lattice Test" width="90%" align="center"/>

3D Point Source test case with SP<sub>39</sub>.

<img src="profile/images/pointsource_80x80_sp39.jpg" alt="Point Source Test" width="90%" align="center"/>
