Five hundred twenty-five thousand, six hundred minutes
Five hundred twenty-five thousand moments so dear
Five hundred twenty-five thousand, six hundred minutes
How do you measure, measure a year?

— “Seasons of Love,” Rent


Assuming there are 365 days in a year, there are 
 minutes in that same year (because there are 24 hours in a day and 60 minutes in an hour). But how many minutes are there in two or more years? Well, it depends on how many of those leap years with 366 days, per the Gregorian calendar, as some could have 
 additional minutes. In fact, how many minutes has it been since you were born? Well, that, too, depends on how many leap years there have been since! There is an algorithm for such, but let’s not reinvent that wheel. Let’s use a library instead. Fortunately, Python has a datetime module with a class called date that can help, per docs.python.org/3/library/datetime.html#date-objects.

This program prompts the user for their date of birth in YYYY-MM-DD format and then prints how old they are in minutes, rounded to the nearest integer, using English words instead of numerals, just like the song from Rent, without any and between words. Since a user might not know when they were born, assume, for simplicity, that the user was born at midnight (i.e., 00:00:00) on that date. It assumes that the current time is also midnight. In other words, even if the user runs the program at noon, assume that it’s midnight, on the same date.
