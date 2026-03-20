# Week 03 – Live Data
DES240 Making Journal
This week I learned how to use the terminal to get data from the internet. I did not use a browser. I used simple commands to request data and see the result in text form.
I used the Terminal and the command `curl`. This tool sends a request to a web address and shows the response. For example, I typed: `curl ascii.live/parrot`. 

![alt text](../assets/week-03/Screenshot%202026-03-20%20at%203.37.24 PM.png)

The terminal showed a moving animation made from text. The animation kept updating. I understood that the computer was receiving data from a server in real time.
I also tried other commands: `curl ascii.live/forrest` and `curl ascii.live/earth`.
These commands showed different live streams. The output kept changing. I saw that data can move and update without a visual interface.

![alt text](../assets/week-03/Screenshot%202026-03-20%20at%203.36.40 PM.png)
![alt text](../assets/week-03/Screenshot%202026-03-20%20at%203.39.24 PM.png)

I then tested weather data: `curl wttr.in` and `curl wttr.in/Auckland`.
The terminal returned a full weather report. The data was in text form. I also used a shorter format: `curl "wttr.in/Auckland?format=3"`.

![alt text](../assets/week-03/Screenshot%202026-03-21%20at%209.31.33 AM.png)

This version was easier to read. I learned that I can control the output format by changing the URL.
I also tested a dictionary API: `curl https://api.dictionaryapi.dev/api/v2/entries/en/design`.
The terminal returned JSON data. The structure looked complex. I understood that this format is for programs, not for people. Code can read this data and use it.

I learned that data on the internet can be accessed directly. I saw that websites are only one way to show data. The terminal shows the raw data without design. I think this is useful for creative work. I can use this method in future projects to build interactive visuals with live data.