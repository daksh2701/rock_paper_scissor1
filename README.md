# 🎮 Rock Paper Scissors Arena

A modern, interactive Rock Paper Scissors game built with Streamlit featuring a beautiful UI, real-time scoring, game statistics, and match history.

![Rock Paper Scissors Arena](https://img.shields.io/badge/Game-Rock%20Paper%20Scissors-blue)
![Streamlit](https://img.shields.io/badge/Built%20with-Streamlit-red)
![Python](https://img.shields.io/badge/Python-3.7%2B-green)

## 🌟 Features

- **Interactive Gameplay**: Click buttons to make your choice against the computer
- **Beautiful UI**: Modern design with gradients, animations, and responsive layout
- **Real-time Scoring**: Track wins, losses, ties, and win percentage
- **Game Statistics**: Visual progress bars and performance metrics
- **Match History**: Review your last 10 games with timestamps
- **Mobile Responsive**: Optimized for both desktop and mobile devices
- **Smooth Animations**: Engaging bounce and fade effects
- **Game Rules**: Built-in expandable rules section

## 🎯 Game Rules

- 🪨 **Rock** crushes ✂️ **Scissors**
- 📄 **Paper** covers 🪨 **Rock**  
- ✂️ **Scissors** cuts 📄 **Paper**

## 🚀 Getting Started

### Prerequisites

Make sure you have Python 3.7 or higher installed on your system.

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/rock-paper-scissors-arena.git
   cd rock-paper-scissors-arena
   ```

2. **Install required dependencies**
   ```bash
   pip install streamlit
   ```

   Or if you have a requirements.txt file:
   ```bash
   pip install -r requirements.txt
   ```

### 🏃‍♂️ Running the Application

To run the Rock Paper Scissors Arena on your localhost:

```bash
streamlit run app.py
```

**Note**: This application is built with Streamlit and is designed to run on localhost. After running the command above, Streamlit will automatically open your default web browser and navigate to `http://localhost:8501` where you can play the game.

The terminal will display:
```
You can now view your Streamlit app in your browser.

Local URL: http://localhost:8501
Network URL: http://192.168.x.x:8501
```

## 📁 Project Structure

```
rock-paper-scissors-arena/
│
├── app.py                 # Main Streamlit application
├── README.md             # Project documentation
├── requirements.txt      # Python dependencies (optional)
└── .gitignore           # Git ignore file (optional)
```

## 🎮 How to Play

1. **Launch the game** by running the Streamlit command
2. **Choose your weapon** by clicking one of the three buttons:
   - 🪨 Rock
   - 📄 Paper
   - ✂️ Scissors
3. **View the battle** as your choice faces off against the computer's random selection
4. **Check your results** and see if you won, lost, or tied
5. **Track your progress** with the real-time scoring system
6. **Review your history** in the "Recent Games" section

## 🎨 Features Breakdown

### Visual Elements
- **Custom CSS styling** with gradients and shadows
- **Smooth animations** for choice reveals and results
- **Responsive design** that works on all screen sizes
- **Professional color scheme** with modern aesthetics

### Game Mechanics
- **Random computer selection** for fair gameplay
- **Persistent score tracking** throughout your session
- **Win rate calculation** and performance metrics
- **Game history storage** (last 10 games)

### User Interface
- **Intuitive button layout** for easy selection
- **Clear result display** with emoji indicators
- **Expandable sections** for rules and history
- **Reset functionality** to start fresh anytime

## 📊 Statistics Tracked

- Total wins, losses, and ties
- Overall win percentage
- Performance indicators and encouragement messages
- Timestamped game history
- Visual progress bars for win rate

## 🛠️ Technologies Used

- **Python 3.7+**
- **Streamlit** - Web application framework
- **HTML/CSS** - Custom styling and animations
