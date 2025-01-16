# Introduction

This site provides information on how to use the TSW WebSocket API Mod as a developer.

<warning>
This library is a work in progress (WIP) and does not add any content on its own. It serves as a dependency for mod creators, providing access to game data and enabling control over certain aspects of the game through a WebSocket connection.</warning>

## Getting started

The Mod will start a Websocket Server on <code>ws://127.0.0.1:9187/api</code>.

<tip>
The port is currently hardcoded, and it is unlikely that this will change in the future.
</tip>

This mod offers the following features for TSW:

- Receiving Location / DateTime / Speed Updates

Have a look at <a href="Events.md" /> on how to subscribe to certain events.

