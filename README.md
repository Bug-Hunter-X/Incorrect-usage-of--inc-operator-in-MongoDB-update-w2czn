# Incorrect $inc operator usage in MongoDB
This repository demonstrates an uncommon error when using the `$inc` operator in MongoDB update queries.  The error arises from using a string value instead of a numerical value for the increment. 

## Bug Description:
The provided JavaScript code shows an incorrect usage of the `$inc` operator which leads to a failed update. This is because the increment value should be a number, not a string.