---
Library
---
is_restricted(day,time)
is_restricted(day)
bad_weather(day)
bad_weather(day,time)
bad_weather() // implies now()


---
API
---

Location
---
* Get, Update, Add, Delete

Schedules
---
* GetAll, UpdateOne, AddOne, DeleteOne
* GetAllByDay

Valves
---
* GetAll, UpdateOne, (AddOne, DeleteOne) <- these are private

Configs
-------
Access Point
Soak and Cycle
Water Restriction Rules
Alert Settings
    * SMTP
    * SMS

network.username
network.password
network.ssid
