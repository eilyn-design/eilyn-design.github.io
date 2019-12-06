# rangeCalendar
Vanilla JS range calendar

## Description
A simple vanilla js code with no libraries or dependencies that renders a calendar with as many weeks/months/years based on user inputs:

  - Starting date | String | mm/dd/yyyy
  - Number of days from the starting date | Integer | From 1 to 999 (limit added just for validation testing purposes)

## Public access link to the initial solution.
http://techtest.doubledigit.com/

## Tasks
  - Allow the user to specify a Country Code using a text input.
  - Validate the Country Code (required field, accept only 2 alphabetic characters).
  - Show the selected country holidays consuming a simple JSON list.
  - If the Country Code specified by the user does not match an available JSON country file (cr/us), use default international holiday list to display holidays.
  - Differentiate today's day (when in range) using a gray background (#444) and white text (#FFF).
  - Differentiate holidays using a green background (#3d9438) and white text (#FFF).
  - Alert the holiday's name on click.

## Ground Rules
  - Your solution must be uploaded and shared in a public repository on your GitHub account since this is what we will use to review the code.
  - Use the provided ZIP file to create your first commit and start the test.
  - A link to a published working solution needs to be provided, otherwise, the exercise will not be evaluated.
  - Use whatever resources you need, except another person’s help.
  - The initial code for this calendar has been developed using Vanilla JS. You can include jQuery if you feel more comfortable, however, the use of MVC frameworks, plugins or ready-to-use code to build the calendar will not be accepted.
  - Completing this exercise fast is not important, we only care you demonstrate a fundamentally sound approach for the development of this exercise.