# 🐶 Python OOP Challenge: Digital Pet

Welcome to the Python Object-Oriented Programming challenge! This project is a virtual pet simulation built using Python classes and methods.

## 📌 Objective

Build a digital pet that can eat, sleep, play, and learn tricks! The project helps you practice using:

- Classes
- Attributes
- Methods
- Constructors (`__init__`)
- List handling (for tricks)

## 🐾 Pet Features

### Attributes
- `name`: Pet's name
- `hunger`: Hunger level (0 = full, 10 = very hungry)
- `energy`: Energy level (0 = tired, 10 = rested)
- `happiness`: Mood level (0 = sad, 10 = happy)

### Methods
- `eat()`: 🍽️ - Reduces hunger by 3 (min 0), increases happiness by 1
- `sleep()`: 😴 - Increases energy by 5 (max 10)
- `play()`: 🎾 - Reduces energy by 2, increases happiness by 2, increases hunger by 1
- `get_status()`: 📊 - Displays current pet state
- `train(trick)`: 🎓 - Teaches a new trick, adds it to a list, boosts happiness
- `show_tricks()`: 🧠 - Lists all learned tricks

SAMPLE OUTPUT

Creating pet: Max 🐶
Max is eating... 🍽️
Max is playing! 🐕🎾
Max is sleeping... 😴
Max is learning a new trick: roll over 🎓
Max is learning a new trick: play dead 🎓
Max has learned the following tricks: 🧠
- roll over
- play dead

Max's current status:
Hunger: 2
Energy: 8
Happiness: 9
Tricks: ['roll over', 'play dead']

Max's current status:
Hunger: 2
Energy: 8
Happiness: 9
Tricks: ['roll over', 'play dead']
