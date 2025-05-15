Absolutely! Here's a **clean, professional version** of your README in plain text format — with clear headings and bold formatting (using all caps and spacing) so it looks great even without markdown:

---

**AR PROJECT – MARKER-BASED AUGMENTED REALITY PARK SCENE**
(CTSE – Modern Topics in Software Engineering)

This group project showcases a marker-based Augmented Reality (AR) web application developed using **A-Frame** and **AR.js**. The app visualizes a virtual **Park Scene**, where 3D models are triggered through distinct image markers. The experience is enhanced with animation and sound effects for interactivity.

---

**THEME: PARK**

Each group member contributed one 3D object relevant to a typical park environment.

**MEMBER CONTRIBUTIONS:**

* **Member 1** – Tree + Bench
  **Marker**: pattern-tree.patt
  **Feature**: Rotation animation and birds chirping sound

* **Member 2** – Park Bench
  **Marker**: pattern-bench.patt
  **Feature**: Rotation animation and ambient people sound

* **Member 3** – Tent
  **Marker**: pattern-tent.patt
  **Feature**: Bouncing animation and tent flap sound

* **Member 4** – Picnic Basket
  **Marker**: pattern-shopping-basket.patt
  **Feature**: Scaling animation and picnic ambience sound

---

**TECHNOLOGIES USED**

* A-Frame (for rendering 3D scenes)
* AR.js (for marker-based AR tracking)
* Custom .patt image markers
* Local Web Server using Node.js (`local-web-server`)

---

**PROJECT FOLDER STRUCTURE**

```
ar-project/
├── index.html
├── models/              (GLB model files)
├── markers/             (Custom .patt marker files)
├── sound/               (MP3 sound effects)
└── README.txt
```

---

**HOW TO RUN LOCALLY**

1. **Install Node.js** if not already installed:
   Download from [https://nodejs.org/](https://nodejs.org/)

2. **Install Local Web Server** (one-time setup):
   Open terminal and run:
   `npm install -g local-web-server`

3. **Start the Web Server** in your project folder:
   Navigate to the `ar-project` folder in terminal and run:
   `ws --https`

4. **Access the Application**:

   * Copy the HTTPS IP link shown in terminal (e.g., [https://192.168.1.5:8000](https://192.168.1.5:8000))
   * Open it in your mobile browser (Chrome, Firefox, or Samsung Internet)
   * Allow camera access when prompted

---

**HOW TO TEST**

* Display each marker image one at a time (print or show on screen)
* When scanned by the AR camera:

  * A 3D model appears over the marker
  * The assigned animation and sound effect play automatically
* Repeat for all four markers to demonstrate the full scene

---


**NOTES**

* For best results, test on a mobile browser using the same Wi-Fi network as your PC
* Ensure good lighting when scanning printed markers
* Sound may auto-play depending on browser permission settings

---
