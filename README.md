# WIKIBot

**WIKIBot** is an intelligent assistant developed during **Cliqtrix 2025 – A Coding Contest by Zoho**.  
It is designed to fetch concise, accurate, and reliable information directly from **Wikipedia**, allowing users to access knowledge instantly through a simple chat interface.


<p align="center">
  <img src="https://oweb.zohowebstatic.com/sites/oweb/images/cliqtrix/cliqtrix-banner.jpg" width="50%" height="2%">
</p>

---

## Features

- 🔍 **Quick Search:** Instantly retrieve Wikipedia summaries using `/Wiki(topic)`  
- 🧾 **Concise Answers:** Delivers short and focused explanations  
- 🖼️ **Card-Based Display:** Presents information neatly with optional thumbnails  
- 🆘 **Help Command:** Guides users on how to interact with the bot  
- ⚙️ **Smart Error Handling:** Handles invalid or missing queries gracefully  
- 🌐 **Reliable Source:** Fetches verified data directly from Wikipedia’s API  

<img src="https://cdn.dribbble.com/userupload/32122583/file/original-400827bdf243931c8ffd26a268a837ce.gif" width="60%" height="10%">



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

<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRuZWVgq2wX-FXyhw2TJ1tTG4hoQ3QNUVcchg&s" width="60%" height="10%">

This project was created as part of  
**Cliqtrix 2025 – A Coding Contest by Zoho**,  
focusing on creativity, innovation, and practical problem-solving using **Zoho Cliq Bots**.

---

### _“Learn smarter with every command — WIKIBot makes Wikipedia simple and accessible!”_

