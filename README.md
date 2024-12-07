# MongoDB $inc Operator Error

This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations.  The `$inc` operator is designed to increment a numeric field by a specified value. However, if a string value is provided as the increment, it won't increment correctly and could potentially lead to unexpected data corruption or inconsistencies. 

The `bug.js` file shows the incorrect usage, while `bugSolution.js` provides the corrected implementation.  Read the code comments for a detailed explanation.