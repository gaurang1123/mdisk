Mdisk
Install
For Package
pip install mdisk
pip install git+https://github.com/HeimanPictures/Mdisk.git
Usage
You can use this as python module or via terminal

Use as python module
from mdisk import Mdisk

d = Mdisk("YOUR_API_KEY")

# Upload video from direct links
d.upload("VIDEO_LINK")
Use via terminal
set your Mdisk api key first

export MDISK_API=you_key_here
Providesw link for mdisk
mdisk upload VIDEO_LINK
