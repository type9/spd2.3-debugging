# Debug Log

**Explain how you used the the techniques covered (Trace Forward, Trace Backward, Divide & Conquer) to uncover the bugs in each exercise. Be specific!**

In your explanations, you may want to answer:

- What is the expected vs. actual output?
- If there is a stack trace, what useful information does it contain?
- Which technique did you use, on which line numbers?
- What assumptions did you have about each line of code, and which ones were proven to be wrong?

_Example: I noticed that the program should show pizza orders once a new order is made, and that it wasn't showing any. So, I used the trace forward technique starting on line 13. I discovered the bug on line 27 was caused by a typo of 'pzza' instead of 'pizza'._

_Then I noticed another bug ..._

## Exercise 1

- attempt to enter in pizza to get an error thrown. error occurs on line 79 on submission of pizza toppings.
- line 79 fixed kwargs "toppings" to "topping_type"
- line 84 fixed redirect to url_for("home") as "/" in invalid and is the raw url
- see proper posting of orders into DB but no display.
- line 82 was missing db commit
- error in committing to db because of null values
 - line 62 modified names to properly take values from form so they're not null
 - testing fulfillment works. going to give this a naive it's fixed stamp.

## Exercise 2

[[Your answer goes here!]]

## Exercise 3

[[Your answer goes here!]]
