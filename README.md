![Screenshot](https://github.com/YourUsername/YourRepo/blob/main/images/Screenshot-2025-03-16-070115.png?raw=true)

WebSocket Logger and Debugger
Description
This is an advanced WebSocket logger and debugger tool designed to capture and log all incoming and outgoing WebSocket traffic, as well as WebRTC signaling packets. It offers full flexibility for custom WebSocket command injection and includes features like

WebSocket connection management (automatic heartbeat management)
Real-time logging of WebSocket and WebRTC packets
Customizable command injection for sending arbitrary WebSocket messages
Professional, hacker-oriented interface
Features
WebSocket Traffic Logging Logs every incoming and outgoing WebSocket message, including heartbeat signals
WebRTC Signaling Logging Handles and logs WebRTC signaling packets (WebRTC-specific messages)
Custom Command Injection Send arbitrary WebSocket commands and messages directly from the interface
Automatic Heartbeat WebSocket connection is maintained with periodic heartbeats
Help Command Display a full list of commands with examples using the help command
User Interface Clean and professional design with color-coded logs (green for received, red for sent, blue for WebRTC)
Installation
To use this project locally

Clone this repository git clone https://github.com/SleepTheGod/WebSocketLogger.git cd WebSocketLogger

Open the index.html file in your preferred browser

Usage
Connect to a WebSocket server
Enter the WebSocket URL (e.g., wss://gateway.discord.gg) and click "Connect"
Send WebSocket messages
In the command input box, type send <your-message> to send custom messages to the WebSocket server
Log WebSocket and WebRTC messages
All WebSocket messages (sent and received) will be displayed in real-time
WebRTC signaling packets are also displayed with a blue background for easy identification
Use the help command
Type help in the input box to see a list of available commands and examples
Clear messages
Type clear to remove all messages from the log

Commands
send <message> Send a message to the WebSocket server
log <message> Log a custom message to the console
help Show this help message
clear Clear the messages displayed on the screen
<any WebSocket message> Send any WebSocket message (JSON, string, etc.)
Example Usage
Send a WebSocket message send {"op": 1, "d": 12345}
Log a custom message log Custom log message
Clear all messages clear
Get help help
License
This project is licensed under the MIT License - see the LICENSE file for details.
