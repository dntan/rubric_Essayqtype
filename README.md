# Javascript Rubric for Moodle Quiz Essay qtype

This is the brief for the JS rubrics.

# Objectives
- Create a clickable JS marking rubric that we can embed in the "grader information" of a Moodle Quiz Essay question type.
  - Use Bootstrap 4 buttons
  - JS should change the appearance of the button if clicked on or off.
  - a score for each criteron should be stored in a variable.
  - a final score, the sum of all criteron scores should be calculated and automatically entered into the grade field (or presented and another button appear to confirm the grade).


# Initial Ideas
- should we use a table for the rubric structure? [BS4 Tables](https://www.w3schools.com/bootstrap4/tryit.asp?filename=trybs_table_dark_striped&stacked=h)
- use buttons for the rubric scale options.[Buttons](https://www.w3schools.com/bootstrap4/tryit.asp?filename=trybs_button_styles&stacked=h)
- include an alert at the end of the rubric that verifies that instructor is sure and have visually double checked their selections. [Alerts](https://www.w3schools.com/bootstrap4/bootstrap_alerts.asp)
- use toggleclass method from jQuery.[toggleclass](https://www.w3schools.com/jquery/tryit.asp?filename=tryjquery_dom_toggleclass)
- use a slider for the rubric marking. [slider](https://seiyria.com/bootstrap-slider/#example-6)
- ability to copy the rubric from the 'grader information' to 'feedback', so students can see it as well.
