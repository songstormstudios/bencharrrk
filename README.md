# bencharrrk
A benchmark of players sailing the seven seas playing Spacewar on Steam.

## Run

```powershell
node server.mjs
```

Then open:

```text
http://localhost:5173
```

The visible counter is served through `/api/player-count`, which calls Valve's public `GetNumberOfCurrentPlayers` endpoint. The SteamDB chart is embedded with SteamDB's documented iframe for App `480`.
