# System Events

System Events will inform the Client about specificevents e.q. a new WebSocketClient is connected or a client subscribed to a event like
<a href="Location.md">pos</a>

## Join Message

This message will be sent if a new WebSocket Client is connected to the server

<code-block lang="json">
{
    "event": "join_message"
}
</code-block>

## Subscribe Message

<code-block lang="json">
{
    "event": "subscribe_message"
}
</code-block>

## Unsubscribe Message

<code-block lang="json">
{
    "event": "unsubscribe_message"
}
</code-block>