# School_District_Analysis

Challenge Analysis

The whole goal of this analysis was to find and replace the math and reading scores of 9th graders at Thomas High School with a "NaN" value and then see what the implications would be like when recreating/re-running most of our module's code.  

The challenge asked for a written summary that answers the following questions:

Task 1: Recreate the district and school summary DataFrames.

	How is the district summary affected?
	- "% Passing Math", "% Passing Reading", and "% Overall Passing" all fell by 1% in the new district summary.
	
	How is the school summary affected?
	- (*Specific to Thomas High School*) Although the "Average Math Score" and "Average Reading Score" didn't change
	drastically, the % passing math, % passing reading, and % overall passing changed a lot.  Changing the 9th grader's
	scores to NaN changed the % Passing Math from around 93% to 67%, the % Passing Reading from 97% to 70%, and the %  
	Overall Passing from 91% to 65%.

Task 2: Recalculate the high- and low-performing schools.

	How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance, relative to the
	other schools?
	- Thomas High School slipped from 2nd to 8th place in the school rankings.

Task 3: Recalculate the scores by grade, scores by school spending, scores by school size, and scores by school type.

	How does replacing the ninth-grade scores affect the following?

		a. Math and Reading Scores by Grade
		- All the math and reading scores for all grades in all schools stay the same, EXCEPT for the 9th grade math
		and reading scores at Thomas High School.  Those are now NaN because they were replaced with NaN.

		b. Scores by School Spending
		-  The % Passing Math, % Passing Reading, and % Overall Passing percentages for the $630-644 Spending Range
		all decreased: (from 73% to 67%), (from 84% to 77%), and (from 63% to 56%)
 
		c. Scores by School Size
		- The % Passing Math, % Passing Reading, and % Overall Passing percentages for the Medium (1000-2000) school
		size all decreased: (from 94% to 88%), (from 97% to 91%), and (from 91% to 85%)

		d. Scores by School Type
		- The % Passing Math, % Passing Reading, and % Overall Passing percentages for the Charter School Type all
		decreased: (from 94% to 90%), (from 97% to 93%), and (from 90% to 87%)
