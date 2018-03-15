# Python-homework
Identify the leap year
x=int(input())
if x%400==0:
    print('%d is a leap year','x')
elif x%4==0 and x%100!=0:
    print('%d is a leap year','x')
else:
    print('%d is not a year','x')
