# 🍽️ Calorie Counter

An interactive calorie tracking web app built with **HTML**, **CSS**, and **JavaScript**.  
Users can log meals and exercises, calculate their remaining calories, and instantly see whether they are in a **caloric surplus** or **caloric deficit**.

---

## 📋 Features

- **Daily Calorie Budget**: Set a daily calorie allowance.
- **Meal & Exercise Logging**: Add multiple entries for breakfast, lunch, dinner, snacks, and exercise.
- **Dynamic Form**: Add as many food or exercise entries as needed.
- **Real-Time Calculation**:
  - Calculates consumed, burned, and remaining calories.
  - Detects if you are in **Surplus** (ate more than budget) or **Deficit** (ate less than budget).
- **Input Validation**:
  - Cleans input values to avoid invalid characters.
  - Prevents invalid scientific notation (e.g. `2e10`).
- **Clear Functionality**: Reset the form and start fresh with one click.
- **Dynamic Styling**:  
  - Surplus calories → highlighted in **pink**.  
  - Deficit calories → highlighted in **green**.  

---


## 🚀 How It Works

1. **Set a Budget**:  
   Enter your daily calorie budget at the top of the form.

2. **Add Entries**:  
   - Select a category (Breakfast, Lunch, Dinner, Snacks, or Exercise).  
   - Click **Add Entry** to create new input fields.  
   - Fill in the entry name (e.g. "Pizza") and calories.

3. **Calculate**:  
   - Click **Calculate Remaining Calories**.  
   - The app sums up your meals, subtracts from budget, adds burned exercise calories.  
   - The result is shown in the **Output box**, colored based on surplus or deficit.

4. **Clear**:  
   - Reset all inputs and start again with the **Clear** button.

---


## 📚 Key JavaScript Concepts Demonstrated

- **DOM Manipulation**  
  - `querySelectorAll`, `insertAdjacentHTML`, `innerHTML`  
- **Event Handling**  
  - `addEventListener("click", ...)`  
  - `addEventListener("submit", ...)`  
- **Form Validation**  
  - `cleanInputString()` removes invalid characters  
  - `isInvalidInput()` checks for scientific notation  
