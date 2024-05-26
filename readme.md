# EMF Camp Schedule Viewer
Once you have got your link to your favourite talks/workshops from [EMF 2024 Line-up](https://www.emfcamp.org/schedule/2024), clone/fork this repo, modify the code, and run it to generate your personal gantt chart. Github uses [Mermaid.js](http://mermaid.js.org/syntax/gantt.html) to render the code block, so you can visualise the output by committing the repo back to github.

```mermaid
gantt
    title Your EMF Camp Schedule
    dateFormat YYYY-MM-DD HH:mm
    axisFormat %a %H:%M
    section Friday
      Opening Ceremony  :crit, 2024-05-31 10:00, 30m
      Script your way to circuit boards with CircuitPainter  :done, 2024-05-31 10:30, 60m
      The Tiny Tool Kit Manifesto  :active, 2024-05-31 11:40, 30m
      Build your own sensor.community air quality monitoring station!  :done, 2024-05-31 12:30, 60m
      Digital Music Synthesis/Solder workshop with ArduTouch music synthesizer kit  :done, 2024-05-31 13:30, 150m
      Let's Party Like It's 1994 - Re-Imagining How to Find Stuff Online  :active, 2024-05-31 13:40, 30m
      Lightning talks (Friday)  :2024-05-31 15:30, 30m
      Matchmaking for Creators  :done, 2024-05-31 16:00, 60m
      Downpour & more  :2024-05-31 16:40, 30m
      Mastodon.me.uk (and fediverse friends) Tootup  :done, 2024-05-31 21:00, 60m
    section Saturday
      Computer Font Making Workshop  :done, 2024-06-01 10:00, 120m
      Connecting Arduinos to websites  :active, 2024-06-01 10:40, 20m
      Hackspace Foundation Meetup  :done, 2024-06-01 11:00, 120m
      Are archivists pointless when the cloud can just save everything?  :active, 2024-06-01 11:20, 30m
      From Tax Law to Tangible Dreams  :2024-06-01 12:30, 20m
      Exploring and extending the Elite game engine for the BBC Micro  :active, 2024-06-01 12:40, 40m
      Eavesdropping on Eastnor’s bats  :done, 2024-06-01 13:00, 90m
      Keeping shell history in sync with turtles and magic  :2024-06-01 13:40, 30m
      Making automata from paper clips and beads  :done, 2024-06-01 14:30, 120m
      Hack the Printer! Hack the Printer!  :active, 2024-06-01 14:50, 30m
      Build Your Own Satellite Ground Station 📡  :done, 2024-06-01 15:30, 120m
      Lightning talks  (Saturday)  :2024-06-01 16:10, 40m
      Data is plural  :2024-06-01 17:00, 20m
      Furoshiki - The art of fabric wrapping  :done, 2024-06-01 17:30, 30m
      The story of Älgen guitar  :active, 2024-06-01 18:10, 30m
      Girls Just Wanna Play Games (and be represented in them)  :2024-06-01 18:50, 30m
      Up - A Scientist's Guide to the Magic Above Us  :active, 2024-06-01 19:30, 30m
    section Sunday
      From Makerspace to Outer Space  :active, 2024-06-02 10:00, 30m
      Where is the Art? A history in Technology  :2024-06-02 11:10, 20m
      Bringing Any Super 8 Camera Into The Digital Age  :active, 2024-06-02 11:50, 30m
      BIG PIPES! A dive into Scotland's hidden underground hydroelectric infrastructure 🌊  :crit, 2024-06-02 12:20, 30m
      Contrary to popular belief, tech needs unions  :crit, 2024-06-02 13:40, 30m
      Hack The Plan  :active, 2024-06-02 14:00, 30m
      Badge Talk  :crit, 2024-06-02 14:20, 30m
      Art with character(s)  :done, 2024-06-02 14:30, 60m
      Surface mount electronics assembly for terrified beginners  :done, 2024-06-02 15:00, 120m
      BMI270 sensor, the Badge, MicroPython and everything  :done, 2024-06-02 16:00, 90m
      Driving fancy LED panels with commodity hardware  :2024-06-02 16:40, 30m
      How to build a physical work/life balance.  :active, 2024-06-02 17:30, 30m
      Closing ceremony  :crit, 2024-06-02 19:00, 30m
      Karaoke  :done, 2024-06-02 20:00, 180m
```