# lunar-solar-birthday-calendar-generation_new
Generate lunar or solar birthday calendar subscription file that can be added in Google Calendar or others.

---
* This script generates an iCalendar file (.ics) containing birthday events for the next 100 years for any amount of people you want to add. Import the file into the calendar to subscribe. You can re-run the script and import it into the same calendar to update the birthdays of new people.
* This script can realize the conversion between lunar and solar dates, that is, you can input the solar birthday and get the lunar birthday subscription in the .ics file, or vice versa.
* This code recognizes leap months in lunar birthdays, so an additional input option is added when entering the lunar birthday to determine whether it is a leap month.

Required Libraries: ics, lunarcalendar. You can install them using 
```
pip install ics lunarcalendar
```

