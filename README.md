2.NUMBERS
# Function to calculate speed in meters per second
def calculate_speed(distance, time_in_minutes):
    time_in_seconds = time_in_minutes * 60
    speed = distance / time_in_seconds
    return int(speed)  # Return the speed without any decimal points

# Calculate the speed
distance = 490
time_in_minutes = 7
speed_in_mps = calculate_speed(distance, time_in_minutes)
print("Speed in meters per second:", speed_in_mps)

