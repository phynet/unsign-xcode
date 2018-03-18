# Local Homebrew formula to unsign Xcode :boom::computer:

Sometimes you need to remove code signatures to Xcode. Why?...well, simple: you need more functionality than Apple gives you today. And for example, if you want to add some colors to your terminal when printing in debug state, it's necessary to do this. Speaking of hacking, right?. So I've created this local (not uploaded to homebrew repo yet) homebrew formula to help me out unsign Xcode. This doesn't have tests, so be aware of this. For me this is working fine, but if you find any bug, contact me and I will try to sort it out :)

### Note BTW: you don't need to clone this repo. Just follow the instructions below to get it done!


# How to use 

  Well, I've created a homebrew command to unsign Xcode, because it takes a lot of steps to unsign, and I usually tend to forget everything when I'm not using it constantly, and because it's cool. Thanks homebrew!. Cutting straight to the point:

:point_left:  Tap it  
 
      brew tap phynet/unsign-xcode

:floppy_disk: Install it:  

      brew install unsign-xcode

if a message appears telling you that a version X is already installed:

      Error: unsign-xcode 1.0.X is already installed
      To upgrade to 1.0.4, run `brew upgrade unsign-xcode`

run the command `brew update` and it will automatically update to the tag version for the current version.

:muscle: Use it:

       unsign-xcode
 
And there you have it :D

# Thanks

Thanks to [@j4n0](https://github.com/j4n0) for helping out, and [@steakknife](https://github.com/steakknife/unsign) from which I took the code in C to remove code signatures from OSX Mach-O binaries
