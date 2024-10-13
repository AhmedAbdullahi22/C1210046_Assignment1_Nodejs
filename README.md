# Student_name = Ahmed Abdullahi Mohamed
# ID = C1210046


# Explanation of the Function and How It Works
calculateTotalTarget(startDate, endDate, totalAnnualTarget)
# Parameters:

 startDate: A string representing the start date of the period (e.g., '2024-01-01').
 endDate: A string representing the end date of the period (e.g., '2024-03-31').
 totalAnnualTarget: A numeric value representing the total target for the year that needs to be distributed across the months.

# Functionality:

The function iterates through the specified date range, counting the number of working days (excluding Fridays) for each month.
It calculates a monthly target by dividing the total annual target evenly across the months.
Finally, it returns a JSON object summarizing the number of working days per month, the monthly targets for those months, and the total target.
Example of Usage

# console.log(calculateTotalTarget('2024-01-01', '2024-03-31', 5220));
This will output a JSON string detailing the number of days worked (excluding Fridays), the monthly targets for those months, and the total target for the specified date range.

# Assumptions or Limitations
The function assumes that the date format provided is valid and follows the ISO format (YYYY-MM-DD).
It considers only Fridays as non-working days; other holidays or non-working days are not taken into account.
The total annual target is evenly distributed across 12 months, regardless of the actual number of working days in each month.
