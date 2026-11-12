# 📚 Pages You Might Like – Recommendation System

A Python-based recommendation system that suggests pages to users based on their shared interests and liked pages.

## 🚀 Project Overview

**Pages You Might Like** is a simple recommendation system that analyzes users' liked pages and identifies common interests between users.

It recommends new pages based on how many interests a user shares with other users in the dataset.

The project demonstrates the basic working principles of a recommendation algorithm using Python and JSON data.

## ✨ Features

- 📊 Loads user and page information from a JSON dataset.
- 👥 Analyzes users' liked pages.
- 🔍 Identifies common interests between users.
- 🎯 Recommends pages that users haven't liked yet.
- 📈 Ranks recommendations based on shared interests.
- ⚡ Uses Python dictionaries and sets for efficient data processing.

## 🛠️ Technologies Used

- **Python** – Core programming language.
- **JSON** – Data storage and management.
- **Data Structures** – Dictionaries, lists, and sets.
- **Recommendation Logic** – Common-interest-based recommendations.

## 📁 Project Structure

```text
Pages_You_Might_Like/
│
├── page_you_like.py    # Main recommendation algorithm
├── data.json           # User and page dataset
└── README.md           # Project documentation
```

## ⚙️ How It Works

1. Loads user and page information from `data.json`.
2. Extracts the pages liked by each user.
3. Finds common liked pages between the selected user and other users.
4. Identifies pages that the selected user hasn't liked.
5. Calculates recommendation scores using shared interests.
6. Sorts the recommended pages based on their scores.

## 💻 Installation & Setup

**1. Clone the repository**

```bash
git clone https://github.com/jayprakashbiswa49-pixel/Pages_You_Might_Like.git
```

**2. Navigate to the project directory**

```bash
cd Pages_You_Might_Like
```

**3. Run the Python program**

```bash
python page_you_like.py
```

## 📌 Example

The program uses User ID `1` (Amit) as the example user.

```python
user_id = 1
page_recommendations = find_pages_you_might_like(user_id, data)
print(f"Pages You Might Like for User {user_id}: {page_recommendations}")
```

## 🎯 Learning Outcomes

Through this project, I practiced:

- Python functions and loops.
- Working with JSON files.
- Dictionaries, lists, and sets.
- Set operations and intersections.
- Sorting data using custom keys.
- Implementing basic recommendation logic.

## 🔮 Future Improvements

- Display recommended page names instead of IDs.
- Build a user-friendly web interface.
- Add recommendation scores and ranking.
- Use a larger real-world dataset.
- Develop more advanced recommendation algorithms.

## 👨‍💻 Author

**Jayaprakash Biswal**

- GitHub: [@jayprakashbiswa49-pixel](https://github.com/jayprakashbiswa49-pixel)
- LinkedIn: [Jayaprakash Biswal](https://www.linkedin.com/in/jayaprakash-biswal-bb1937414/)

---

⭐ If you find this project interesting, consider giving it a star!
