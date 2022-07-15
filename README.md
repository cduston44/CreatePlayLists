# CreatePlayLists
Bash script that generates playlists from an artist/album directory structure. 

#
# This here script will take a directory full of directories of
# artist names organized like
#
# /artist1
#	album1
#	album2
# /artist2
#	album1...
#
# and create a playlist file in each album directory.
#
# Written by C L Duston (July 2022), christopher.duston@protonmail.com
#
# Run with bash CreatePlayList, after chmod crap.
# Make sure there are no other directories in this one
# except directories of artists!
# Like, watch out for that 'system volume information' nonesense!

Even more detail:
For some absolutely insane reason, even though all my music files have been ripped to a USB to be in the form

artist/album/trackno-songtitle

My stupid car (2021 Subaru Crosstrek) alphabetizes the songs in each album. Like, in what Universe does the person who coded this car stereo get off? This is stupidity on the scale of the sack of Carthage, or two-lane roundabouts, or chocolate/vanilla/strawberry ice cream. Would you read a book by shuffling the chapters? Would you watch Firefly with the episodes in a random order? Would you learn history by picking random dates and figuring out what happened on them? If you answered "no" to any of those questions, this code is for you.

I have only tested this run on Linux, played on a 2021 Subaru CrossTrek. Any further testing I would like to hear about, and would not need much convincing to come up with a Windows port / instructions. 

Fight the Power!
