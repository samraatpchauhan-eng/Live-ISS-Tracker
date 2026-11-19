## Live-ISS-Tracker
Live ISS Tracker is a web app you can use to pinpoint the exact location of the International Space Station, at any given time. It features a minimal, sci-fi inspired interface, and can be run on most modern browsers.

# HOW THIS WAS MADE
Live ISSTracker was made entirely from scratch, utilizing HTML, CSS, and some JavaScript logic to build this.


# API's Used
Core telemetry / Backend positioning logic: [wheretheiss.at](wheretheiss.at)
    
    I mainly used this for calling the location (lat and lon), altitude, and velocity of the iss every 2.5ms. This API also helped with computing the user's GPS location with the ISS's location to predict the next overhead pass based on the user

ISS Crew API: [corquaid.github.io/.../people-in-space.json](corquaid.github.io/.../people-in-space.json)

    This static JSON file contains a list of the name and details of each person currently on the ISS, or bound to be on it in the near future. I called mainly, the names, countries of origin and role on the ISS to feed back into an output the user can see, similar to the telemetry data above.








