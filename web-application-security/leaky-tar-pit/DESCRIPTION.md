With the ability to read any file as root, hackers can exfiltrate sensitive information from the server. However, what information can hackers still read from an unelevated server? Can you leak the flag?

Ps. You can only start the server through `/challenge/run`; it will start a proxy server at `localhost:80` and redirect all of your traffic to the actual web server address (at `localhost:1337`). You don't have to worry about the proxy; it's only there to avoid confusion due to port number change from the last challenge.
