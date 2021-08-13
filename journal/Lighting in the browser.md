### Rationale
- What does it mean to have lightning in the browser?
-  Why should a node need to be in the browser?
- Why should lightning be in a browser?
- Lightning is a near instant payment system. What benefits does this have

**Why lightning in the web?**
-   Content monetization
-   Brave
-   Still used by xx% of Internet users which is xxxxxx
-   Aversion to downloading applications.
-   Still an open platform, no app stores, no commissions, importance of a browser
-   Mobil Applications are inherently centralized 
-   Not anyone can publish
-   Restrictive
-   No accounts
-   Ephemeral
-   Cross platform
-   Privacy
  

**The role of burner wallets** 
-   Reference Austin Griffin
-   Easy on boarding
-   Experimentation
-   Discovering new business and content monetization models
-   Number of Web developers vs native application developers.
-   Bitcoin needs more experimentation on the application layer. Those innovations have been coming from the web(has it?)
-   Ajax loading. Infinite scroll    

## Approaches
```
I see a couple of technical design options which would impact UX.

1.  Run a LN node as an app on the computer with the browser (eg your laptop) or on a remote computer that the user controls (eg a rpi). A browser extension is a relatively simple remote control to that LN node.
2.  Run a LN node (the LN state machine and key signing) inside a browser extension (eg using the modular LDK). A proxy server, which could be a 3rd party, would maintain LN TCP connections with peers, and would communicate with the browser extension via websockets.

Option 2 has the advantage of not requiring a user to install and operate a LN node on a computer. Option 1 has the advantage of better privacy as a 3rd party trusted server isn't needed to send/receive LN p2p messages. Both options are non-custodial.

Are each of these options being considered and discussed in terms of impact on UX design?
```
-   [Full node in-browser](https://bolt.fun/guide/architecture#full-node-on-device)
-   [Partial node in-browser](https://bolt.fun/guide/architecture#partial-node-on-device)
-   [Remote controlled node](https://bolt.fun/guide/architecture#remote-controlled-node)
-   [3rd-party controlled node](https://bolt.fun/guide/architecture#3rd-party-controlled-node)
    
### Full node in a browser (not possible)

- The browser enviroment isnt able to perform TCP...
- Web Sockets connecting to a proxy

### Partial node in-browser
**Why Partial nodes on device**
Because Limitations 
-   low power
-   low bandwidth
-   low storage

A similar architture to [partial node on mobile devices](https://bolt.fun/guide/architecture#partial-node-on-device).

https://medium.com/simplecoin/toward-a-lightning-node-in-the-browser-847ba0194697

WebAssembly

### Remote controlled node.
- installed on the device
- installed on another device

### 3rd-party controlled node/channel.
lndhub

Notes from Steve 

