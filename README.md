# Who's That Pokémon?

A fun and interactive Python game that challenges you to guess a Pokémon from its silhouette—and then try to catch it using hand gestures and your webcam!  
Built with **OpenCV**, **MediaPipe**, **Pillow**, and the **PokéAPI**, this project blends computer vision and classic nostalgia.

---

## 🎮 Features

- 🎲 **Random Pokémon Generator** – Pulls a random Gen 1 Pokémon using PokéAPI.
- 🖼️ **Silhouette Guessing Game** – View a silhouette of a Pokémon and try to guess it.
- ✋ **Hand Gesture Interaction** – Use your webcam and hand motions to throw a Pokéball!
- 🧠 **Basic Gesture Recognition** – Catch a Pokémon by moving your hand up/down.
- 📦 **Pokedex Tracking** – See which Pokémon you've caught.
- 🧹 **Auto-cleanup** – All assets are deleted at the end of the game session.

---

## 🧱 Requirements

Install dependencies with:

```bash
pip install -r requirements.txt
```
Dependencies:
- opencv-python
- numpy
- requests
- Pillow
- mediapipe

You’ll also need:
- A working webcam
- Internet connection (to fetch Pokémon data)
