
# 🥗 Personalized Nutrition Recommendation Engine

A Java-based application that generates **personalized meal recommendations** by analyzing a user's calorie requirements, dietary preferences, and dietary restrictions. The project demonstrates the practical application of **Object-Oriented Programming (OOP)** and **Data Structures** by using a **Binary Search Tree (BST)** to efficiently organize user profiles and generate customized meal plans.

---

# 📖 Table of Contents

- Project Overview
- Objectives
- Features
- Technologies Used
- System Architecture
- Project Structure
- Working Methodology
- Data Structures Used
- Installation
- Usage
- Sample Output
- Future Enhancements
- Author
- License

---

# 📌 Project Overview

Healthy eating is essential for maintaining a balanced lifestyle, but selecting meals that satisfy nutritional needs and dietary preferences can be difficult. This project addresses that challenge by recommending meals that align with each user's profile.

Each user provides:
- Name
- Age
- Dietary Preference
- Daily Calorie Requirement
- Dietary Restrictions

The system compares these details against a predefined meal database and generates a personalized meal plan consisting of breakfast, lunch, and dinner.

---

# 🎯 Objectives

- Build a personalized nutrition recommendation system.
- Demonstrate Object-Oriented Programming concepts.
- Implement Binary Search Tree operations.
- Recommend meals based on calorie limits and dietary restrictions.
- Improve understanding of Java Collections and searching algorithms.

---

# ✨ Features

- 👤 Create and manage multiple user profiles.
- 🌱 Supports Vegan and Vegetarian meal categories.
- 🍽️ Automatically generates breakfast, lunch, and dinner plans.
- 🔥 Filters meals according to calorie requirements.
- 📊 Displays nutritional information such as calories, protein, and carbohydrates.
- 🌳 Stores user profiles in a Binary Search Tree for efficient organization.
- 🧩 Modular design using separate classes for different functionalities.

---

# 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| Java | Programming Language |
| OOP | Code Organization |
| Java Collections | Managing Lists |
| Binary Search Tree | User Profile Storage |
| Arrays & Lists | Meal Database |

---

# 🏗️ System Architecture

```text
User Profile
      │
      ▼
Binary Search Tree
      │
      ▼
Meal Database
      │
      ▼
Meal Matching Algorithm
      │
      ▼
Personalized Meal Plan
```

---

# 📂 Project Structure

```text
Main.java
│
├── UserProfile
├── Meal
├── MealPlan
├── BSTNode
├── DietaryBST
└── MealPlanner
```

---

# ⚙️ Working Methodology

### Step 1: User Registration

The application creates user profiles containing:
- Name
- Age
- Dietary Preference
- Calorie Requirement
- Dietary Restrictions

### Step 2: Profile Storage

Each profile is inserted into a Binary Search Tree based on calorie requirements, enabling efficient organization and traversal.

### Step 3: Meal Matching

The system compares user preferences with the available meal database and filters meals that satisfy:
- Calorie requirement
- Dietary category
- Dietary restrictions

### Step 4: Meal Plan Generation

The first suitable meals are assigned as:
- Breakfast
- Lunch
- Dinner

The final meal plan is then displayed.

---

# 🌳 Data Structures Used

## Binary Search Tree (BST)

The BST stores user profiles according to calorie requirements.

### Advantages

- Faster searching
- Efficient insertion
- Sorted traversal
- Better organization of user profiles

---

# 🚀 Installation

## Prerequisites

- Java JDK 8 or above
- VS Code / Eclipse / IntelliJ IDEA

## Compile

```bash
javac Main.java
```

## Run

```bash
java Main
```

---

# 💻 Sample Output

```text
Inorder Traversal of Profiles

User: Sathwik
User: Dheeraj
User: Deekshith

Meal Plan for Sathwik
Breakfast : Oatmeal
Lunch : Salad
Dinner : Smoothie
```

---

# 📚 OOP Concepts Used

- Classes and Objects
- Encapsulation
- Constructors
- Object Composition
- Method Invocation

---

# 🌟 Future Enhancements

- Integrate a nutrition database.
- Read meal information from CSV files or databases.
- Add BMI and BMR calculations.
- Support diabetic, keto, gluten-free, and high-protein diets.
- Develop a GUI using JavaFX or Swing.
- Store user data in MySQL.
- Integrate machine learning for intelligent meal recommendations.
- Connect with external nutrition APIs.

---

# 👨‍💻 Author

**Deekshith Peddi**

GitHub: https://github.com/DEEKSHITH-PEDDI

---

# 📄 License

This project is developed for educational and academic purposes.

---

⭐ If you found this project helpful, consider giving it a **Star** on GitHub!
