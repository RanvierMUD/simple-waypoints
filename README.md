Basic waypoint fast travel system. There are two commands, `waypoint` which let's a player register a room configured as a wayshrine to his waypoint list. The command also lets the player set their preferred home point, which will be used for the `recall` command.

To make a room a waypoint simply configure on the room

```yaml
  behaviors:
    waypoint: true
```
