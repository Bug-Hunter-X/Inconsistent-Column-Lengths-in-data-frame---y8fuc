# R Bug: Inconsistent Column Lengths in data.frame()

This repository demonstrates a common error in R when creating data frames:  inconsistent column lengths.  The `bug.R` file contains code that attempts to create a data frame with columns of differing lengths. This results in an error because `data.frame()` requires all columns to have the same number of elements.

The `bugSolution.R` file provides a corrected version, showing how to handle this issue by ensuring all vectors have equal length before creating the data frame.  Several approaches are shown, offering flexibility depending on the situation.