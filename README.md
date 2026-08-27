# ce5-board

The travellers board for the CE-5 Beacon (https://pizzy00.github.io/ce5-beacon/), with no server.

- The beacon page files each finished trip as a **new issue** here (body = one JSON object: call-sign, destination, light-years).
- The `board` Action turns the open issues into **[board.json](board.json)** and the readable **[BOARD.md](BOARD.md)**, then closes them.
- The page reads `board.json` straight from GitHub.

Nothing personal is stored: a made-up call-sign (or one the traveller typed), the destination, the light-years, and the time.
