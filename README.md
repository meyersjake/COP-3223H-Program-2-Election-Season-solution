# COP-3223H-Program-2-Election-Season-solution

Download Here: [COP 3223H Program #2: Election Season solution](https://jarviscodinghub.com/assignment/program-2-election-season-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

Problem A: How many more votes? (votes_a.py/votes_a.cpp)
In the upcoming election, candidate A is behind candidate B. In order to win the election,
candidate A needs to get some number of citizens who are allowed to vote (but who have not) to
vote for her. Write a program that asks the user for the number of votes candidate A is projected
to receive at this point in time and the number of votes that candidate B is projected to receive at
this point in time and prints out how many new citizens must be recruited to vote for candidate A
to allow her to win the election.
Input Specification
Both input values (current votes for candidate A and current votes for candidate B) will be
positive integers less than 30,000,000 and the first input value will be strictly less than the
second. (Thus, it’s guaranteed that candidate A will have fewer votes than candidate B.)
Output Specification
Output a single line of the format:
Candidate A needs X more votes to win the election.
Sample Program Run #1
How many votes does candidate A currently have?
123456
How many votes does candidate B currently have?
130000
Candidate A needs 6545 more votes to win the election.
Sample Program Run #2
How many votes does candidate A currently have?
8610213
How many votes does candidate B currently have?
8610214
Candidate A needs 2 more votes to win the election.
Problem B: How many minds must be changed? (votes_b.c)
In the upcoming election, candidate A is behind candidate B. Candidate A’s staff has decided that
they will be able to convince some people who are already intending on voting to simply change
their minds and switch their vote from candidate B to candidate A. Write a program that asks the
user for the number of votes candidate A is projected to receive at this point in time and the
number of votes that candidate B is projected to receive at this point in time and prints out how
many of the latter group must be convinced to switch their vote to candidate A in order for
candidate A to win.
Input Specification
Both input values (current votes for candidate A and current votes for candidate B) will be
positive integers less than 30,000,000 and the first input value will be strictly less than the
second. (Thus, it’s guaranteed that candidate A will have fewer votes than candidate B.)
Output Specification
Output a single line of the format:
Candidate A needs X people to switch their vote.
Sample Program Run #1
How many votes does candidate A currently have?
123456
How many votes does candidate B currently have?
130000
Candidate A needs 3273 people to switch their vote.
Sample Program Run #2
How many votes does candidate A currently have?
8610213
How many votes does candidate B currently have?
8610214
Candidate A needs 1 people to switch their vote.
Problem C: Registering Voters (votes_c.py/votes_c.cpp)
In the upcoming election, candidate A is behind candidate B. Candidate A’s staff has decided that
the best strategy will be encouraging those who aren’t registered to do so and vote. Their research
has shown that some percentage of the newly registered voters (greater than 50) will vote for
candidate A over candidate B. Write a program that will calculate the number of people the
campaign must register such that candidate A is projected to win by at least 1,000 votes. (Note:
we are building in a margin of error here just in case some portion of the projections are slightly
off.)
Input Specification
The first two input values, the number of votes currently for candidate A and the number of votes
currently for candidate B are both going to be positive integers less than or equal to 30,000,000,
with the first value less than the second. The third input value, the percentage of new voters who
vote for candidate A over candidate B is going to be an integer in between 51 and 100, inclusive.
Output Specification
Output a single line of the format:
Candidate A needs X new voters to register.
Your answer can be ±1 of the actual answer and will be counted as correct.
Sample Program Run #1
How many votes does candidate A currently have?
123456
How many votes does candidate B currently have?
130000
What percentage of new voters will vote for candidate A?
60
Candidate A needs 37720 new voters to register.
Sample Program Run #2
How many votes does candidate A currently have?
8610213
How many votes does candidate B currently have?
8610214
What percentage of new voters will vote for candidate A?
51
Candidate A needs 50050 people to switch their vote.
Problem D: Hybrid Strategy (votes_d.c)
In the upcoming election, candidate A is behind candidate B. Candidate A’s staff has decided on
a hybrid strategy that involves trying to change the mind of current voters and encouraging those
who aren’t registered vote to do so and vote. Their research has shown that some percentage of
the newly registered voters (greater than 50) will vote for candidate A over candidate B, and that
some other percentage of current voters will change their minds due to the new campaign
strategy. Write a program that will calculate the number of people the campaign must register
such that candidate A is projected to win by at least 1,000 votes.
Input Specification
The first two input values, the number of votes currently for candidate A and the number of votes
currently for candidate B are both going to be positive integers less than or equal to 30,000,000,
with the first value less than the second. The third input value, the percentage of new voters who
vote for candidate A over candidate B is going to be an integer in between 51 and 100, inclusive.
The fourth input value, the percentage of current voters who will switch from candidate B to
candidate A, is going to be a positive integer.
Output Specification
Output a single line of the format:
Candidate A needs X new voters to register.
where X is the number of new voters that must be registered to ensure a victory for candidate A
of at least 1000 votes.
Sample Program Run #1
How many votes does candidate A currently have?
123456
How many votes does candidate B currently have?
130000
What percentage of new voters will vote for candidate A?
60
What percentage of current voters will switch to candidate A?
2
Candidate A needs 0 new voters to register.
Sample Program Run #2
How many votes does candidate A currently have?
8000000
How many votes does candidate B currently have?
10000000
What percentage of new voters will vote for candidate A?
55
What percentage of current voters will switch to candidate A?
3
Candidate A needs 9210000 new voters to register.
Deliverables
Four source files:
1) votes_a.py or votes_a.cpp for your solution to problem A
2) votes_b.c for your solution to problem B
3) votes_c.py or votes_c.cpp for your solution to problem C
4) votes_d.c for your solution to problem D
All files are to be submitted over WebCourses.
Restrictions
Although you may use other compilers and coding environments, your programs must run in
IDLE for the Python programs and Code::Blocks for the C/C++ programs.
Grading Details
Your programs will be graded upon the following criteria:
1) Your correctness
2) Your programming style and use of white space. Even if you have a plan and your program
works perfectly, if your programming style is poor or your use of white space is poor, you could
get 10% or 15% deducted from your grade.
Note: As mentioned in class, the input specifications are there to help you. Those are the
requirements I guarantee I’ll stick to when testing your program. You don’t need to check if
the user enters values within those parameters.

