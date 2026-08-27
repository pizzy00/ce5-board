# ce5-board

The travellers board for the CE-5 Beacon (https://pizzy00.github.io/ce5-beacon/), with no server.

- The beacon page files each finished trip as a **new issue** here (title `TRIP · <destination>`, body = one JSON object: call-sign and destination).
- The `board` Action turns the oldest open issues into **[board.json](board.json)** and the readable **[BOARD.md](BOARD.md)**, pushes, and only then closes them. Light-years come from a fixed table of the page's destinations, never from the issue. Only issues filed by the owner's key count; anything else is closed as not planned.
- The page reads `board.json` straight from GitHub.

What is stored: a call-sign (made up, or typed by the traveller), the destination, the light-years, and the time. Call-signs are public here. Nothing else.

**This issue tracker is a machine channel.** Bug reports for the beacon go to https://github.com/pizzy00/ce5-beacon/issues.
