# 🎵 Java Music Platform  

A **Java-based music platform** that provides an interactive interface for exploring, searching, and managing media files such as audio, video, images, and text. The application is built using **Swing for GUI** and supports various media management functionalities.  

---

## 📌 Features  
✅ **Browse & Search** – Users can explore and manage a collection of media files.  
✅ **Graphical User Interface (GUI)** – Built with **Swing**, featuring an intuitive interface.  
✅ **User Authentication** – Includes **Login, Logout, and Password Change** functionalities.  
✅ **Media Management** – Handles **audio, video, images, and text** files dynamically.  
✅ **Commenting System** – Users can **comment on different media types**.  
✅ **Serialization Support** – Saves and loads media files using **object serialization**.  

---

## 🛠 Technologies Used  
- **Programming Language:** Java  
- **GUI Framework:** Swing  
- **Serialization:** Java Object Streams (`.ser` files)  
- **Event Handling:** Java ActionListeners  

---

## 🚀 How to Run the Project  

### **1️⃣ Prerequisites**  
Ensure you have:  
- Java **JDK 11 or later** installed.  
- An IDE such as **IntelliJ IDEA, Eclipse, or VS Code**.  

### **2️⃣ Clone the Repository**  
```sh  
git clone https://github.com/MariaChmite/MusicPlatform.git  
cd MusicPlatform  
```

### **3️⃣ Compile & Run**  
#### **Using Command Line**  
```sh  
javac -d bin -cp src src/defaultpck/main.java  
java -cp bin defaultpck.main  
```

#### **Using an IDE (Eclipse/IntelliJ)**  
1. Open the project in your IDE.  
2. Set `main.java` as the main class.  
3. Run the project.  

---

## 📂 Project Structure  
```
📂 MusicPlatform/
  📂 javafolder/
    📜 .classpath
    📜 .project
    📂 data/
      📜 audioList.ser
      📜 imageList.ser
      📜 textList.ser
      📜 videoList.ser
    📂 defaultpck/
      📜 main.java
      📜 menu.java
    📂 metadata/
      📜 audio.java
      📜 comments.java
      📜 image.java
      📜 media.java
      📜 Texto.java
      📜 video.java
    📂 metadatagroup/
      📜 album.java
      📜 playlist.java
    📂 user/
      📜 creator.java
      📜 guest.java
      📜 ids.java
      📜 staff.java
      📜 user.java
```

---

## 👥 Contributors  
- **Maria Chmite** - [@MariaChmite](https://github.com/MariaChmite)  
- **Salim El Ghersse** - [@SalimElGhersse](https://github.com/SalimElGhersse)  
- **Nouamane Zanboui**  
- **Jad Falaq**  

🔥 Special thanks to all contributors for their efforts in developing this project!  

---

## 📜 License  
This project is **open-source** and free to use. Contributions are welcome! 🚀  

---

## 📫 Connect With Us  
💡 **Maria Chmite** – [GitHub](https://github.com/MariaChmite) | [LinkedIn](https://linkedin.com/in/maria-chmite)  
💡 **Salim El Ghersse** – [GitHub](https://github.com/SalimElGhersse)  
💡 **Nouamane Zanboui** 
💡 **Jad Falaq**  

---

🎉 **Enjoy coding & keep innovating!** 🚀
