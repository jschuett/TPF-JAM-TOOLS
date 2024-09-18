
Skip to content
Navigation Menu

    jschuett
    /
    tpf-jam-tool

Code
Issues 2
Pull requests
Discussions
Actions
Projects
Wiki
Security
Insights

    Settings

Editing README.md in tpf-jam-tool
Breadcrumbs

    tpf-jam-tool

/
in
main

Indent mode
Indent size
Line wrap mode
Editing README.md file contents
Selection deleted
12
13
14
15
16
17
18
19
20
21
22
23
24
25
26
27
28
29
30
31
32
33
34
35
36
37
38
39
40
41
42
43
44
45
46
47
48
49
50
51
52
53
54
55
56
57
58
59
60
61
62
63
64
65
66
67
68
69
70
71
72
73
74
75
76
77
78
79
80
81
82
83
84
85
86
87
88
89
90
91
92
93
The TPF-Client application handles firewall and IT settings, allowing you to focus on immediately connecting with other musicians and starting to jam. The digital audio workstation "Reaper 7.16"(the newest) is your digital mixing console. You can mix the incoming signals in a virtual room with Reaper and the pre-installed third-party plugins.
Of course, the mix can also be recorded directly in Reaper, providing an instant recording of your jamming session.

And now .... let's jam...


-----

# What can TPF-JAM-TOOL do?

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


### You can download the TPF-JAM-TOOL here: -> comming soon

#### NOTE:
TPF-JAM-TOOL is for testing and is still under development!
Please read the [installation](https://github.com/jschuett/TPF-JAM-TOOL-tool/wiki/Installation) instructions!

---

## Prerequisites
Make sure to have all these Applications pre-installed:
- [TPF-JAM-TOOL ]() in development
- [TPF-Client_v2.0.17+](https://github.com/zhdk/tpf-client)
- [ICST Ambisonics Plugins](https://github.com/schweizerweb/icst-ambisonics-plugins/wiki)
- Try the unofficial version v3.0.0.3

##### NOTE: The LV2 version of these Plugins is experimental and not jet-ready!!
- [IEM-Plugin-Suite](https://plugins.iem.at/)
- [Reaper.app ](https://www.reaper.fm/download.php)
- [BlackHole](https://github.com/ExistentialAudio/BlackHole)
  BlackHole is a modern macOS virtual audio loopback driver that allows applications to pass audio to other applications with zero additional latency. Donate $10.

##### NOTE: 
After downloading, open the dmg file and drag the Reaper.app into the folder '/Applications/TPF-JAM-TOOL'. Open the Reaper.app with Ctrl-click or right-click.

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
4. by Mail invitation from 'Bandleader', you get all the needed information, like server address, room, and link to Livelab
5. open Reaper, then choose "Setting" -> "Device" and select your 'Aggregate TPF-JAM-TOOL'.
6. the left toolbar of the Reaper template contains all the necessary functions for a telematic connection.
7. press the button 'tpf-client on'
8. go to Settings in 'tpf-client', and add your <location-name> and the <jamming-room-name>. 
9. before connecting to the server, check your inputs in Reaper and unmute your local inputs 1 and 2 (the channels in tpf-client are green flickering)
10. to connect to the server, click the top left square in the tpf-client. If connected, it will turn blue. 
11. one by one, all fellow musicians/locations will appear. You can connect by clicking the square on the left. You should now hear them all.
12. click "LiveLab on' in the left toolbar of Reaper, and Safari will open. Type in the LiveLab URL you received from the bandleader. In the settings of LiveLab choose 'no audio'.
13. then click 'start'. You should now be connected by video. 
    (set Google-Chrome.app as your main Browser)

Your audio should be connected to the TPF client and all other musicians/locations. You are connected to video via LiveLab in the Chrome browser. 
So, happy jamming...

---

### Closing the session

Use Control + Shift + m to toggle the tab key moving focus. Alternatively, use esc then tab to move to the next interactive element on the page.
Attach files by dragging & dropping, selecting or pasting them.
Home · jschuett/tpf-jam-tool Wiki


-----

©2024 [ICST/ZHdK ](https://www.zhdk.ch/forschung/icst)Switzerland
