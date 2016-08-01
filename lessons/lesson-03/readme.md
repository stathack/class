---
title: Statistics Fundamentals
duration: "1:45"
creator:
    name: Chris Connell
    city: ATX
---

# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Experimental Design and Pandas
DS | Lesson 3

### LEARNING OBJECTIVES
*After this lesson, you will be able to:*

- Use NumPy and Pandas libraries to analyze datasets using basic summary statistics: mean, median, mode, max, min, quartile, inter-quartile range, variance, standard deviation, and correlation
- Create data visualizations - including: line graphs, box plots, and histograms- to discern characteristics and trends in a dataset
- Identify a normal distribution within a dataset using summary statistics and visualization
- ID variable types and complete dummy coding by hand


### STUDENT PRE-WORK
*Before this lesson, you should already be able to:*

- Create and open an iPython Notebook
- Have completed all of the python pre-work

### INSTRUCTOR PREP
*Before this lesson, instructors will need to:*

- Review [project feedback guidelines](../../projects/project-feedback.md)
- Copy and modify the [lesson slide deck](./assets/slides/slides-3.md)
- Read through datasets and starter/solution code
- Add to the "Additional Resources" section for this lesson

### LESSON GUIDE
| TIMING  | TYPE  | TOPIC  |
|:-:|---|---|
| 5 min  | [Opening](#opening)  | Lesson Objectives  |
| 10 min  | [Introduction](#introduction1)   | Laying the ground work |
| 30 min  | [Codealong](#codealong1)  | Summary statistics in Pandas |
| 10 min  | [Introduction](#introduction2)   | Is this normal? |
| 15 min  | [Demo](#demo)   | Determining the distribution of your data |
| 10 min  | [Guided Practice ](#guidedpractice2)  | Is this skewed?  |
| 20 min  | [Introduction](#introduction3) | Variable types |
| 10 min  | [Demo](#demo2)  | Classes |
| 10 min  | [Independent Practice](#practice)  | Dummy colors |
| 10 min  | [Conclusion](#conclusion)  | Review dummies and lesson objectives |
| 15 min  | [Wrap-up](#wrapup)  | Project questions and Next Project|

---
<a name="opening"></a>
## Opening (5 min)

> Instructor Note: Review Prior Lesson Content & Exit Tickets. Discuss Current Objectives.

<a name="introduction"></a>
## Intro: Laying the ground work (20 mins)

Define:

1. Mean
2. Median
3. Mode
4. Max
5. Min
6. Quartile
7. Inter-quartile Range
8. Variance
9. Standard Deviation
10. Correlation

### Mean
> Source: Content for mean, median and mode sourced from www.yti.edu/lrc/images/math_averages.doc.

The mean of a set of values is the sum of the values divided by the number of values.  It is also called the average.

	Example:  Find the mean of 19, 13, 15, 25, and 18

		19 + 13 + 15 + 25 + 18    =    90   =   18
		_______________________	    _______
			   5		                5


### Median

The median refers to the midpoint in a series of numbers.

To find the median, arrange the numbers in order from smallest to largest. If there is an odd number of values, the middle value is the median. If there is an even number of values, the average of the two middle values is the median.

	Example #1:  Find the median of 19, 29, 36, 15, and 20

		In order:  15,  19,  20,  29,  36  since there are 5 values (odd number), 20 is the median (middle number)

	Example #2:  Find the median of 67, 28, 92, 37, 81, 75

		In order:  28,  37,  67,  75,  81,  92   since there are 6 values (even number), we must average those two  middle numbers to get the median value

		Average:  (67 + 75) / 2  =    142/2    =    71 is the median value


### Mode

The mode of a set of values is the value that occurs most often. A set of values may have more than one mode or no mode.

	Example #1:  Find the mode of  15, 21, 26, 25, 21, 23, 28, 21
	     The mode is 21 since it occurs three times and the other values occur only once.

	Example #2:  Find the mode of 12, 15, 18, 26, 15, 9, 12, 27
	      The modes are 12 and 15 since both occur twice.

	Example #3:  Find the mode of 4, 8, 15, 21, 23
	      There is no mode since all the values occur the same number of times.

**Check:**

A.  For the following groups of numbers, calculate the mean, median and mode by hand:


		1. 18, 24, 17, 21, 24, 16, 29, 18		
			Mean_______
			Median______
			Mode_______
			Max _______
			Min _______

		> Answers:
			Mean = 20.875
			Median = 19.5
			Mode = 18, 24
			Max = 29
			Min = 16

		2. 75, 87, 49, 68, 75, 84, 98, 92			
			Mean_______
			Median______
			Mode_______
			Max _______
			Min _______

		> Answers:
			Mean = 78.5
			Median = 79.5
			Mode = 75
			Max = 98
			Min = 49

		3. 55, 47, 38, 66, 56, 64, 44, 39		
			Mean_______
			Median______
			Mode_______
			Max _______
			Min _______

		> Answers:
			Mean = 51.125
			Median = 51
			Mode = none
			Max = 66
			Min = 38


<a name="conclusion"></a>
## Conclusion (10 mins)

> - Review questions from dummy practice
> - Review objectives from class

<a name="wrapup"></a>
## Project questions and Next Project (15 mins)

> - Review [Project 1](../../projects/unit-projects/project-1/readme.md)
> - Introduce the next project
> - Exit tickets

***

### BEFORE NEXT CLASS
|   |   |
|---|---|
| **PROJECT 2** | [Unit Project 2](../../projects/unit-projects/project-2/readme.md)   |

### ADDITIONAL RESOURCES
- If any
