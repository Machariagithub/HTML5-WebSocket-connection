# HTML5-WebSocket-connection
JavaScript:
Get references to the button and message output elements.
Define the WebSocket server URL (ws://your-server-uri:port).
Create a new WebSocket object (const ws = new WebSocket(wsUri)).
Add event listeners:

onopen: Triggers when the connection is established, display a message and optionally send an initial message.

onmessage: Handles incoming messages from the server and displays them.

onclose: Handles connection closure, provides information about the reason.

onerror: Handles any errors during communication.

NB: Replace your-server-uri:port with the actual URL and port of your WebSocket server.

How to run the code: Save the provided HTML code as a file with a .html extension. For example, you can name it websocket-example.html.
