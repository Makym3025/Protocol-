Would you like to be anonymous on the internet? To not be subject to any censorship?

I'd like to introduce you to my custom data exchange protocol between users. How does it work?

All messages go through a tracker, which you can host on various platforms, such as Replit. Then, when a peer connects to your server via py peer_http (url), all your messages will be encrypted with your key and transmitted securely through the tracker — this means end-to-end encryption.

But that’s not all!

Before reaching the final recipient, all your messages will be routed through other users, similar to how the Tor browser works. These messages are sent in encrypted fragments, and the recipient will reassemble them into a complete message. No one — not even the tracker — will know who sent the message or who the recipient is.

In the beta version, messages are visible to everyone because they pass through users in plain form, but in the future version, this will no longer be the case.

