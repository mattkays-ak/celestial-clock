# ☀️ Celestial Clock 🌍 🌙

An interactive, real-time web visualization depicting a top-down view of the Sun-Earth-Moon orbital system.

Built with plain HTML, CSS, and pure JavaScript (HTML5 Canvas), this lightweight web app maps the relative positions of the Earth and Moon as they orbit the Sun, providing dynamic astronomical insights and interactive time-scrubbing controls.

---

## ✨ Features

* **Real-Time Astronomical Orbital Map:**
  * **Sun & Cardinal Solstices/Equinoxes:** Visual markers for the *Winter Solstice*, *Spring Equinox*, *Summer Solstice*, and *Fall Equinox*.
  * **Earth's Orbit:** Dynamic position calculations based on the current day of the year.
  * **Lunar Orbit & Phase:** Realistic Moon positioning relative to Earth and lit-hemisphere orientation toward the Sun.

* **Interactive Time Controls:**
  * **Play / Pause / Reverse / Fast-Forward:** Scrub through time forward or backward to observe seasonal solar arc changes and monthly lunar phases.
  * **Variable Simulation Speeds:** Adjust time progression from **1x (Real-time)** up to **1 Month per second**.
  * **Live Reset Button:** Instantly snap back to the exact current time in AKDT (Alaska Daylight Time).

* **Side-Panel Moon Report:**
  * Displays the exact date and current time.
  * Renders a rendered 2D canvas of the current Moon phase graphic.
  * Displays the calculated **Moon Phase Name** and **Illumination Percentage**.

---

## 🛠️ Built With

* **HTML5 Canvas:** Custom 2D vector rendering for both the top-down orbital system and the moon phase graphic.
* **Vanilla JavaScript:** Zero external dependencies or frameworks—uses standard trigonometric orbital geometry and lunar cycle math ($29.53$ day synodic period).
* **Google Fonts:** *Plus Jakarta Sans* and *JetBrains Mono* for layout typography.

---

## 🚀 Live Demo & Deployment

You can host this project for free using **GitHub Pages**:

1. Ensure `index.html` is committed to the `main` branch of your repository.
2. In your repository on GitHub, go to **Settings** > **Pages**.
3. Under **Build and deployment**, set the **Branch** to `main` and folder to `/ (root)`.
4. Click **Save**. Within 1–2 minutes, your live site will be available at:
   `https://<your-username>.github.io/<your-repo-name>/`

---

## 📁 Repository Structure

```text
├── index.html     # Complete application code (HTML, CSS, and JS)
└── README.md      # Documentation and overview
