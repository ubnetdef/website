---
date: "2018-01-29"
title: "Network Security"
navbar_active_link: "courses"

course: "Network Security"
course_number: 200
semester: "Spring"
year: 2018
difficulty: "Intermediate"

active: true

subtext: "Spring 2020 / Online / Daily Sunday - Thursday"
---

# Overview
This course exposes students to the tools and techniques used by information security professionals to analyze computer network traffic and identify suspicious and/or malicious activity within that traffic.

**Upon successful completion of the course, students will have gained real-world experience that will make them highly desirable to employers with open entry-level Security Operations positions.**

This course also exposes students to professional skills, to include: public speaking, business writing, technical writing, and teamwork.

The course is built on the premise that students learn best by actively doing, and through hands-on experience.

# Instructor
<table class="table">
	<thead>
		<tr>
			<th>Name</th>
			<th>Email</th>
			<th>Chat Username</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Chris Crawford</td>
			<td>christopher.p.crawford@gmail.com</td>
			<td>@chriscrawford</td>
		</tr>
			<tr>
			<td>Peter Gebura </td>
			<td>pngebura@buffalo.edu</td>
			<td>@petergebura</td>
		</tr>
			<tr>
			<td>Zach Tenenbaum</td>
			<td>zatenenb@buffalo.edu</td>
			<td>@zachtenenbaum</td>
		</tr>
			<tr>
			<td>Sriniketh Varma Dasarraju</td>
			<td>sriniket@buffalo.edu</td>
			<td>@srini</td>
		</tr>
	</tbody>
</table>

# Course Objectives
At a high level, each student has the following objectives to meet:

1. Understand the advantage of using the passive voice in comparison to the active voice. 
2. Read the Lockheed Martin Cyber Kill Chain paper to identify Indicators of Compromise (IoC), distinguish intrusion kill chain phases, and recommend mitigation strategies.
3. Build a 3-node network using VirtualBox (see topology below).    
4. Compile open source network defense tools (such as Zeek and Snort) to monitor legitimate network traffic over their new network.    
5. Using the knowledge and capabilities gained from the previous objectives, analyze malicious network traffic from prior network defense competition packet captures.   
6. Effectively communicate in written reports, without using the passive voice, the steps taken and results of the packet analysis (see report outline below).    
7. Present twice as a group to the Systems Security class.   
    
# Course Tasks (20% of grade)
Students will apply an Agile methodology (similar to Scrum) to accomplish the tasks assigned, utilizing Trello to track all progress throughout the semester. Students must complete the tasks in order before moving on to the next task and submit PowerPoint slides to Dropbox upon completion. Additionally, students will upload a daily screenshot to Dropbox prior to the daily meeting which highlights their progress. Students are also required to update their daily progress and active task on Trello before the daily meeting. All class communication will be conducted through the Mattermost course chat channel and students are encouraged to collaborate and ask questions in this channel. 
The course tasks consist of building a 3-node network, compiling and installing various tools, and becoming familiar with the tools. Students will construct their network using VirtualBox and Vagrant. The primary packet analysis tools utilized in class are Wireshark, Snort, Zeek (Bro), and Splunk. 
An example list of tasks to be completed is outlined [here](/content/Course_Tasks.docx) (link to list). Please note that these are tasks from a past semester and that tasks vary between semesters. 

# Course Calendar
The instructor will share the official course calendar with students as a Google Calendar during the first week of class.  Students are expected to have their own Google Calendar for this class, and will be asked to block out times that they are unavailable to meet.

Although it is subject to change, a tentative course calendar is provided in the table below:

TBD

# Grading Policies
<div class="row">
	<div class="col-md-8">
		<table class="table table-bordered">
			<thead>
				<tr>
					<td>Course Component</td>
					<td>Percentage of Final Grade</td>
				</tr>
			</thead>
			<tbody>
				<tr>
					<td>Daily Sync Meeting - Attendance</td>
					<td>10%</td>
				</tr>
				<tr>
					<td>Daily Sync Meeting - Participation</td>
					<td>35%</td>
				</tr>
				<tr>
					<td>Written Reports</td>
					<td>45%</td>
				</tr>
				<tr>
					<td>Presentations</td>
					<td>10%</td>
				</tr>
			</tbody>
		</table>
	</div>
	<div class="col-md-4">
		<table class="table table-bordered">
			<thead>
				<tr>
					<td>Final Grade (X)</td>
					<td>Final Letter Grade</td>
				</tr>
			</thead>
			<tbody>
				<tr>
					<td>X >= 90%</td>
					<td>A</td>
				</tr>
				<tr>
					<td>80% <= X < 90%</td>
					<td>B</td>
				</tr>
				<tr>
					<td>70% <= X < 80%/td>
					<td>C</td>
				</tr>
				<tr>
					<td>60% <= X < 70%</td>
					<td>D</td>
				</tr>
				<tr>
					<td>X < 60%</td>
					<td>F</td>
				</tr>
			</tbody>
		</table>
	</div>
</div>

