# Blackjack-Casino
🎰 A Python-based Blackjack Casino Game featuring a modern black-and-gold CustomTkinter GUI, SQLite database integration for user login and game history, and secure bcrypt password encryption

📁 Project Structure

Blackjack-Casino-GUI/
│
├── main.py                 # GUI and game flow using CustomTkinter
├── database.py             # SQLite database for login and game history
├── blackjack_logic.py      # Core blackjack logic and scoring system
├── requirements.txt        # Dependencies (customtkinter, bcrypt, pillow)
│
├── assets/                 # Contains images and optional logo
│   ├── cards/              # Folder for 52 card images (PNG format)
│   └── screenshots/        # Folder for GUI screenshots (optional)
│
└── blackjack_casino.db     # Auto-created SQLite database file after first run

🎮 Full GUI using CustomTkinter (black and gold casino theme)

🔐 Secure login/signup system (passwords hashed using bcrypt)

🃏 Classic Blackjack gameplay with realistic rules

💾 SQLite integration to save and view game history

🖼️ Support for card images (auto-drawn placeholders if missing)

⚙️ Installation & Setup
# Clone this repository
git clone https://github.com/YourUsername/Blackjack-Casino-GUI.git

# Navigate to project directory
cd Blackjack-Casino-GUI

# Create virtual environment (recommended)
python -m venv venv

# Activate it
venv\Scripts\activate      # Windows
source venv/bin/activate   # macOS/Linux

# Install dependencies
pip install -r requirements.txt

# Run the game
python main.py


🧾 Dependencies
customtkinter
bcrypt
Pillow

🏁 How It Works

User signs up or logs in securely (passwords are hashed).

After login, user navigates from the Main Menu to start the game or view previous results.

The Blackjack Game follows standard casino rules:

Player can Hit or Stand.

Dealer auto-draws until reaching a score ≥17.

Final result (WIN/DRAW/LOSS) is stored in the database.

Game History tab displays previous scores, dealer scores, and timestamps.

🧩 Future Enhancements

Add sound effects & animations.

Include bet system with virtual chips.

Add multiplayer support via socket or web integration.

👨‍💻 Author

Sujay J
B.E – Artificial Intelligence and Data Science
Maharaja Institute of Technology Mysore

🏷️ License

This project is open-source under the MIT License.
You’re free to modify and distribute with proper attribution.

