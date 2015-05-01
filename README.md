# Calendar 
This is Calendar Plugin that lets you manage events. It allows to manage custom events.
#Installation 
Calendar is compatible with Cordova Plugman, compatible with PhoneGap 3.0 CLI, here's how it works with the CLI:
```
phonegap local plugin add https://github.com/Anuj-Harshe/Calendar
```
or
```
cordova plugin add https://github.com/Anuj-Harshe/Calendar
```
#Example
```
  var startDate = new Date("May 1, 2015 2:00:00");
  var endDate = new Date("May 1, 2015 2:00:00");
  var notes = "Calendar Plugin for Android";
  var title = "Anuj Harshe Calendar Plugin";
  var location = "Nagpur, India";
  var success = function() { alert("Success"); };
  var error = function(message) { alert("Error :- "+ message); };
  calendar.createEvent(title, location, notes, startDate, endDate, success, error);
```
