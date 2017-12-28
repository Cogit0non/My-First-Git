# My-First-Git

print 'This script will ask your name in 5 Seconds...'
x = 5
while x > 0 :
    print x
    x = x - 1 
print 'Coutdown complete!\n'

name = raw_input('What is your name?\n')
print 'Welcome',name

print 'To calculate your total pay, Please enter worked hours below'
hours = raw_input('Hours:')
hours = float(hours)
print "Now enter your rate"
rate = raw_input('rate:')
rate = float(rate)
print 'Your Rate will now be calculated:\n'
print hours * rate 

temp = raw_input('Enter the current temperature in Farenheit\n')
try: 
    temp = float(temp)
except : 
    print 'please enter a number'
cel = (temp - 32) * 5.0 / 9.0 
cel = float(cel)
print 'the temperature in celcius is:' 
print cel
	
if cel > 30: print 'Its hot outside!' 
elif cel > 0: print 'Seems Reasonable'
else : print 'its cold outside!'
