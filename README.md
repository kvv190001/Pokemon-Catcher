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

## 🚀 How to Run
```bash
python main.py
```

1. A silhouette of a random Pokémon will appear.
2. Type your guess.
3. Whether you're right or wrong, you'll then get a chance to catch the Pokémon!
4. Show your hand to the webcam and move it up or down to throw the Pokéball.
5. After the throw, the result is shown and added to your Pokedex if caught.
6. All images will be automatically deleted at the end of the game.

## 🖼️ Screenshots
![image](https://github.com/user-attachments/assets/9966d4aa-3d49-4dfa-ad96-2b6cbc620917)


## 🧠 How it Works
- The app uses MediaPipe Hands to track your palm position.
- A "throw" is detected by tracking significant vertical movement.
- 75% chance to catch the Pokémon after a throw.
- The silhouette is created by converting the image to grayscale and removing brightness.
