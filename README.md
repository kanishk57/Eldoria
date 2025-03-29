# **Eldoria - A Java-Based 2D Adventure Game**

Eldoria is a **Java-based 2D adventure game** where players navigate a world, interact with objects, and progress through levels. The game features dynamic **keyboard-based movement**, **custom maps**, and **collision detection** for an immersive gameplay experience.

---

## **Features**
 **Smooth Character Movement** (WASD / Arrow Keys)  
 **Customizable Game Levels** (Loaded from text-based maps)  
 **Collision Detection** (Prevents walking through walls)  
 **UI Elements** (Health Bar, Score Display)  
 **Interactive Objects & NPCs** (Enemies, Coins, Keys, etc.)  
 **File-Based Level Loading** (Modify `map.txt` to create new levels)  

---

## **🛠Technologies Used**
- **Java Core (OOP Principles)** - Game Logic & Structure  
- **Java Swing & AWT** - UI Rendering & Graphics  
- **Java Collections (ArrayList, HashMap)** - Managing game data  
- **Java File I/O** - Loading maps & saving progress  
- **KeyListener** - Handling keyboard inputs  

---

## **Project Structure**
```
Eldoria/
│── src/
│   │── com.eldoria.main/        # Main Game Engine
│   │── com.eldoria.model/       # Game Logic (Player, Enemies, NPCs, Items)
│   │── com.eldoria.view/        # Graphics & UI
│   │── com.eldoria.controller/  # Input Handling & Game Events
│   │── com.eldoria.map/         # Map & Tile Management
│   │── com.eldoria.utils/       # Utility Functions (Resource Loader, Logger)
│
│── assets/                      # Game Assets (Images, Sounds, Maps)
│── config/                      # Game Configurations
│── README.md                    # Project Documentation
│── Eldoria.jar                   # Compiled Game File
```

---

## **Installation & Running the Game**
### **🔹 Prerequisites**
- Java **JDK 11 or higher** installed on your system  

### **🔹 Steps to Run**
1. **Clone the Repository**
   ```sh
   git clone https://github.com/your-username/Eldoria.git
   cd Eldoria
   ```
2. **Compile the Game**
   ```sh
   javac -d bin src/com/eldoria/main/Game.java
   ```
3. **Run the Game**
   ```sh
   java -cp bin com.eldoria.main.Game
   ```

---

## **Controls**
| Key | Action |
|------|--------|
| `W` / `↑` | Move Up |
| `S` / `↓` | Move Down |
| `A` / `←` | Move Left |
| `D` / `→` | Move Right |
| `ESC` | Quit Game |

---

## **🛠How to Modify the Game**
- **To edit levels**, modify the `map.txt` file inside the `assets/maps/` folder.  
- **To change character sprites**, replace images in `assets/images/`.  
- **To add new NPCs or enemies**, modify `NPC.java` and `Enemy.java`.  

---

## **Contributing**
Want to improve Eldoria? Feel free to fork the project and submit a pull request!

---

## **License**
This project is licensed under the **MIT License**.

---

## **Contact**
For any questions or feature requests, reach out via **GitHub Issues** or email **dhimankanishk21@gmail.com**.

---


