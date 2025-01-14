# UnrealScreenshot 🎮📸  

**Your ultimate Unreal Engine plugin for snapping jaw-dropping screenshots!**  
Whether you're capturing cinematic moments, debugging your game on multiple displays, or simply want to show off your work, **UnrealScreenshot** makes it easy, customizable, and fun. Say goodbye to boring screenshots—this plugin is your new best friend in Unreal Engine 5.1. 🚀

---

## 📢 Features  

### 🌟 **Capture Like a Pro**
- Take screenshots **on any connected display**—just point and snap!  
- Choose to include or exclude the **UI overlay** for cleaner shots.  

### 🗂️ **Stay Organized**
- Save your screenshots to **custom directories**, keeping your work neat and tidy.  

### 🛠️ **Built for Blueprint Wizards**
- Fully **Blueprint-accessible functions** for seamless integration into your game.  

### ⚡ **Fast and Reliable**
- Asynchronous tasks ensure your game keeps running smoothly while screenshots are saved in the background.  

---

## 🖥️ How It Works  

### 🛠️ Install the Plugin  
1. **Clone or download** the repository.  
2. Copy the `UnrealScreenshot` folder to your Unreal Engine project's `Plugins` directory.  
3. Restart Unreal Engine.  
4. Enable the plugin in the **Plugins Manager**.  

### 🎨 Use It Your Way  

#### **Blueprint Functions**  

1. **`TakeScreenshot`**  
   Snap a screenshot with your chosen name and UI visibility!  
   - **Parameters**:  
     - `BaseName` (String): Name your masterpiece.  
     - `bShowUI` (Bool): Show or hide the UI.

2. **`SetScreenshotDirectory`**  
   Where do you want your screenshots? You decide.  
   - **Parameters**:  
     - `Directory` (String): The path to save your art.

3. **`TakeScreenshotOnDisplay`**  
   Got multiple monitors? Capture any display with ease.  
   - **Parameters**:  
     - `BaseName` (String): Give it a name.  
     - `bShowUI` (Bool): Include the UI?  
     - `DisplayID` (Int): Select your screen.

4. **`TakeScreenshotOnGameThread`**  
   Need precision? Take a screenshot on the **main game thread**.  
   - **Parameters**: Same as `TakeScreenshotOnDisplay`.

#### **Console Commands**  

- `shot`: Capture the default screenshot with just a word.  
- `setscreenshotdir <directory>`: Update your screenshot directory on the fly.  
- `shotondisplay <BaseName> <bShowUI> <DisplayID>`: Screenshot magic for any display!  

---

## 📜 License  

This project **does not include a license**, meaning it is protected by default under copyright law.  
- **You are NOT allowed to use, distribute, or modify the code** without explicit permission from the author.  
- If you wish to use this project, please contact the repository owner for more information.  

---

🎮 **Create. Capture. Share.**  
Made with ❤️ for Unreal Engine developers
