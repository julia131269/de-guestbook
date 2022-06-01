# de-guestbook V1.1
### A guestbook(template) written in PACT for the Kadena Blockchain

First of all a shoutout to [github.com/Thanos420NoScope/Anon-Chat](https://github.com/Thanos420NoScope/Anon-Chat) that inspired this project. 
Most of the code is copied from anon-chat and [this frontend(IPFS)](https://ipfs.io/ipfs/QmcTRrux4MbjVFY3yCw6f2WDLgtpT5fmGZRDJrbgKZG59U) by anon. I built on top of it to customize and learn.
Click [here](https://julz.cafe/guestbook.html) for a working copy on my website!

## How to use?
Download all the files. Both html and pact files have comments that should explain all the changes you need to do, to setup your own guestbook!
Upload both contracts with a unique name and follow the comments.
Now all you need to do is open the html file or  upload it to your server and that's it!

## Features:
* Catching html injections and rendering them safely
* Fully decentralised backend, storing messages on the Kadena Blockchain
* Customisable locale for displaying Date and Time. Date and Time gets converted to viewers timezone
* Ability for the contract uploader to change content of entries if needed with a suffix added to notify Users the message has ben edited
* Direct links to imgur.com get automatically inlined
* "4chan style" quotes of post get automatically linked
* Every post contains a link to the block containing the send call
* No Copyright, feel free to do whatever you want to. No attribution required, sell it as your own project if you wish :)
* Made with love in Germany
