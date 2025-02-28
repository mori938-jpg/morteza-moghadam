# morteza-moghadam
برنامه نویسی پیشرفته: تمرین شماره یک برسی یک سال کبیسه است یا خیر؟#
def is_leap_year(year):
    """determines if a year is a leap year using logical operators ."""
    return(year % 4 == 0 and year % 100 != 0) or (year % 400 == 0)
year = int(input("Please enter a year: "))
if is_leap_year(year):
   print(f"{year} is a leap year")
else:
   print(f"{year} is not a leap year")
