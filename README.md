# `Frontend Technical Test`

Thanks for taking part in our technical exercise! Please go through this README carefully before starting.

Take as long as you need (or however long you think is reasonable). You don't need to complete all the requirements if
you are pushed for time, however your solution should give us enough code to get a clear understanding of how you normally approach
and solve technical problems.

Please do not make your solution publicly available, just compress this folder and send it back to us.

## Brief

We would like you to implement a simple form which retrieves data from an endpoint and displays this data on a map. Please see
the mockup in the link below to get a better understanding of the brief:

https://storage.googleapis.com/unmortgage-static/map-form.png

Please note that this mockup is just for reference; your solution does not have to look exactly like this.

The basic user journey for this feature should be:

1. User enters their income
2. User enters their deposit
3. User clicks on the "Find your next home" button
4. Markers appear on the map

The data for the map markers can be found in the repo `assets/data.json`.

## Requirements

As we're using React for our frontend, please complete this task using React. Other than that, you're free to use any
other libraries of your choice. 

Other acceptance criteria:
* Form validation:
    * A green tick within the input if the field is valid (assets supplied in this repo `assets/tick.svg`).
    * A red cross within the input if the field is invalid (assets supplied in this repo `assets/cross.svg`).
    * Both fields should accept numbers only.
    * No empty or 0 values should be allowed.
    * Income must be £20,000 or over.
    * Deposit must be £10,000 or over.
    * The user should not be able to submit the form if invalid.
* Number formatting
    * Numbers must be displayed with thousand separators i.e. `30000` becomes `30,000`.
* For this exercise, custom map markers are not necessary; simply displaying the default map marker will do.

## Nice to haves

* Components should be built with reusability in mind.
* The solution should be compatible with the latest versions of Chrome, Firefox, Safari and Edge.
* The solution should be compatible with IE11.
* An approach which would allow for adding tooltips to the markers which will show the city name (as seen in the mock up)
* An approach which would allow for adding a click event to the markers, which allows the city ID to be used (for example, opening
a 'city' modal based on the ID).


## Finishing up

We understand that you may not have time to complete all the requirements in this exercise.
Whether you fully the complete the task or not, please add (either in a text file with the source code or in an email):
* Instructions on how to get your source code running.
* An explanation for your approach/design decisions.
* What you would like to add if you had more time.
* Any improvements you would make to your code.

Good luck and have fun!





