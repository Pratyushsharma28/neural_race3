# NEURAL//RACE 🏎️

A futuristic 3D browser racing game built with React and Three.js. Race around a circuit against two AI opponents, complete three laps, and review your driving stats at the finish.

## Features

- 3D racing scene with a player car and two AI opponents
- Keyboard controls for acceleration, braking, steering, and drifting
- Three-lap races with ordered checkpoints and position tracking
- Start countdown, live race HUD, and minimap
- Race results with finish time, position, and six Driver DNA stats
- Scenic environment with trees, buildings, lamps, and grandstands

## Tech Stack

- React
- Three.js
- React Three Fiber and Drei
- Webpack and Babel

## Controls

| Key | Action |
| --- | --- |
| `W` or `↑` | Accelerate |
| `S` or `↓` | Brake / reverse |
| `A` or `←` | Steer left |
| `D` or `→` | Steer right |
| `Space` | Handbrake / drift |

## Getting Started

### Requirements

- Node.js
- npm

### Install and run

```bash
git clone https://github.com/Pratyushsharma28/neural-race.git
cd neural-race
npm install
npm run dev
```

Open the local URL printed in the terminal.

### Production build

```bash
npm run build
```

The production files are generated in the `dist` folder.

## How to Play

Choose **Start Race** and wait for the countdown. Drive through the checkpoints in order and complete three laps. Your position is tracked against two AI opponents. After finishing, view your time, position, and Driver DNA scores. Choose **Race Again** to restart or return to the main menu.

Driver DNA displays scores for speed, risk, precision, drift, aggression, and consistency based on race telemetry.

## Project Structure

```text
src/
├── App.jsx
├── main.jsx
└── components/
    ├── Game.jsx
    ├── Track.jsx
    ├── PlayerCar.jsx
    ├── AIOpponent.jsx
    ├── CarPhysics.js
    ├── CarControls.js
    ├── RaceManager.jsx
    ├── DriverDNA.js
    ├── CameraController.jsx
    ├── Environment.jsx
    ├── Countdown.jsx
    ├── HUD.jsx
    ├── Minimap.jsx
    ├── MainMenu.jsx
    └── ResultsScreen.jsx
```

## Deploying on Render

Create a **Static Site** and use:

- **Build Command:** `npm ci && npm run build`
- **Publish Directory:** `dist`

## Future Improvements

- Connect the planned safe/risk route fork to the track and race logic
- Improve AI racing behavior and finish-time ranking
- Add sound, mobile controls, and saved best times

## Credits

Created as a college hackathon project. Add your team members’ names and any asset credits here.