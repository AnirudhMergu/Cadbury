# Cadbury
## Decentralized meetings powered by web3

Open,neutral,bodorles,decentralized and Censorship resistance Meetings(Google Meet / Zoom) powered by web 3.

Core Team [Ayush Ranjan](https://github.com/ranjan3118)  

### Cadbury Meets Flutter !

https://github.com/susmit/Cadbury-Flutter

### Working Product:-

Fleek https://cadbury.on.fleek.co/

IPFS https://ipfs.fleek.co/ipfs/QmTFJZQwtrJTV4FmLfZDSZgFC64q8ExLVEFG4CXCeR9GXF/

Unstoppable Domain => meet-cadbury.crypto

Signaling https://meet-cadbury.herokuapp.com/

Flutter https://github.com/susmit/Cadbury-Flutter


### Meeting's Infra
* Capture media from web cam via getUsermedia.
* Signaling service (code in server.js) to discover user browsers (ICE,SDP,Offers,Answers) via websockets/libp2p-websockets(can be used as alternative).
* Connection libp2p-js-webrtc (can be used as alternative) / Webrtc on browser.
* RTCPeerconnection sets up peer to peer connection.
* Send data (chat texts,images,files) to other peers via RTCDataChannel
* Sets up mesh network for multiparty peers.
* Ethtereum SMC handles rating system via metamask
* Hosted via fleek on IPFS Utilizing Unstoppable domains
* Pinata for manual meeting code archive (complementing pieces).
* Meeting artifacts on filecoin/ipfs via textile powergate. (A FFS API instance for every peer to be spwaned)
* FFS API is assigned to user via 3Box authentication and store FFS token in 3Box private Profile.
 

### Meeting's Mechanics
* To run the meeting open cadbury fleek link https://cadbury.on.fleek.co/ which will guide you to land page.
* Press Start button and you will be guided to meeting ready page.
* Copy the meeting code to share with other peers who wants to join ,you can set your own custom name too.
* Press Join now,Hola !
* Since IPFS host static website sharing dynamic link will not work,therfore other peers are adviced to enter same meeting room.
* To join meeting go to https://cadbury.on.fleek.co/ ,press Start button,Enter your meeting code ,Press Join now,Hola !
* To access your powergate ffs instance api, select file icon.
* Since meetings establishes mesh network,it works bests for less than 6 peers. (for performance and scalability will be handled via our upcoming protocol).
* Sharing links works on static website hosted with our signaling server https://meet-cadbury.herokuapp.com/.


![Cadbury Image](https://i.ibb.co/XscdngP/Screenshot-2020-08-09-at-11-49-15-AM.png)

![Cadbury Image](https://i.ibb.co/F5XMvXv/Screenshot-2020-08-09-at-11-49-54-AM.png)

![Cadbury Image](https://i.ibb.co/BqTCk34/Screenshot-2020-08-06-at-10-17-31-PM.png)

![Cadbury Image](https://i.ibb.co/S78vm7Z/Screenshot-2020-08-09-at-2-24-20-PM.png)

![Cadbury Image](https://i.ibb.co/KxDKsdf/Screenshot-2020-08-09-at-2-24-06-PM.png)

![Flutter](https://i.ibb.co/vd845xd/Screenshot-2020-08-14-at-5-54-45-PM.png)




