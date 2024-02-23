## schedule_creator
# Intro
This is a schedule creator for my colleagues. We work as a team of 8 (maximum). This schedule is to provide ample coverage for our help desk, so that enough representatives are available at each time for our clients. I was unable to find a package or software that worked for the unique needs of our team, so created this with a colleague of mine. This code was written and edited by me, my colleague helped me to generate constraints and improved ideas on how to handle this task. 

We refer to taking live help desk tickets as being "on ADD" and when we are working on other duties we are "off ADD" which you will see below. This schedule accomodates for 8 of us, and works with partial days, our colleagues being out, or a "custom" shift if a specific team member has a unique schedule.

The team can input their preferred lunch and break time, however if this does not "optimize" the schedule, they will be overwritten. An "optimized" schedule means that we have enough representatives covering the help desk at each time.

# Libraries
- datetime
- numpy
- pandas
- matplotlib

# Use
In everyday use the only cell that may require an update is the below, to the users path.
![image](https://github.com/celestav/schedule_creator/assets/55772237/ab54c77e-753c-4483-a260-db23bf818fae)

The excel linked will look like the below. Users will need to update their start and end times, as well as their shift if they have a shift or time that is different than usual.

![image](https://github.com/celestav/schedule_creator/assets/55772237/937e9a28-0642-4904-8fa5-647280851b2f)


After running the script, the output with the current Schedule_1.xlsx shows the below for the week:

Everyone is in on Monday.
![image](https://github.com/celestav/schedule_creator/assets/55772237/c815f109-e5a1-42e0-b318-79c0e902fa81)

Rep2 is out on Tuesday.
![image](https://github.com/celestav/schedule_creator/assets/55772237/f527ad2d-2845-44d9-a7d5-50b963681f24)

On Wednesay, Rep4 has a custom schedule.
![image](https://github.com/celestav/schedule_creator/assets/55772237/4971ef4a-5265-4ab2-b737-62aee2db4971)

Rep 5 has a partial day on Thursday, and Rep2 is out.
![image](https://github.com/celestav/schedule_creator/assets/55772237/a64c84c3-3efc-44f2-ad84-d389fcd0e5a8)

Rep3, Rep6, and Rep4 are out on Friday.
![image](https://github.com/celestav/schedule_creator/assets/55772237/8382c102-1cbe-4855-9202-4c0afd2c7e7f)
