# Time-and-Date-Desklet
Settings for the time and date

Hello pals.

I share with you the settings of my beautiful clock.

The files are located in /home/your name/.local/share/cinnamon/desklets/TimeAndDate@nightflame


metadata.js
Transparent background can be set on/off in the line:
 "prevent-decorations": true, // true = transparente, false = background
 
 I added day of the week, num day, month, and year, because it is the format used in Mexico, for your country read the full description of the doc desklet
 "timeFormat": "%I:%M %p",
 
 stylesheet.css
 you are free to set up the styles you want 'cause it is CSS, don´t forget to install your desired font
 
 .clock-container{
	font-family: dejavu sans extralight;
	font-weight:lighter;
	color:rgb(255, 255, 255);
	text-shadow: 1px 1px 2px #000;
	padding: 4px 10px 4px 10px; 
	background: none;
}

.time-container{
}

.date-container{
}

.clock-date-label{
}
