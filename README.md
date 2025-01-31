# MongoDB $inc Operator Error
This repository demonstrates an incorrect usage of the MongoDB `$inc` operator and its correct implementation.
The `bug.js` file shows the erroneous code, while `bugSolution.js` provides the corrected version.
The issue arises from attempting to increment a field by a string value instead of a numeric value.  The `$inc` operator requires a numerical value for the increment. The corrected solution uses a numeric value for the increment. 