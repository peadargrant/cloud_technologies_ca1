% Cloud Technologies CA1

**SUBJECT TO CHANGE. DO NOT START WORKING ON THIS YET.**

**Deadline:** as displayed on Moodle

**Weight:** 30%

# Aim

You will design and implement a suite of cloud services for a given case study on AWS. (As per module descriptor).

# Case study

INSERT CASE STUDY HERE.

# Deliverables

## Diagram (10%)

You will present your designed system in a GraphViz diagram.
File should be named `diagram.gv`.

## CloudFormation file (30%)

The CloudFormation file should setup all resources needed.
File should be named `template.json`.

## Setup file (20%)

The setup file should call your cloudformation file, and should be called `setup.ps1`.

## Demonstration script (20%)

Script that will show your system in operation. `demo.ps1`

## Teardown file (10%)

The teardown file `teardown.ps1` should remove all resources created, including calling `aws cloudformation delete-stack`.

## Development process (10%)

Version control as evidenced from commit history.

# Checking your submission for compliance

Your work should be checked using the `ca1_checks.ps1` file that will check your submission for compliance with the required files and naming.
Files that are mis-named or in the wrong format will receive a zero mark.

# How to submit your work

You will submit your work by means of a Git patch file.
This will encapsulate the changes you've made relative to the starting repository in a single file.

## Creating the Git patch file

INSERT GIT PATCH FILE CREATION STEPS HERE. 

## Submission to Moodle

Submit *ONLY* your git patch file named *exactly* `cloud_technologies_ca1` to Moodle.
Do not alter the filename. 

# Feedback

Summary feedback will be given on Moodle.
Verbal feedback is available on request.
