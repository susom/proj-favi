# Proj Favi
A custom EM for Haily Hedlin and the FAVI project.


##
1. Like ARREST, this EM uses a second project to store an array of randomization aliases for blinding.
- When a record is randomized, the EM looks out to the other project and finds the first matching, unallocated record and pulls the alias to this project, similar to how the normal REDCap Randomization works.

2. Like ARREST, after randomization, each participant is assigned a STUDY-ID which is their DAG and a numberical counter in that dag.  If there is no dag, then it is just a numerical counter.

