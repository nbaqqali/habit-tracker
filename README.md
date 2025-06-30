# Habit Tracker App

A simple command-line habit tracking application built for the OOFPP module.

## 📦 Project Structure

```
habit-tracker/
├── app/
│   ├── habit.py         # Habit class and save/load functions
│   ├── analytics.py     # Analytics using functional programming
│   └── tests/           # Unit tests (coming next!)
├── main.py              # CLI interface
├── habits.json          # Saved data
├── README.md            # Project description
└── .gitignore           # Ignored files and folders
```

## 🚀 Features

- Create daily or weekly habits
- Mark habits as completed
- View all created habits and their completions
- Show analytics: daily/weekly count, most completed habit
- Save/load habit data using JSON
- Periodicity-based streak tracking (in progress)
- Pre-filled test data (4 weeks)
- Unit testing (coming up)

## 🛠 How to Run

```bash
python main.py
```

Make sure you have Python 3 installed.

## 🧪 Testing

Tests will be placed in `/app/tests/test_app.py` and run with:

```bash
python -m unittest discover app/tests
```

## 👩‍💻 Author

Niama Baqqali  
OOFPP Portfolio – Final Phase  

