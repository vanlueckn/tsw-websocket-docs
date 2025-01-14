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
    "subscribe": "pos"
}
</code-block>
Once subscribed, the WebSocket server will periodically send you updates about the location. This ensures you always have the latest information at regular intervals.