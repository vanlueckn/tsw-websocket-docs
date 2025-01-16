# Events

## Subscribing to Events
To keep track of specific events, like location changes, you can subscribe to receive regular updates from the server.

<tip>
Please note that some events (like <a href="System-Events.md"/>) may be sent to the client automatically, even without a subscription.
</tip>

Example: Subscribing to Location Updates
To subscribe to location updates, simply send the following command to the server:

<code-block lang="json">
{
    "subscribe": "pos",
    "interval": 1000, //optional, default value is 10000 ms
}
</code-block>
Once subscribed, the WebSocket server will periodically send you updates about the location. This ensures you always have the latest information at regular intervals. For performance reasons interval below 1000ms will be executed every <code>1000ms</code>. If you subscribe without any given interval, the default value of <code>1000ms</code> will be used.