Library
=======
* get_water_group()
* is_restricted(day,time)
* is_restricted(day)
* bad_weather(day,time)
* bad_weather() // implies now()
* expand_for_soak_and_cycle(water_event)

API
===

Location
--------
* Get
* Update
* Add
* Delete

Schedules
---------
* GetAll
* UpdateOne
* AddOne
* DeleteOne
* GetAllByDay

Valves
------
* GetAll
* UpdateOne
* (AddOne, DeleteOne) <- these are private

Misc
----
* GetWaterGroup()

Configuration
-------------
* AccessPoint (G,P,P,D)
* Soak and Cycle ?
* Water Restriction Rules
* Alert Settings
    * SMTP
    * SMS
