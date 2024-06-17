# TPF-JAM-REAPER
![TPF-JAM-TOOL - Overview](https://github.com/jschuett/tpf-jam-reaper/assets/773797/bb3272a7-cff0-4a40-b7f7-28fcc678058e)
Fig 1: TPF-JAM-REAPER in action.

## About

TPF-JAM-REAPER is a low-latency 'jamming tool' that connects sixteen different jamming partners/locations. (Mac only)  
TPF-JAM-REAPER further develops the previous tools '[tpf-tools](https://networkperformance.space/)' and 'TPF-JAM-BASIC'. [Reaper.fm](https://www.reaper.fm/) is one of the most widely used digital audio workstations (DAW) today. Reaper, as a DAW, is our choice because most of the parameters in Reaper can be operated via scripts ([LuaScript](https://dail8859.github.io/LuaScript/)) and are available for retrieval, as well as having early audio routing. The idea behind the TPF-JAM-REAPER is to provide a very easy-to-use bundle with a wide variety of possibilities. In connection with the SNSF research project '[spatial-dis-continuities-in-telematic-performances](https://networkperformance.space)', many features have been incorporated into this tool. 
Over the years, we spent many hours communicating over Zoom as a team of artists and researchers, which always tired us out quickly from an acoustic point of view. After experimenting with Ambisonics and Binaural rendering, many of us became less tired because a more natural hearing sensation set in, especially in music making.

This was the primary motivation to integrate the 3D audio research '[Ambisonics at ICST](https://ambisonics.ch/)' into the telematic applications in the [spatial-dis-continuities-in-telematic-performances](https://www.zhdk.ch/en/researchproject/575742) project.
The tools are freely available, and while the installation may take some time, it's a worthwhile investment. 
The TPF-Client application handles firewall and IT settings, allowing you to focus on immediately connecting with other musicians and starting to jam. The digital audio workstation "Reaper 7.16"(the newest) is your digital mixing console. You can mix the incoming signals in a virtual room with Reaper and the pre-installed third-party plugins.
Of course, the mix can also be recorded directly in Reaper, providing an instant recording of your jamming session.

And now .... let's jam...


-----

# What can TPF-JAM-REAPER do?
![Bildschirmfoto 2024-06-12 um 14 34 10](https://github.com/jschuett/tpf-jam-reaper/assets/773797/b4e76b2e-6555-4b45-8aae-14725feeb9d3)

- Low-latency bidirectional telematic jamming over Lan
- Two Inputs (Mic/Inst) sending to max 16-Destinations/Locations
- Receiving max. 16 locations 
- Placement in 3D audio (binaural) 
- Streaming a binaural Mix (2ch) over OBS
- Head tracking (Headphones)
- Recording
- Playback of audio from the DAW
- Rec/Play from external sources (e.g. Ableton)
- Play Video from the DAW
- The tools are freely available


---


### You can download the TPF-JAM-REAPER here:[Download](https://github.com/jschuett/tpf-jam-reaper-tool/releases/tag/v1.5.6b)
#### NOTE:
tpf-jam-reaper is for testing and is still under development!
Please read the [installation](https://github.com/jschuett/tpf-jam-reaper-tool/wiki/Installation) instructions!

---

## Prerequisites
Make sure to have all these Applications pre-installed:
- [TPF-JAM-REAPER ]()
- [TPF-Client_v2.0.13+](https://github.com/zhdk/tpf-client)
- [ICST Ambisonics Plugins](https://github.com/schweizerweb/icst-ambisonics-plugins/wiki)
##### NOTE: The LV2 version of these Plugins is experimental and not jet-ready!!
- [IEM-Plugin-Suite](https://plugins.iem.at/)
- [Reaper.app ](https://www.reaper.fm/download.php)
- [BlackHole](https://github.com/ExistentialAudio/BlackHole)
  BlackHole is a modern macOS virtual audio loopback driver that allows applications to pass audio to other applications with zero additional latency. Donate $10.
##### NOTE: 
After downloading, open the dmg file and drag the Reaper.app into the folder '/Applications/TPF-JAM-REAPER'. Open the Reaper.app with Ctrl-click or right-click.

---

## Usage

### Quick Start 
You have completed all pre-installations and are up to date.

--> Restart Computer!
1. first setup your Audio Interface and Hardware components, e.g.
	- Mic (CH1)
	- Instrument (Keyboard) (CH2)
2. be sure that your hardware works correctly with your Mac/PC
3. create an aggregate (Mac) and name it as shown in the following picture. The correct order of components is crucial.
   <img width="1463" alt="Apple_Aggregate_TPF-JAM-TOOL" src="https://github.com/jschuett/tpf-jam-reaper/assets/773797/92645938-7ed3-4cb8-abf4-73c7acf25b81">


4. by Mail invitation from 'Bandleader', you get all the needed information, like server address, room, and link to Livelab
6. open Reaper, then choose "Setting" -> "Device" and select your 'Aggregate TPF-JAM-TOOL'.
7. the left toolbar of the Reaper template contains all the necessary functions for a telematic connection.
8. press the button 'tpf-client on'
9. go to Settings in 'tpf-client', and configure the audio backend according to your Aggregate.
  
<img width="620" alt="Bildschirmfoto 2024-06-13 um 15 43 45" src="https://github.com/jschuett/tpf-jam-reaper/assets/773797/8d78c821-213e-4600-9d38-51bcb5ace7b5">

    
11. before connecting to the server, check your inputs in Reaper and unmute your local inputs 1 and 2 (the channels in tpf-client are green flickering)
12. to connect to the server, click the top left square in the tpf-client. If connected, it will turn blue. 
13. one by one, all fellow musicians/locations will appear. You can connect by clicking the square on the left. You should now hear them all.
14. click "LiveLab on' in the left toolbar of Reaper, and Safari will open. Type in the LiveLab URL you received from the bandleader. In the settings of LiveLab choose 'no audio'. Then click 'start'. You should now be connected by video. 


### Closing the session

1. click 'tpf-client off'. A message will remind you to disconnect all connections before.
2. press FPHD off and livelab off
3. close your Reaper session


For more detailed information, visit Wiki (Link) -->, which is coming soon!



----
## Bugs
For any bug, issue, or suggestion, please open an issue
[here](https://github.com/jschuett/tpf-jam-reaper/discussions).

---

## Links and Referencing
- [REAPER (DAW)](https://www.reaper.fm/)
	- [SWS/S&M](https://www.sws-extension.org/)
	- [ReaPack](https://reapack.com/)
- IEM Plugin Suite <https://plugins.iem.at/>
- ICST Ambisonics Plugins <https://github.com/schweizerweb/icst-ambisonics-plugins/wiki>
- TPF-Client 2.0+ <https://github.com/zhdk/tpf-client>
#### Optional
#### Head Tracker Tools:
- NX Head Tracker Waves <https://www.waves.com/hardware/nx-head-tracker>
- USB Head Tracker <https://supperware.co.uk/headtracker-overview>
- nvsonic <https://github.com/trsonic/nvsonic-head-tracker>
- RC HeadTracker <https://github.com/dlktdr/HeadTracker>
- OpenTrack (win/linux)
- SAKHeadTracker <https://spatialaudiokit.github.io/headtracker/>



#### NOTE to REAPER: 
Reaper is not free, but you get 60 days of evaluation free, with full functionality and no strings attached. All license purchases are final.
If you own multiple computers, you may install the same license key on all of them as long as you only use REAPER on one computer at a time.
[Purchasing Reaper](https://www.reaper.fm/purchase.php)
We have to thank all these wonderful resources:
- [SWS/S&M EXTENSION](https://www.sws-extension.org/)
- [ReaPack](https://reapack.com/)
Please donate them when you are happy with all these tools!

----


## Authors

Johannes Schuett / Roman Haefeli / Matthias Ziegler / Patrick Mueller 


----

## License
GPL 3.0 (see LICENSE.txt)

-----



©2024 [ICST/ZHdK ](https://www.zhdk.ch/forschung/icst)Switzerland
