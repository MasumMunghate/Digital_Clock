# Digital_Clock

The code starts by getting references to HTML elements that will display the time: hourEl, minuteEl, secondEl, and ampmEl.

The updateClock function is defined to update the displayed time.

Inside the updateClock function:

It creates a Date object called now to get the current date and time.
It extracts the hours, minutes, and seconds from the now object.
It initializes the ampm variable as "AM".
If the hour (h) is greater than 12, it subtracts 12 to convert to the 12-hour format and sets ampm to "PM".

It checks if the extracted values are single digits and, if so, adds a leading zero to format them correctly (e.g., 9 becomes "09").

It updates the HTML elements (hourEl, minuteEl, secondEl, and ampmEl) to display the current time and AM/PM.

The setTimeout function is used to call updateClock every 1000 milliseconds (1 second), ensuring that the clock updates in real-time.

The updateClock function is initially called to start the clock.
