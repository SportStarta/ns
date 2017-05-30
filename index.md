# SportStarta Namespace Vocabulary Terms

# Properties

## Domain: [Event](http://schema.org/Event) 

### sportstarta:rate

> Type: One of a [list of defined rate concepts](http://www.client1.sport.sportstarta.com/api/concepts/rate). 

The rate of the game.

### sportstarta:genre

> Type: One of a [list of defined genre concepts](http://www.client1.sport.sportstarta.com/api/concepts/genre). 

The genre of the game. 

### sportstarta:speed

> Type: One of a [list of defined speed concepts](http://www.client1.sport.sportstarta.com/api/concepts/speed). 

The speed of the game. 

### sportstarta:nature

> Type: One of a [list of defined nature concepts](http://www.client1.sport.sportstarta.com/api/concepts/nature). 

The nature of the game.

### sportstarta:surface

> Type: One of a [list of defined surface concepts](http://www.client1.sport.sportstarta.com/api/concepts/surface). 

The surface or type of court.

### sportstarta:ball

> Type: One of a [list of defined ball concepts](http://www.client1.sport.sportstarta.com/api/concepts/ball). 

The ball type.

### sportstarta:partershipProgramme

> Type: Boolean

Whether the game leader is part of the SportStarta Partership Programme.

### sportstarta:minimumAttendeeCapacity

> Type: Integer

Minimum number of players required to start the game

### sportstarta:attendeesNeeded

> Type: Integer

Number of players remaining who must join before the game can start


# Enumeration members

## Domain: [EventStatusType](http://schema.org/EventStatusType) 

### `http://data.sportstarta.com/ns/EventPending`

> Possible value of eventStatus, alongside `http://schema.org/EventScheduled` and `http://schema.org/EventCancelled`

Indicates that the game is not yet confirmed, as it is still awaiting the number of players stated in `sportstarta:attendeesNeeded`.
