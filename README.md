# homePlanner
Android aplication for home planning.

Modules:

1st realise: Google Calendar with adding/remove/edit events, Task manager, Weather, Notes, Quotes.
2nd realise: Interface to comunicate with Arduino board for getting/setting info from sensors/to motors.

1st.
Google Calendar adapter.
Allow see a fragment of calendar in day/week/mounth view.
Allow see and edit calendar events
Allow specify a color of events.

{Thinking about additional layer for handwrite}

Task manager:
Allow to create a local task.

Weather:
Adapter for comunicate with weather service about local weather.

Notes:
Simply notepad

Quotes:
Quotes will show on specified place on display, collect from txt file on internal memory.


2nd:
Comunication with arduino board (for example) VIA Bluetooth or wi-fi, for getting information from different sensors (temperature, humidity, lights etc) each will be programmed for this board. Availability to send command via interface to arudino board according some rules.  
