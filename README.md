###💡Inspiration
Due to the pandemic, there has been a large shift to learning and meetings being done online through the various online meetings platforms. However, attending these meetings has now become quite a gruesome task especially after people have been spending hours on end in them over this past year. We feel that traditional online meetings need to be updated to make them a more enjoyable task. We plan to accomplish this by making joining meetings more fun and enjoyable by adding a game-like aspect when joining calls.


###❓What it does
Link Up works by allowing individuals to join various video meeting rooms by using a game in which you control a character to move into the specific room you want to join. Once you move towards the room it starts a voice and video call on our very own Link Up website, with your own room ID.


###🏗️How we built it
Frontend: HTML, CSS, JS
Backend: NodeJs, Socket.io, PeerJS, WebRTC, EJS
Deployment: Heroku 
Game: Unity, WebGL, Photon
Logo: Figma 
Pitch Video: Adobe Premiere Pro

The video chat application was built using vanilla HTML/CSS/JS while using EJS as a templating language. For the backend, we used Socket.io, PeerJS, and WebRTC to create peer-to-peer connections within the browser running on a NodeJS server, connecting you with players within the Link Up game.


###🚧Challenges we ran into
Throughout the process of creating LinkUp we ran into a variety of challenges when bringing our idea to fruition. During the deployment of the meeting platform we came across an issue in which certain users' videos were not being registered, due to Heroku using different ports when trying to establish a peer-to-peer connection, however through some troubleshooting we were able to solve this problem. Another aspect of this project that was causing us some difficulties implementing was the multiplayer functionality in the game when our characters will not spawn in or not move properly. We managed to resolve this as well through help from mentors and problem-solving.

Overall building a product with technologies so foreign to us in such a small time frame really constricted our vision. We tried to cram in as much detail as programmatically possible and refine all the kinks in our platform, but plan to continue to fine-tune our platform after Hack the North concludes.


###✅Accomplishments that we're proud of
The completion of our project was a huge accomplishment for us. But more specifically being able to create a video chat system in such a short time with a library that was new to us was most nice, and getting peer-to-peer connections to work both in Unity and in the Browser proved to be a daunting task.


###🙋‍♂️What we learned
Through the process of building this project we learned and refined a variety of skills. We were able to refine and build upon our Unity skills. We also used Socket.io for the first time for the building of the video chat system which was a good introduction to the library and made it very enjoyable to learn, and now we are familiar with how peer-to-peer connections work and can implement them in our next adventures.


### 💭What's next for Link Up
Moving forward we would like to refine the design and add more detail to the game aspect of this project. We would like to make it so our game can support a larger player base running at one time, and add a bigger open world aspect into our game, integrating more level design making exploration a bigger focus, overall adding more enjoyment into the game.


###Github Repositories
- [LinkUp Video Chat Web application Repo](https://github.com/tyseer2335/LinkUp)
- [Unity WebGL Game Repo](https://github.com/mohas1203/Link-Up)
