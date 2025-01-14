# Events

## Subscribing to Events
To stay updated on specific events, such as location changes, you can subscribe to receive regular updates from the server.

Some Events will also be send to the Client even if they are not subscribed.

Example: Subscribing to Location Updates
To subscribe to location updates, send a command to the server in the following format:
<code-block lang="json">
{
    "subscribe": "pos"
}
</code-block>

Once subscribed, the WebSocket server will periodically send you updates about the location. This ensures you always have the latest information at regular intervals.