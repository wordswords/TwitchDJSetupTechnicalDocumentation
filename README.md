# Current DJDC Twitch DJ Setup

- [Current DJDC Twitch DJ Setup](#current-djdc-twitch-dj-setup)
  * [Video Demo](#video-demo)
  * [DJing Setup Data Wiring Diagram](#djing-setup-data-wiring-diagram)
    + [Notes](#notes)
  * [DJing Setup Audio Flow Diagram](#djing-setup-audio-flow-diagram)
    + [Notes](#notes-1)
  * [Twitch Broadcast Setup Diagram](#twitch-broadcast-setup-diagram)
    + [Notes](#notes-2)
  * [Software Used](#software-used)
  * [To come later](#to-come-later)

<small><i><a href='http://ecotrust-canada.github.io/markdown-toc/'>Table of contents generated with markdown-toc</a></i></small>


This is my DJ setup for Twitch DJing. For more information on my DJing, see https://www.DJDavidCraddock.com

To zoom in to any of the diagrams, right click on them and select 'open image in new tab'.

## Video Demo
[![Watch the video](https://img.youtube.com/vi/4pt2nO5LPyc/0.jpg)](https://www.youtube.com/watch?v=4pt2nO5LPyc)

## DJing Setup Data Wiring Diagram
![alt text](DJDC%20DJing%20Laptop%20Data%20Connectivity%20Diagram.drawio.png "DJing Setup Data Wiring Diagram")

* DJing Laptop - Lenovo Legion 5 - Nvidea 3070ti 12th Gen i7 16 GB DDR5 RAM 512GB SSD
* Thunderbolt 3 Hub - MOKiN - 14 in 1 USB-C Laptop Thunderbolt 3 Hub
* Vinyl turntables - 2x Reloop 8000mk2s turntable/serato controllers
* CDJ - Numark NX500 CD player/serato controller
* Serato Sampler Controller - Akai LPD8 USB midi controller
* Phase Controllers - MVM Wireless Vinyl DVS Phase Controllers
* DJing Music SSD - SanDisk Extreme 1TB Portable NVMe SSD
* Wireless mouse

### Notes

* I have tried to minimise wireless traffic in the studio room in favour of wired, and will continue to do so.
* The DJing laptop is connected to TWO wired networks, it has two interfaces that are in use. One is connected
via a 2.5gbit USB3 network adaptor to my 10GB/sec private network (no internet). The other is connected to my
1GB/sec wired network, with a gigabit internet connection.
* The fast connection to my private high speed network allows rapid transfer of music from my server upstairs
where the music is kept, and backed up.
* I use Mixed in Key 10 on the DJing laptop. The CPU power of the laptop means that it is relatively quick to
analyse the ~20,000 files that I have.
* I also analyze all music in Serato before playing it.
* This setup works really well with Serato 3 stems, and is able to analyse stems on track load no problem.
* I also keep my mobile phone on a phone holder during the stream as a backup way of checking the stream /
chatting in the stream.

## DJing Setup Audio Flow Diagram
![alt text](DJDC%20Setup%20Audio%20Flow%20Diagram.drawio.png "DJing Setup Audio Flow Diagram")

* Broadcasting PC Sound Interface - Behringer UMC1820 USB2 Interface
* Broadcasting PC - Custom built PC see - https://davidcraddock.net/my-computer-setup/
* Main mic - R0de Procaster with mic boom, roll cage and pop sheild
* Guest mic - I have two.. standard mic with mic stand and pop shield, and a wireless headset mic
* Hardware synthesiser patchbay - standard balanced patchbay.. wiring for synthesisers and music studio setup 
will be explained in another repo and linked to this
* External VU Meter - Douk Audio 56 Bit Level Meter
* Roland 707m - Roland DJ707m Serato Controller and 4 channel Advanced Hardware Mixer
* Booth Monitor Speaker - Presonus Eris E3.5 Active Monitor (Single)
* DJ headphones - Sennheiser HD 25 Plus 

### Notes

* Each channel on the 707m has at least two options - Line or PC. When the channel is in line mode, it pulls
the audio sent into the mixer. When it is in 'PC' mode, it will use the controller synced with the Serato channel
to manipulate and play the digital track loaded onto the Serato deck.
* All platters I have synced to Serato work in Serato 'HID' mode for low latency when scratching.
* I have two options with DVS using the Reloops - play a vinyl DVS record, or use the phase controllers.
* I usually use the phase controllers when they are charged, or the DVS records when they are not. They maintain
a charge for about 5 hours.
* Channel 1 also has the option, instead of using Line or PC mode.. to use TR mode, which is the 707ms internal
drum machine. I find this very useful. It is useful in redrumming tracks, but also, it is useful in sending MIDI
sync messages over the external MIDI port in the 707m for use in my music studio. I have experiemented a lot with 
this previously when triggering external Eurorack drum machine modules. I currently don't have this setup, it probably
requires another person 'piloting' the Eurorack while I DJ.

## Twitch Broadcast Setup Diagram
![alt text](DJDC%20Broadcast%20setup.drawio.png "Twitch Broadcast Setup Diagram")

### Notes

* I position the DroidCam old mobile phone usually to show off various bits around the studio, such as the laser I
have with the smoke machine. I don't always use it.

## Software Used

* Serato DJ Pro 3 with all extras
* Resolume Avenue 7
* Resolume Wire
* Mixed in Key 10
* NDI Tools (free)
* Streamlabs OBS
* Moobot
 
## To come later

* Monitors setup
* Lighting setup
* Extras (DVS records, cartridges etc)
* Furniture/mounts list
