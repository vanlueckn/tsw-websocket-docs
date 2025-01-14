# Position

The Position API will give you Information about the current coordinates and speed of the player as well as the current Date and Time of the World.

## Subscribe

<code-block lang="json">
{
    "subscribe": "pos"
}
</code-block>

## Response

The server will send the Updates every 10 Seconds.

<code-block lang="json">
{
    "event":"pos",
    "lat":53.08251953125,
    "long":8.815362930297852,
    "speed_kph":253.83319091796875,
    "time_iso_8601":"2025-01-14T10-01-16Z"
}
</code-block>

<code>event</code> is the name of the event (in this case <code>pos</code>) <br/>
<code>lat, long</code> representing the coordinates of the current player <br/>
<code>speed_kph</code> speed of the player in Kilometer per Hour <br/>
<code>time_iso_8601</code> the current date/time formated as a ISO 8601 String
