# Journey- #to find days between christmas and my birthday 
from datetime import date
# Example: Christmas 2023 to Birthday 2024
christmas = date(2023, 12, 25)
birthday = date(2024, 2, 3)

# Calculate the difference
delta = birthday - christmas

# Output the result
print("There are {delta.days} days between Christmas and your birthday.")
#output = 40 days
