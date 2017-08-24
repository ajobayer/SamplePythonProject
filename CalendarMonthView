import calendar
from time import localtime

print 'This python file working fine'

activities = {8: 'Sleeping',
              9: 'Commuting',
              17: 'Working',
              18: 'Commuting',
              20: 'Eating',
              22: 'Resting' }

time_now = localtime()
hour = time_now.tm_hour

for activity_time in sorted(activities.keys()):
    if hour < activity_time:
        print activities[activity_time]
        break
else:
    print 'Family time, AFK or sleeping! \n'
    
    
# Python program to display calendar of given month of the year



yy = 2017
mm = 8

# To ask month and year from the user
# yy = int(input("Enter year: "))
# mm = int(input("Enter month: "))

print 'Display calendar of month August \n'

# display the calendar
print(calendar.month(yy, mm))
