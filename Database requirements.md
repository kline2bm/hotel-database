**CS374 Project Data Requirements (Bryce)**  
*Hotel Chain System*

*You are developing a system for a hotel chain. This hotel chain has hotels all over the world.*

Each individual hotel has a unique id, a name, an address and multiple phone numbers. It also has multiple features, for example: a pool, conference facilities, a spa, restaurants, etc.

Each hotel has its own set of room types: e.g., single, double, suite, penthouse, etc. A room type has a size (in sq. meters), a capacity (max \# of people), and multiple room features. Room types are specific to a single hotel – even if 2 hotels have “single” rooms – those “single” rooms are different in each hotel (differ in size, view, furnishings, etc.)

Each individual room in a hotel has a room number, a floor (even if the floor is part of the room number, because people sometimes want or do not want a specific floor) and belongs to a single room type.

The hotel chain keeps track of guests. Each guest has a unique guest id, also an identification type and number (e.g. US passport & number or driving license & number), an address and a home phone number and a mobile phone number.

A guest may hold one or more reservations for specific room type(s) in a specific hotel from a check-in to check-out date. A guest may be currently occupying one or more specific rooms. A guest is the person who pays, but their family members or friends may be occupying the room(s) that are assigned to the one guest. For security reasons, the hotel must know at least the names of all the people occupying a room, and who has occupied that room in the past.

Assume the price of a room is not fixed, but instead it depends on the day of the week and the season. There are numerous seasons, which depend on the location of the hotel, for example: winter, winter holiday, beach season, etc. Each season has a name, and a start and end date. Seasons might be unique to a hotel, but sometimes a group of hotels that are nearby one another all share the same seasons. Guests may belong to certain guest categories (e.g., VIP, government, military, etc.) that give them a discount. 

