# 🧩 Frontend–Backend Demo (Exercise 1)

A simple HTML + JavaScript page that demonstrates how the **frontend** communicates with a **backend API** to display live data.

---

## 🎯 Learning Objectives
- Understand the difference between **frontend**, **backend**, and **database** layers.  
- See how a browser fetches data from a public API.  
- Modify HTML structure and JavaScript logic safely.  
- Practice reasoning about what code does — not just copying it.

---

## 🧠 Concepts Overview
| Layer | Role | Example |
|-------|------|----------|
| **Frontend** | What the user sees (HTML, CSS, JS) | This web page |
| **Backend** | Logic & APIs providing data | `https://api.chucknorris.io` |
| **Database** | Stores information | Not used here, but APIs usually talk to one |

When you click the **Get Joke** button, your browser (frontend) sends a request to a public backend API.  
The API replies with JSON data → JavaScript extracts the `value` field and displays it in the page.

---

## 🧱 Project Structure

---

## 🚀 How to Run
1. Open this project in **StackBlitz**, **Replit**, or any browser.  
2. Press **Run** or simply open `index.html`.  
3. Click **“Get Joke”** to see a random Chuck Norris joke appear.  
4. Open the **Browser Console** (`F12 → Console`) to view logs or errors.

---

## ✅ Your Tasks
### A. Structure & Content
- [ ] Add your **name** in the `<header>` (e.g., “Frontend–Backend Demo – by Maria Ivanova”).  
- [ ] Add a **`<footer>`** with the current year.  
- [ ] Add an **image** (`<img>`) below the joke box using [https://picsum.photos/200](https://picsum.photos/200).  
- [ ] Add a **link** to the API page (https://api.chucknorris.io).  
- [ ] Add a short **paragraph** explaining what happens when the button is clicked.

### B. Enhancement (optional)
- [ ] Change the joke box style (`#joke`) — new color, border, or font.  
- [ ] Add a second button that loads **two jokes** and displays them as a list.  
- [ ] Show a ✅ “Success” or ❌ “Error” message after each fetch.

### C. Reflection (write in a comment or separate file)
Answer in 2–3 sentences each:
1. What part of this code is the **frontend**?  
2. What is the **backend** here?  
3. What format does the API return?  
4. What does `await fetch()` do?  
5. How could an AI assistant help you understand or extend this code?

---

## 💡 Bonus Challenge
Replace the Chuck Norris API with another public one, such as:
- `https://api.adviceslip.com/advice`
- `https://api.kanye.rest/`

Update the text and layout so the page becomes a **Quote of the Day** or **Random Fact** generator.

---

## 🧾 Submission
- Push your finished file to your repository **o**
