# 🎬 Movie Recommendation System

## 📌 Overview
This is a simple Movie Recommendation System built using Python. It suggests similar movies based on a predefined dataset. The project demonstrates the basic concept of recommendation systems in Artificial Intelligence.

---

## 🎯 Aim
To design a basic recommendation system that helps users discover movies of similar type or genre.

---

## 🌟 Why It Matters
Recommendation systems are widely used in platforms like Netflix and Amazon. They:
- Help users find relevant content quickly  
- Improve user experience  
- Save time in decision-making  

---

## ⚙️ Features
- Simple and easy to understand  
- No external libraries required  
- Runs on any online Python compiler  
- Takes user input  
- Shows top 3 recommended movies  
- Handles invalid input  

---

## 🛠️ Technologies Used
- Python (Core Python)

---

## ▶️ How to Run

### Method 1: Online Compiler
1. Open any online Python compiler (Programiz / Replit)
2. Copy the code below
3. Run the program
4. Enter a movie name

### Method 2: Local System
1. Install Python
2. Save file as `main.py`
3. Run:
   python main.py

---

## 💻 Code

```python
movies = {
    "Inception": ["Interstellar", "Matrix", "John Wick"],
    "Interstellar": ["Inception", "Matrix", "The Dark Knight"],
    "The Dark Knight": ["Avengers", "John Wick", "Inception"],
    "Avengers": ["The Dark Knight", "Matrix", "John Wick"],
    "Titanic": ["Notebook", "Inception", "Interstellar"],
    "Notebook": ["Titanic", "Inception", "Interstellar"],
    "John Wick": ["Matrix", "The Dark Knight", "Avengers"],
    "Matrix": ["Inception", "Interstellar", "John Wick"]
}

movie = input("Enter a movie name: ")

if movie in movies:
    print("\n🎬 Recommended Movies:")
    print("------------------------")
    for m in movies[movie]:
        print("👉", m)
else:
    print("\n❌ Movie not found in database!")
```

---

## 🎯 Example Output

Enter a movie name: Inception

🎬 Recommended Movies:
------------------------
👉 Interstellar
👉 Matrix
👉 John Wick

---

## 🧠 Approach
- Created a small dataset of movies  
- Used dictionary for storing data  
- Took user input  
- Matched input with dataset  
- Displayed recommendations  

---

## 🔑 Key Decisions
- Used simple logic instead of ML  
- Avoided external libraries  
- Used predefined dataset  
- Limited output to 3 results  

---

## ⚠️ Challenges
- Creating dataset  
- Handling invalid input  
- Keeping project simple  
- Making it run everywhere  

---

## 📚 Learning Outcomes
- Basics of recommendation systems  
- Python dictionaries  
- Input handling  
- Conditional statements  
- Logical thinking  

---

## 🚀 Future Improvements
- Add more movies  
- Use machine learning  
- Create GUI  
- Improve accuracy  

---

## 👩‍💻 Author
Sanskruti Kanoje
