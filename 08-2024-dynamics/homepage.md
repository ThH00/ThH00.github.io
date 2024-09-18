# MECH 230 Dynamics - Section 2


Lecture: MW 2:00-3:15 pm in Bechtel 211\
Discussion: M 3:30-4:45 pm in Bechtel 211 starting Monday September 2\
Office Hours: M 10:30-11:30am, T 2:00-3:00pm, Th 10:30-11:30am in Bechtel 532

| Week | Date | Topic & Chapter in Primer | Topic from MKB | Homework | Suggested Problems |
| ---- | ------- |-------------------------- | ------- |-------- | ------- |
| 1 | Aug 26 | A. Preliminary on Vectors and Calculus & Matlab <br> 1. Single Particle: Cartesian Coordinates | 1/1-1/7, 2/2, 2/4, 3/4 |  | [Set 0](sets/Set00.pdf)<br>[Set 1](sets/Set01.pdf) |
| 1 | Aug 28 | 1. Single Particle: Cartesian Coordinates (cont.) | 1/1-1/7, 2/2, 2/4, 3/4 | [HW01](HW/HW01.pdf) due Sep 4 | [Set 2](sets/Set02.pdf) |
| 2 | Sep 2 | 2. Single Particle: Polar Coordinates | 2/6,3/5 |  | [Set 3](sets/Set03.pdf) |
| 2 | Sep 4 | 2. Single Particle: Polar Coordinates | 2/6,3/5 | [HW02](HW/HW02.pdf) due Sep 11 | [Set 4](sets/Set04.pdf) |
| 3 | Sep 9 | 3. Single Particle: Serret-Frenet Triads | 2/5, 2/7, 3/5 |  | [Set 5](sets/Set05.pdf) |
| 3 | Sep 11 | 3. Single Particle: Serret-Frenet Triads | 2/5, 2/7, 3/5 | [HW03](HW/HW03.pdf) due Sep 18 | [Set 6](sets/Set06.pdf) |
| 4 | Sep 18[^1] | 4. Single Particle: Further Kinetics | 3/5 | [HW04](HW/HW04.pdf) due Sep 25 | [Set 7](sets/Set07.pdf) |
| 5 | Sep 23 & 25 | 5. Single Particle: Work and Energy | 3/6-3/7 | |  |
| | Saturday Sep 28 | Midterm 1 |
| 6 | Sep 30 & Oct 2 | 6.1-6.2 Linear Momenta and Angular Momenta | 3/9-3/10 |  |  |
| 7 | Oct 7 & 10 | 6.3-6.5 Collisions of Particles | 3/12 |  |  |
| 8 | Oct 14 & 16 | 7. Systems of Particles | 4/1-4/5 |  |  |
| 9 | Oct 21 & 23 | 8. Kinematics of Rigid Bodies | 5/1-5/4 |  |  |
| 10 | Oct 28 & 30 | 8. Kinematics of Rigid Bodies | 5/5-5/7 |  |  |
| | Saturday Nov 2 | Midterm 2
| 11 | Nov 4 & 6 | 9. Planar Dynamics of Rigid Bodies | 6/1-6/3, Apps A & B |  |  |
| 12 | Nov 11 & 13 | 9. Planar Dynamics of Rigid Bodies | 6/4 |  |  |
| 13 | Nov 18 & 20 | 9. Planar Dynamics of Rigid Bodies | 6/5-6/6 |  |  |
| 14 | Nov 25 & 27 | 10. Systems of Rigid Bodies | 6/8 |  |  |

[^1]: September 16 is a holiday.

## Announcements

### Wednesday September 18,2024

<span style="color:red">

Since we could not meet in class this week, here are a few directives to help get us back on track before Midterm 1.

-	The following formula [sheet](Midterm_1_Formulas.pdf) posted on the class website will be included with your Midterm 1 packet.

-	HW3 which was originally due today Wednesday September 18 will become due on Wednesday September 25.

-	HW4 which was originally due Wednesday September 25 will become due on Wednesday October 2. Although I highly encourage you to complete this homework before the Midterm because it was originally meant as preparation for it as it does not include any coding portion.

-	I will be positing video solutions to some problem set problems today on my Youtube channel. I will provide links to these videos on the class website as they become ready.

-	My office hours tomorrow will be from 1-3:30pm. I will not have office hours in the morning. If you need to come to office hours, but cannot make it in this time interval, please let me know.

-	Feel free to email me today is you have any sticking questions about the lectures or problem sets. I will set some time aside in the late afternoon to answer your emails.

</span>

### Syllabus
Syllabus: Please read the complete [syllabus](MECH230-Syllabus-Sec2.pdf) carefully.

### Downloading Matlab
Please visit [https://matlab.mathworks.com/](https://matlab.mathworks.com/), and select sign in from the to right corner of the page, please sign in with your AUBnet account, after signing in you will find MATLAB button on the top of the page, click on MATLAB and select install MATLAB, will redirect you to another page, please click on download for windows, and save the file, after download has completed, please start the installation, will ask you to sign in again, and accept the license agreement, select the license and click next, click next on the location of the installation, please select needed modules to install and click next, pleas check add shortcut to desktop, and uncheck improve MATLAB,, click next and then click begin install.

### Units
Before completing the recommended problems, please read this [note on units](notes/Note_on_Units.pdf).

### Active Learning
Check out these two excellent videos of Professor Noel Perkins from the Univesity of Michigan at Ann Arbor explaining the active learning techniques he uses to teach dynamics! [Part 1](https://www.youtube.com/watch?v=wHEys-JHeb8), [Part 2](https://www.youtube.com/watch?v=96j69u4v-wE). We will using these techniques ourselves.

## Agenda

### Lecture 1 - Aug 26
- Dynamics: An overview.
- Review of vector geometry (dot product, cross product, magnitude, projections, Cartesian coordinates)
- Basic particle kinematics concepts (position vector, velocity, acceleration)
- Rectilinear motion (given acceleration as function of time, speed, or position)

### Lecture 2 - Aug 28
- Rectilinear motion example, MKB 2/28 from Set 1.
- Arc-length.
- Particle kinetics: BoLM and action-reaction.
- Four steps to problem solving using the balance of linear momentum (BoLM, a.k.a. Newton's second law or Euler's first law).
- [Example](notes/question_cross_product.pdf): Position, Velocity, Acceleration, and Cross Product

### Lecture 3 - Sep 2
- Cylindrical polar coordinate system.

### Lecture 4 - Sep 4
- Explaining the components of the acceleration vector.
- Gravitational force model.
- Constrained motion.

### Lecture 5 - Sep 9
- The Serret-Frenet basis.

### Lecture 6 - Sep 11
- See this [video](https://www.youtube.com/watch?v=0ACqRREH180).
- The Serret-Frenet basis cont. (curvature of a plane curve, the S-F relations, time permitting, example Set 5, 03/043)

### Lecture 7 - Sep 18
- Spring force with examples from Set 6.
- Friction force with examples from Set 7.


