# PulseWatch

Aimed at the elderly and those with volatile ailments, **PulseWatch** is an Android companion for the [Microsoft Band](https://www.microsoft.com/microsoft-band/) which keeps track of the Band wearer's heart rate, in real-time. If the wearer's heart rate falls outside of the user-defined bounds, the app immediately sends a text message to an emergency list of contacts (defined by the user). The message will include the wearer's name, their heart rate at that moment, and their precise geolocation, with a Google Maps link. 

Once the wearer installs PulseWatch and syncs it with the Microsoft Band, all they need to do is hit the "Start" button on the app's landing page. Once that is done, the app is now monitoring the wearer's heart rate in real-time.

**Placed in the Top 10 at [UofTHacks](https://uofthacks.com/)**.

### Built By
- Myself ([atheed](https://github.com/atheed))
- [rahulch95](https://github.com/rahulch95)
- [cheerios2787](https://github.com/cheerios2787)

### Software
- Android SDK
- Java
- [Flask](http://flask.pocoo.org/) (for the text-messaging server)
- [Twilio](https://www.twilio.com/) API (for text-messaging)

## UI
Below are two images of PulseWatch's UI. The first shows the landing page, with a wearer's heart rate already being monitored. The second shows the settings page, which allows the user to add emergency contacts, and define the wearer's name and the "recommended" heart rate bounds. 

### Landing Page
<img src="/img/main.jpg" width="225px" height="400px"/>

### Settings Page
<img src="/img/settings.jpg" width="225px" height="400px"/>