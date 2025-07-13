 💻 AbinayaTask-3: Real-Time Collaborative Editor

This project is a **real-time collaborative text editor** built with **Node.js**, **Express.js**, and **Socket.IO** to enable multiple users to edit text **simultaneously** with WebSocket technology.

## 🚀 Features

* ✅ Real-time multi-user text editing
* ✅ Built using **Express.js** and **Socket.IO**
* ✅ Runs on **Node.js server**
* ✅ Simple, clean server setup


## 📁 Project Structure

```
collab-tool/
 ├── package.json
 ├── package-lock.json
 ├── server.js
 └── public/
      ├── index.html
      ├── script.js
      └── style.css

## 🛠️ Dependencies

From **package.json**:

* **express:** ^5.1.0
* **socket.io:** ^4.8.1

---

## ⚙️ Getting Started

### 🔧 Installation

In the project directory, you can run:

1. **Clone the repository**

   ```bash
   git clone <your-repo-link>
   cd collab-tool
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Run the app**

   ```bash
   node server.js
   ```

4. **Open in browser**

   * Visit [http://localhost:3000](http://localhost:3000) to view it.
   * Open in **multiple tabs or devices** to test real-time updates.

---

## ✏️ Usage

* The server (`server.js`) uses **Express** to serve static files from the `public` folder.
* **Socket.IO** listens for `contentChange` events from any client and broadcasts the updated content to all other connected clients instantly.

---

## 💡 Future Improvements

* Add user authentication
* Save and load documents from database
* Add collaborative whiteboard functionality

---

## 👩‍💻 Author

**Abinaya M**

---

## 📜 License

This project is licensed under the **ISC License**.

---

> Built with ❤️ for **CodTech Internship Task-3 Submission**

