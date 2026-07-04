# ⏰ Python Alarm Clock

A simple Alarm Clock application built using Python. It allows users to set an alarm for a specific time, continuously checks the current system time, and plays an alarm sound when the set time is reached.

This project helped me practice Python fundamentals while building something useful.

---

## 📌 Features

- Set an alarm using 12-hour format (AM/PM)
- Continuously checks the current time
- Plays an alarm sound when the alarm time matches
- Alarm keeps playing until stopped by the user
- Handles errors if the audio file cannot be loaded

---

## 🛠️ Technologies Used

- Python 3
- datetime
- time
- pygame

---

## 📂 Project Structure

```
Python-Alarm-Clock/
│
├── alarm_clock.py
├── air_raid_siren.mp3
└── README.md
```

---

## 🚀 Installation

Clone this repository

```bash
git clone https://github.com/YourUsername/python-alarm-clock.git
```

Move into the project folder

```bash
cd python-alarm-clock
```

Install the required package

```bash
pip install pygame
```

---

## ▶️ Run the Project

Run the Python file

```bash
python alarm_clock.py
```

Enter the alarm time in the following format:

```
07:30 AM
```

Example:

```
Enter the alarm time (HH:MM AM/PM): 07:30 AM

Alarm set for: 07:30 AM
Current Time: 07:29 AM
Checking 07:29 AM vs 07:30 AM
```

When the current time matches the alarm time, the alarm sound will start playing.

Press **Enter** to stop the alarm.

---

## 📚 What I Learned

While building this project, I practiced:

- Taking user input
- Working with loops
- Using if conditions
- Handling date and time
- Using external libraries (Pygame)
- Exception handling
- Writing clean and readable Python code

---

## 💡 Future Improvements

Some features I would like to add in the future:

- GUI using Tkinter
- Multiple alarms
- Snooze button
- Custom alarm sounds
- Daily repeating alarms
- Desktop notifications

---

## ⭐ Thank You

If you found this project helpful or interesting, feel free to give it a ⭐ on GitHub.

Feedback and suggestions are always welcome!
