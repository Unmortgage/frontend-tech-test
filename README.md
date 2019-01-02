# `Frontend Technical Test`

Thanks for taking part in our technical exercise! Please go through this README carefully before starting.

There is no strict time limit for the exercise but we recommend that you spend no more than a few hours working on it. Also, **You do not need to complete all the requirements** if you are pushed for time, however your solution should give us enough code to get a clear understanding of how you normally approach and solve technical problems. Again, we're not necessarily looking for a complete piece of work, just an insight into **how** you work.

## Brief

We would like you to implement a simple form which, once submitted, retrieves some data from an API (although for this exercise it will be from a JSON provided) and displays some markers on a map. Please see the mockup in the link below to get a better understanding of the brief:

https://storage.googleapis.com/unmortgage-static/map-form.png

Please note that this mock up is just for reference; your solution does not have to look exactly like this.

The basic user journey for this feature should be:

1. User enters their income
2. User enters their deposit
3. User clicks on the "Find your next home" button
4. Markers appear on the map

The data for the map markers can be found in the repo `assets/data.json`.

## Requirements

As we're using React & Redux for our frontend, please complete this task using React & Redux (Redux is definitely overkill for such a small exercise, but again, this is just to get a better understanding of your skills).

Other requirements:
* Styling: please **do not** use an existing component library (such as MaterialUI), as we'd like to see how you would normally approach styling and building a custom component from scratch.
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
* For this exercise, the custom map markers seen in the mock up are not necessary; simply displaying the default map marker will do.
* Testing: please try and include tests for your code.

## Finishing up

When you have finished working on the task, please compress and upload the file online to Google Drive or similar and send us a link.

Please add (either in a text file with the source code or in an email):
* Instructions on how to get your source code running.
* An explanation for your approach/design decisions.
* What you would like to add if you had more time.
* Any improvements you would make to your code.

**Thanks for your time and good luck!**





