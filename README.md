# unix-scripts-and-helpers
Small stuff making my life easier. Grab what might help you.

Most are wrappers and convenience structures around simple unix tools. Instead of typing something long, error prone and hard to remember, just call the script and be hapy.


## scripts
### universal
these should work on both linux and osx alike, probably BSC too! Haven't tested on WSL, but probably there as well

#### compressPDFs
Reduces filesizes of pdfs, you can choose presets in color reduction and compression levels. **Requires ghostscript to be installed.**

#### vid2mp4
Converts videos to mp4 (h.264/aac at 30fps), often reduces filesize dramatically on the way. This format has wide compatiblity, so it's a good pick for embedding or sharing.
Supported file formats: mp4,avi,mov,mkv,flv,wmv,webm
**Requires FFMPEG to be installed** 

#### kml2gpx and gmx2kml
Transforms between GPX and KML geo formats.
**requires gpsbabel to be installed**


### OSX only
#### killDNS
a quick wrapper around 2 calls that are flushing the local DNS cache. useful when updating and debugging Domain records.

#### badQuarantine
Sometimes OSX locks my scripts in quarantine, especially when i copy them over from /usr/local/bin. this script fixes that so you can edit them again. 


## Bashrc & zshrc helpers
A tiny collection of small shell helpers, making navigation the terminal more convenient

### up N
As seen on the ubuntuusers.de - a small bash script under the gplv3 that nagigates folders in an easy way.
I added a zsh compatible version on top.

### ll
just a short alias to ls -laH - your fingers will be thankful.
