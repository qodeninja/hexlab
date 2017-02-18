# Intro

```
██╗  ██╗███████╗██╗  ██╗██╗      █████╗ ██████╗ ██╗
██║  ██║██╔════╝╚██╗██╔╝██║     ██╔══██╗██╔══██╗██║
███████║█████╗   ╚███╔╝ ██║     ███████║██████╔╝██║
██╔══██║██╔══╝   ██╔██╗ ██║     ██╔══██║██╔══██╗╚═╝
██║  ██║███████╗██╔╝ ██╗███████╗██║  ██║██████╔╝██╗
╚═╝  ╚═╝╚══════╝╚═╝  ╚═╝╚══════╝╚═╝  ╚═╝╚═════╝ ╚═╝                                                 
```

:blue_book: HexLab v.0.1 - Lab Management Tool

Hexlab is a NodeJS port of my Lab.sh bash script that I've used to manage my various code experiments and project stubs. The "Hex" part is a nice little hat tip to Node with its beautiful green hexagonly goodness -- that and all the cool namespaces were taken.

It's gonna be huge!

## Hexlab Data Structure
```
 => hex_root
      |_____ dist
      |_____ bin
      |_____ ext
      |_____ src
              |____ labs
              |____ projects
              |____ repos
              |____ graveyard
      |_____ curr
      |_____ zero
              |____ conf
              |____ notes
      |_____ db
              |____ cache
              |____ vars
```
---

## Installation

    $ npm install -g hexlab

## MagicScript

```js
#!/usr/bin/env node
"use strict" 
  const hexlab = require('hexblab');
  try{
    //its gonna be huge!
    hexlab.be_useful_right_now({ how : with_this_magic_fx });
  }catch( it_went_boom ){
    console.log('woops ur life is the suck!');
  }

```

## Backstory

Over my years of coding, I've struggled to keep my code and metadata organized. I wanted to make my tools and information consistently easy to find, reference and use whenever I setup a new development environment, and the more I coded the more I realized I needed to get better at keeping my stuff in order.

One day, I finally had enough and decided to make a plan of attack. The plan alone didn't work out well in early iterations because I kept forgetting what it was; so I created a script to codify the procedure (lab.sh).

The shell script has been really handy, to the point of surprise -- it's also reminded me time and time again that there are still plenty of things for me to learn how to do in bash that dont require fancy bash backflips. 

Nonetheless, I'm experimenting with NodeJS to try and share this little lab utility with others. 

## Oops

  Well this is awkward... noq ode here yet! :v: :punch: qodeninja

