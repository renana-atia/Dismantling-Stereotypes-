# Dismantling-Stereotypes-
Data and supplementary materials for the "Dismantling Stereotypes" paper.
#Processing and Analysis - Steps and Instructions for "Dismantling Stereotypes"

The first steps would be to clean the data files (and merge where needed).
All raw files appear in the "data" folder for the R project, and can be imported easily - 
either by using a command, or by choosing the
needed file from the "files" menu (under "environment"), in R. 

###First file to clean: called "PISR_01112022", and holds data of study 1. 

###Second file to clean: here we collected a snowball sample, therefore need to
merge two files: "pisr_social" and "pisr_sona". 

#NOTE: all cleaning and prepping processes are written in the same file named 
#"Cleaning - Stereotypes in 3D"

Cleaning code has all instructions built in, and detailed checks for the exclusion criteria. 

WHEN ANALYZING:
We left in the added variables from others' projects/that were there for exploratory purposes.
Therefore, here is a guide to the needed variables for this project:
1. PolOr - stands for political orientation/political ideology. 
    the variable works fro 1=extreme political right  to 7=extreme political left
    the variable was also computed to indicate three political groups:RCL,
    where 1=right, 2=center, 3=left.
    the RCL variable is used to measure simple effects within political groups 
    (second step of analysis). 
2. thermometer_A - stands for thermometer towards Arabs in general 
    (there is another thermometer- towards the individual we presented in the article). 
    Main DV.
4. SDA - stands for social distancing from Arabs. Main DV.
5. cond - the variable indicating conditions.Order of the conditions: 
    1=control
    2=attitudes
    3=behavior
    4=traits

###The appendix has more analyses, that requires computing the cond variable differently - all is in the syntax code.
