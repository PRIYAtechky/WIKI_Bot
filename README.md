# WIKIBot

**WIKIBot** is an intelligent assistant developed during **Cliqtrix 2025 – A Coding Contest by Zoho**.  
It is designed to fetch concise, accurate, and reliable information directly from **Wikipedia**, allowing users to access knowledge instantly through a simple chat interface.

---

## Overview

WIKIBot provides users with summarized responses in a visually appealing card format, including a direct source link for further exploration.  
It can be integrated into platforms like **Zoho Cliq** to enhance communication and learning experiences.

---

## Features

- 🔍 **Quick Search:** Instantly retrieve Wikipedia summaries using `/Wiki(topic)`  
- 🧾 **Concise Answers:** Delivers short and focused explanations  
- 🖼️ **Card-Based Display:** Presents information neatly with optional thumbnails  
- 🆘 **Help Command:** Guides users on how to interact with the bot  
- ⚙️ **Smart Error Handling:** Handles invalid or missing queries gracefully  
- 🌐 **Reliable Source:** Fetches verified data directly from Wikipedia’s API  

---

## How It Works

1. **User Input:**  
   The user enters a query in the format `/Wiki(Topic)`
    Example: /Wiki(Artificial Intelligence)

3. **Processing:**  
The bot connects to the **Wikipedia REST API** to fetch a brief summary of the topic.

4. **Response:**  
The bot displays:
- A short topic description  
- A clickable Wikipedia source link  
- Optional image or thumbnail if available  

4. **Help Command:**  
Users can type `help` to view usage instructions and examples.

---

## Example Interaction

**User:**  
`/Wiki(Quantum Computing)`

**WIKIBot:**  
> *Quantum Computing is a type of computation that takes advantage of quantum phenomena like superposition and entanglement.*  
>  
> 🔗 [Read more on Wikipedia](https://en.wikipedia.org/wiki/Quantum_computing)

---

## Tech Stack

| Component | Description |
|------------|-------------|
| **Language** | Deluge Script |
| **Platform** | Zoho Cliq |
| **API Used** | Wikipedia REST API |
| **Integration** | `invokeUrl` connection to Wikipedia |

---

## ⚠️ Error Handling

- **Invalid Format:**  
  _“Invalid format. Please use /Wiki(word) to search for a topic.”_

- **No Data Found:**  
  _“Sorry, I couldn’t find any information on that topic. Please try another query.”_

---

## Benefits

- Quick access to trusted information  
- Minimal, distraction-free UI  
- Ideal for students, professionals, and researchers  
- Easy-to-use command structure  
- Seamless integration within Zoho Cliq  

---

## Developer Notes

1. Configure the bot in **Zoho Cliq Developer Console**.  
2. Set up a **connection** with the Wikipedia REST API using `invokeUrl`.  
3. Implement handlers for:
   - Welcome  
   - Message  
   - Mention  
   - Command  
   - Participation  
4. Test commands like `/Wiki(Zoho)` and `help`.

---

##  Project Origin

This project was created as part of  
**Cliqtrix 2025 – A Coding Contest by Zoho**,  
focusing on creativity, innovation, and practical problem-solving using **Zoho Cliq Bots**.

---

### _“Learn smarter with every command — WIKIBot makes Wikipedia simple and accessible!”_

