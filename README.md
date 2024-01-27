# survey_matching_tool
A tool to match mentors and mentees based on a survey likeness score

This program is designed to loop through two directories containing survey results saved in .txt files.
The format of the .txt files is as follows:
  name: "mentor/mentee name"
  question 1: #
  question 2: #
  ...
  question 10: #

The surveys that this program has been designed to work with are still being written, the program
will be updated to work with whatever format they are exported in (probably .csv), and to reflect
any necessary changes to the math (i.e. if different questions will be weighted differently, if some
quesitons are binary in nature etc.)

The program is also currently being updated to use SQLite to store the raw data and pairings+
likeness scores, so that it can be queried later or easily exported to a friendly format
for the user.
