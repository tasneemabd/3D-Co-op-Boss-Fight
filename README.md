🕹️ 3D Co-op Boss Fight – Game Developer Test
🎯 Objective
Create a 3D cooperative (co-op) PC game where two local players collaborate to defeat an evil boss with multiple timed attack patterns, developed using Unity Engine.

🚀 Game Overview
In this action-packed boss battle, two players must dodge dynamic attacks, outmaneuver a powerful flying boss, and strategically return unexploded rockets to defeat it.

Engine: Unity (2022.3.32f1)

Platform: PC (Local Co-op)

Control: Same keyboard

👾 Boss Mechanics
🧠 Movement
Flies and hovers dynamically, presenting a moving threat.

Continuously repositions to challenge players.

🔥 Attacks
Fire Flame

Shoots a beam using Particle System.

Eagle Strike

Boss disappears off-screen.

Shadow appears indicating the impact zone.

Boss slams vertically onto the shadow.

Rocket Launch

Boss locks onto both players.

Launches 3 rockets:

2 explode on impact.

1 remains unexploded and can be picked up and thrown back.

🧑‍🤝‍🧑 Player Mechanics
Local Co-op:

Player 1: WASD keys

Player 2: Numpad keys

Health: 3 hearts per player.

Throw Mechanic:

Players can pick up the unexploded rocket and throw it back to damage the boss.

Win Condition: Boss is hit by 3 returned rockets.

Lose Condition: Both players lose all hearts.

🎮 Game Flow
1. Main Menu
Play

Character Select

Settings:

Toggle Music

Toggle SFX

2. Transition Scene
Loading scene

3. Gameplay
UI includes heart icons for each player

4. End Game
Win or Lose screen

Options:

Restart Fight

Return to Main Menu

🧩 Assets Used
Simple primitive shapes (e.g., Capsules, Cubes)

Realtime Rascals

📁 Asset Download
🔽 Download the full asset package used in this project from Google Drive:
Download Assets from Google Drive :https://drive.google.com/file/d/1iN03U0KlodACPjFxo8rqqgXRuHEZAkUN/view?usp=sharing

⚠️ Make sure to extract the contents into the Assets/ folder in your Unity project directory.

🗂️ Project Structure

Assets/
├── Scripts/
├── Prefabs/
├── Scenes/
├── UI/
├── Art/ (optional)
├── Resources/
└── SaveSystem/
📦 How to Build & Play
Clone the repo:


git clone https://github.com/tasneemabd/3D-Co-op-Boss-Fight.git
Open with Unity 2022 or later.

Open the MainMenu scene.

Build for PC (Windows/Mac) via File > Build Settings.

Play using:

Player 1: WASD

Player 2: Numpad

Optional: Gamepad

🔗 Repository URL: https://github.com/tasneemabd/3D-Co-op-Boss-Fight.git

👨‍💻 Developer Notes
Built with performance and clarity in mind.

Mechanics are extensible for future gameplay expansion.
