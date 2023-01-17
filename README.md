# in-class-grading

This code will automatically 

## Setup

* Publish assignment
* Download response as a csv file and rename it as `<month>_<date>_in-class-source.csv`
* Download gradbook from canvas as a csv file and rename it as `<month>_<date>_in-class-target.csv`

## Step 1

After u read through all the responses, write down netids of students who should not get a point w.r.t. their response.

## Step 2
Go to `grading.py` and put those netids to the `exclude_netids` list.

## Step 3
Run `grading.py` and input month and date.
