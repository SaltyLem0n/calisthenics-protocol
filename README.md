# **Calisthenics Corps: 30-Day Protocol 🏋️‍♂️💻**

**Op: Reclamation** — A tactical, single-page application (SPA) designed to rebuild fitness baselines while maintaining productivity for developers.

## **📋 Mission Briefing**

This application is a specialized tool for individuals balancing a rigorous 30-day calisthenics transformation with a sedentary coding job. It combines military-style discipline with developer-friendly ergonomics.

**Target:** Drop weight (68kg → 60kg), increase relative strength, and maintain high cognitive function.

## **⚡ Key Features**

### **1\. The Dashboard (Command Center)**

* **Live Weight Tracker:** Log daily weigh-ins and visualize the trajectory against your 60kg goal.  
* **Hydration Control:** Track 250ml increments of water (crucial for Creatine users). Includes (+) and (-) controls to prevent logging errors.  
* **Supplement Stack:** Daily toggles for Zinc and Creatine adherence.  
* **Soldier Stats:** A radar chart visualizing your current attributes (Strength, Endurance, Mobility, Discipline).

### **2\. The Protocol (Workout Manager)**

* **4-Phase Progressive Overload:**  
  * Week 1: Foundation (Form Focus)  
  * Week 2: Volume (Reps)  
  * Week 3: Intensity (Variations)  
  * Week 4: Peak (Test)  
* **Interactive Checkboxes:** Mark days as complete to save progress to local storage.  
* **Form Cues:** Click any workout day to see specific execution tips.

### **3\. Tactical Tools**

* **Combat Timer:** A floating, draggable stopwatch with Play/Pause/Reset controls for planks and rest periods.  
* **"Spine Saver" Mode:** A sidebar timer for developers. Runs a 55-minute "Code Sprint" followed by a mandatory decompression break (Dead Hangs/Stretching).

### **4\. Data HQ (Sync System)**

* **Offline First:** All data is stored in your browser's Local Storage.  
* **Cross-Device Sync:**  
  * **Export JSON:** Download your full history from your phone.  
  * **Import JSON:** Upload that file to your PC to view charts on a larger screen.  
  * **Export CSV:** Export weight data for analysis in Excel or Google Sheets.

## **🚀 Installation & Usage**

### **Option A: The "Cloud" Way (Recommended for Phones)**

1. Fork or Clone this repository.  
2. Go to **Settings** \> **Pages**.  
3. Set the source to main branch and save.  
4. Open the provided link on your mobile browser (Safari/Chrome).  
5. **Tap "Share" \> "Add to Home Screen"** to install it as an App.

### **Option B: The "Local" Way (Offline)**

1. Download the index.html file.  
2. Open it in any web browser (Chrome, Edge, Safari).  
3. No internet required (except for loading Tailwind/Chart.js scripts initially).

## **💾 Data Management Workflow**

Since this is a serverless application, your data lives on your device. To keep your Phone and Computer in sync:

1. **On Phone:** Go to **Data HQ** \> Tap **"Download Full Backup"**.  
2. Send the downloaded .json file to your Computer.  
3. **On Computer:** Open the App \> Go to **Data HQ** \> Tap **"Upload Backup"**.  
4. Select the file. Your phone's progress is now mirrored on your PC.

## **🛠 Tech Stack**

* **Core:** Vanilla HTML5, JavaScript (ES6+).  
* **Styling:** Tailwind CSS (via CDN).  
* **Visualization:** Chart.js (via CDN).  
* **Storage:** Browser localStorage API.

*"Discipline is freedom."*