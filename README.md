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