## Daily Sync Meeting (45%)
This class is designed to be extremely hands-on and borrows some of its structure from [scrum](https://www.atlassian.com/agile/scrum).

Class meets five days a week on Google Hangouts for no more than 10 minutes, at the same time every day.  During the meeting, the instructor asks each student the following three questions:

1. What did you accomplish since the last time we met?
2. What do you plan to accomplish before our next meeting?
3. Is there anything preventing you from accomplishing your plan that I can help you with?

The meeting time is set at the beginning of the semester to a time that all students can consistently meet during the same time every day.

The instructor will maintain Daily Sync Meeting minutes, which will be shared with the class via Google Docs.

Students receive two PASS/FAIL grades for each meeting: one for attendance and one for participation.  Students earn 1 point when they PASS and 0 points when they FAIL.  Final grade for both attendance and participation is determined by the sum of all passing grades, divided by the total number of meetings.


### Daily Sync Meeting Attendance (10%)
<table class="table table-bordered">
	<thead>
		<tr>
			<td>Grade</td>
			<td>Criteria</td>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>PASS</td>
			<td>If student is present on Google Hangouts on time and remains until the end of the meeting (10 minutes maximum).</td>
		</tr>
		<tr>
			<td>FAIL</td>
			<td>If student is late to the meeting, or if they leave the meeting before it concludes.</td>
		</tr>
	</tbody>
</table>

### Daily Sync Meeting Participation (35%)
<table class="table table-bordered">
	<thead>
		<tr>
			<td>Grade</td>
			<td>Criteria</td>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>PASS</td>
			<td>If student accomplished something since the last meeting AND articulates a plan to accomplish something new by the next meeting.</td>
		</tr>
		<tr>
			<td>FAIL</td>
			<td>If student has not accomplished anything since the last meeting OR does not plan to accomplish anything by the next meeting.</td>
		</tr>
	</tbody>
</table>

## Daily Sync Meeting Vacation Days
Students get **5** vacation days, where they may skip the daily sync meeting, with no questions asked.  To use a vacation day, the student must state that they plan to use a vacation day for the following Daily Sync Meeting.

Students that do not attend the daily meeting, and have not previously stated that they had planned on taking a vacation day, will fail both participation and attendance for the day.

## Written Reports (45%)
Students are expected to develop a professional written report every week.  The report will illustrate the student’s work, in detail, and in such a way that a UBNETDEF SYSSEC student can easily understand and achieve the same results without any intervention from the author.

The report will also include an executive summary, which will professionally convey high level points about their work to a non-technical audience.

Students will be provided a template to use to develop their weekly reports.

Students will also be provided with the rubric that the instructor uses to grade each weekly report.  The rubric looks at a number of aspects of the report itself, in detail.

Of note, the following infractions will automatically result in a grade of 0% for a given weekly paper:

* The report includes one or more spelling errors.
* The report includes one or more grammatical errors.
* The executive summary is longer than one page.
* The report is submitted after the official due date.

## Presentations (10%)
Each student will deliver a 10 minute presentation to the Thursday night UBNETDEF SYSSEC class twice during the semester.

The presentation will cover, at a high level, the progress that they have made in the class to date.

The objective of these presentations is to give the student some exposure to delivering an executive level brief to a large audience.

Students will be graded by the course instructor based on input from a jury of their juniors.  Each UBNETDEF SYSSEC student in the audience will be asked to answer the following questionnaire:

* Was the presenter prepared to start on time? (Yes/No)
* Could you hear the presenter? (Yes/No)
* Did the presenter speak clearly? (Yes/No)
* Did the presenter make it easy for you to understand his topic? (Yes/No)
* Did the presenter provide materials (i.e. slides, printouts) that helped you follow along? (Yes/No)
* Did the presenter finish on time or early? (Yes/No)

Each point is decided by a majority vote.  So a student earns 1 point when 51% or more of the class responds “Yes” to one of the questions above.

The total score for the presentation is computed by the number of earned points divided by the number of possible points.

# Office Hours
Office hours are dynamic, flexible, and provided on an as-needed basis.  Students state a need to meet with the instructor during the daily sync meeting, and the instructor and student schedule a mutually agreeable time to meet on Google Hangouts.

# Course Conduct
## Academic Integrity
Students must conduct their coursework in a manner that does not violate the University at Buffalo’s Academic Integrity Policy.  Students found in violation of the [Academic Integrity Policy](http://undergrad-catalog.buffalo.edu/policies/course/integrity.html) will receive an F for the course.

## Ethics Policy
As a student in cyber security, you are learning tools and given resources that are meant to help protect yourself and others. However, these tools and resources can also be used in malicious or illegal ways. It is imperative that while you are a representative of this class, and even well after, you perform any security education or training strictly inside our internal environment or a controlled and contained environment that you have prepared for yourself. Any activity outside of our internal environment is outside of our control and protection. If you are not sure what you’re doing, it is very easy to do something illegal without even knowing you are (even something as simple as port scanning outside our internal network). If you are unsure if something is allowed or not, contact one of the instructors or mentors. **All network traffic inside our infrastructure will be monitored for malicious or suspicious activity and acted upon with severe consequences if such privileges are abused.** You are being given an opportunity to learn, please do not waste it.

## vCenter Usage
As a part of the Network Security course, you are granted elevated permissions permissions inside the vCenter environment.  Any misuse of the environment will result in the **immediate failure of the student, as well as academic dishonesty charges being filed.**

## Network Logging Disclaimer
All traffic that occurs within the vCenter environment is being **logged** for analysis purposes.  Traffic captures (pcaps) may be shared with other individuals within UBNetDef for educational purposes only. **We highly discourage logging into any personal or social networking websites on a Virtual Machine hosted in the vCenter environment.**
