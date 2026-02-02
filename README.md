# 🏆 FPL Analizer

[![FPL](https://img.shields.io/badge/Fantasy-Premier%20League-38003c?style=for-the-badge&logo=premier-league&logoColor=white)](https://fantasy.premierleague.com/)
[![PHP](https://img.shields.io/badge/PHP-7.4+-777bb4?style=for-the-badge&logo=php&logoColor=white)](https://www.php.net/)
[![MySQL](https://img.shields.io/badge/MySQL-Database-4479A1?style=for-the-badge&logo=mysql&logoColor=white)](https://www.mysql.com/)

A comprehensive **Fantasy Premier League (FPL)** toolkit designed for serious managers. Built with PHP, this suite of tools provides live data tracking, AI-powered team optimization, and deep performance analysis.

---

## 📸 Screenshots

![Premier League Header](pl.1.png)
*Modern, clean UI focused on player data and team management.*

---

## ✨ Key Features

### 🤖 AI-Powered Assistants
Dominate your league with advanced algorithms:
- **AI Captain Advisor**: Data-driven captaincy recommendations.
- **AI Team Picker**: Optimizes your squad for long-term returns.
- **AI Wildcard & Free Hit Pickers**: Custom team builds for your biggest chips.
- **AI Team Improver**: Suggests the best transfers to strengthen your squad.
- **Point Predictor**: Forecasts player scores for upcoming Gameweeks.

### 🛠 Team & Strategy Tools
- **Live Dashboard**: Real-time points tracking and squad performance.
- **Team Analyzer & Rating**: Evaluates your squad's strength and identifies weaknesses.
- **Chip Strategy Planner**: Map out when to use your Wildcard, Triple Captain, and more.
- **Transfer Planner**: Detailed transfer simulation and impact assessment.

### 📊 Data & Insights
- **Live Scores & Fixtures**: Real-time match updates and detailed FDR (Fixture Difficulty).
- **Price Changes & Predictor**: Track player values and get ahead of the market.
- **Expert Reveals**: See how top managers are setting up their squads.
- **Player Comparison**: Side-by-side analysis of key FPL assets.

### 🛡 Core Security
- **Secure Authentication**: Robust login/logout system with session management.
- **Advanced Security**: Integrated rate limiting, CSRF protection, and input sanitization.

---

## 💻 Tech Stack

- **Backend**: PHP 7.4+
- **Frontend**: Bootstrap 5, Vanilla CSS, Google Fonts (Outfit)
- **Database**: MySQL / MariaDB
- **Icons**: Bootstrap Icons
- **APIs**: Official FPL API Integration

---

## 🚀 Installation Steps

### 1. Prerequisites
- **PHP 7.4** or higher
- **MySQL/MariaDB**
- **Web Server** (Apache/Nginx or PHP built-in server)

### 2. Setup
1. **Clone the repository**:
   ```bash
   git clone https://github.com/Prasann62/fpl-analizer.git
   cd fpl-analizer
   ```

2. **Configure Environment**:
   - Create a `.env` file in the `config/` directory.
   - Use `config/.env.example` as a template:
     ```env
     DB_HOST=localhost
     DB_USERNAME=your_username
     DB_PASSWORD=your_password
     DB_NAME=your_db_name
     ```

3. **Initialize Database**:
   - Create a new database in MySQL.
   - Ensure your `.env` credentials match the created database.

4. **Run the Application**:
   - If using the PHP built-in server:
     ```bash
     php -S localhost:8000
     ```
   - Open your browser and navigate to `http://localhost:8000`.

---

## 🤝 Contributing

Contributions are welcome! If you have suggestions or want to add a feature:

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📝 License

Distributed under the MIT License. (Current repository state: No License).

---

## 📧 Contact

**Prasanna Kumar** - Project Link [https://github.com/Prasann62/fpl-analizer](https://github.com/Prasann62/fpl-analizer)

*Built with ❤️ for FPL fans everywhere.*
