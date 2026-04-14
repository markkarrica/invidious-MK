# invidious-MK
I currently don't like Invidious default frontend and I don't want to learn Crystal just to fork and make my modifications. So I made this repository to make my own Invidious frontend in React (Next.js)

# Why this repo
The Invidious front-end works, but I think it could be better.
Many people think open source software is about cheap and ugly alternatives to closed source software. It's not, and I'm here to prove it.
My solution will:
- provide a Single Page Application, with animations and transitions to provide a smooth experience to the user
- use a modern frontend framework (I might throw it at Babel to satisfy older browsers)
- be oriented to be as minimal as possible, without having many unnecessary elements (for example, the Reddit comments button, I hate it)
- communicate with the backend by using the JSON format (instead of the current HTML format which isn't even minified, using network resources to send unnecessary whitespace and html tags)

I'm doing it just for fun, but it might become serious later in the future.
Since this is not a fork and uses only the backend APIs I could use any license for this project, but I decided to keep the same license of the Invidious project to contribute to the OSS community.
Also, I'll probably study and replicate some of the JavaScript files related to the player and watch page, since the Invidious player works and works well.

# Requirements
This is a list of requirements to remind me what I should implement.

## MUST HAVE - essential for the application
- [ ] A usable product and player
  - [ ] Homepage with the search bar
  - [ ] Search results are displayed correctly
  - [ ] Player plays the video and has the same features of the Invidious one
- [ ] Animations and transitions between pages
  - [ ] From homepage to search results
  - [ ] From search result to player

## WILL HAVE - things that I will surely implement
- [ ] Comments support
  - [ ] Show current video's comments
- [ ] Related videos support
  - [ ] While the current video is playing, the user has the list of related videos (from YT)
  - [ ] The feature must be optional (as in the original Invidious frontend)
- [ ] Queue support
  - [ ] When the current video is playing, the user should have the ability to add other videos to the queue
- [ ] Playlist support
  - [ ] Playlists are loaded from the search result and display their contents
  - [ ] Once a video from a playlist starts, the playlist becomes the queue
- [ ] Channel support
  - [ ] Load the channel and show its videos

## MAY HAVE - things that I will probably implement
- [ ] Shorts support
  - [ ] On the channel page, have the options to watch its short videos
- [ ] Small picture mode to keep searching and enqueue more videos
  - [ ] Ability to put the playing video in small picture mode to let the user search for more content and add it to the queue
- [ ] Themes support
  - [ ] Allow the user to choose their own flavour from the ones offered by me, or by importing external ones

## NICE TO HAVE - things that I won't implement unless I'm bored
- [ ] Account management
  - [ ] Handle subscriptions
  - [ ] Handle personal playlists
  - [ ] I'll try to replicate the current account management that Invidious has. I prefer to use it without accounts but since the backend is already done I might implement this.
- [ ] Party mode
  - [ ] Have many people scan a QR code to handle the same queue
  - [ ] this requires proper backend work and I will make it as a separate project, probably forking Invidious or something else, idk
     
I might move things up and down from this list of requirements as I wish. If something else comes to mind I'll add it here.
There's a lot of work to do, but it'll surely be fun.
