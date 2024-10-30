# Hello-world
seconds_in_a_minute = 60
minutes_in_an_hour = 60

# Calculate seconds per hour
seconds_per_hour = seconds_in_a_minute * minutes_in_an_hour

# Calculate seconds per day and save it in a variable called seconds_per_day
hours_in_a_day = 24
seconds_per_day = seconds_per_hour * hours_in_a_day

# Divide seconds_per_day by seconds_per_hour using integer division
result_integer_division = seconds_per_day // seconds_per_hour

# Divide seconds_per_day by seconds_per_hour using floating-point division
result_floating_point_division = seconds_per_day / seconds_per_hour

print(f"Result using integer division: {result_integer_division}")
print(f"Result using floating-point division: {result_floating_point_division}")

# Check if the results agree aside from the final .0
agree = result_integer_division == int(result_floating_point_division)
print(f"Do the results agree aside from the final .0? {agree}")

