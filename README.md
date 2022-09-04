# New Year CountDown App Clone

The calculations are done in JavaScript. This involving setting end time to ‘January 01 {current year + 1} 00:00:00’. This can be done using new Date() function and the current year can be obtained using new Date().getFullYear(). The remaining time is obtained by subtracting the current time from the end time. The difference is formatted to the required (days hours minutes seconds) format. If the remaining time is less than 0, counter is cleared and a new timer is started for the next year (current year + 1). If it is greater than 0, the remaining time or counter is displayed and updated every second (that is, remaining time is decremented every minute). If the remaining time is 0, a message - “Happy New Year {Year} “- is displayed. This message is hidden in all other cases.
