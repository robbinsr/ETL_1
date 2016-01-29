# ETL EXAMPLE #

You are reading the `README.md` file in the `ETL_Example_Step_01` repository for Russ Robbins. This README.md file has two purposes:

 - To introduce you to this extended example.
 - To indicate the inputs, processing, and outputs for this first step, (Step 0, an overview of the example.)

Introduction to the ETL Example
---

This repository provides an overview of an example extraction, transformation, load (ETL) project that can be reviewed by potential employers.

In a series of steps I will download, analyze, understand, transform, and load health data into an Oracle 12c pluggable database.

The purpose of the project, beyond providing an ETL example, is to create a non-toy longitudinal data set which can be studied easily, using regression, classification, clustering, etc. 

Steps in this ETL Example
---

 - Step 01: Overview (this repository)
 - Step 02: Study the NHIS 1994 Household data, confirm information in the data dictionary, and standardize field names
 - Step 03: Design the ETL process
 - Step 04: Perform the ETL process "by hand"
 - Step 05: Automate process through programs
 - Step 06: Assess Step 4
 - Step 07: Apply programs from Step 4 to the NHIS 1994 Person, Condition, Doctor, and Hospital Record Files.
 - Step 08: Continue with other health data that can be linked to these 1994 records and which will create a ten year data set.
 
===
Step 01 (Overview) of this ETL example is summarized below.
---

Input of ETL Example Step 01
---

The DS1: Household Record files from [the National Health Interview Survey, 1994](http://bit.ly/1ddSUOC) (NHIS 1994)as provided by the Inter-university Consortium for Political and Social Research (ICPSR) is part of the Institute for Social Research at the University of Michigan. The files can be obtained by selecting "Download All Files" link near DS1: Household Record.

Processing in ETL Example Step 01
---

 - Download NHIS 1994 files and store in `etl_example_step_01`, which is the repository you are within.
 - Write this `README.md` file.

Output of ETL Example Step 01
---

 - `06724-Codebook.pdf` in https://github.com/robbinsr/etl_example_step_01/tree/master/DS1_Household 
 - `06724-0001-Data.txt` in https://github.com/robbinsr/etl_example_step_01/tree/master/DS1_Household/DS0001


