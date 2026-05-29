This `README.md` is designed to match the high-end, technical aesthetic of your project. It includes a feature breakdown, technology stack, and instructions for maintaining the dynamic sections.

***

# 🛰️ EUREKA | Technical Collective
> **"Where Human Intelligence Meets Mechanical Precision."**

A cinematic, high-performance web experience for the **Eureka Technical Club**. This project blends cutting-edge web technologies to create a "Technical Operating System" feel, inspired by sci-fi interfaces and modern engineering aesthetics.

![Eureka Logo](./eureka-logo.png)

## 🌌 Core Features

### 1. Cinematic Visuals
*   **3D Starfield:** An interactive background rendered in real-time using **Three.js**.
*   **Splash Cursor:** A high-performance **WebGL Fluid Simulation** that leaves a trail of "Eureka Gold" ink as you browse.
*   **HUD Interface:** Design elements inspired by Heads-Up Displays, including bracketed corners, scanlines, and monospaced data readouts.

### 2. Advanced Motion
*   **Smooth Scrolling:** Integrated **Lenis** library for weightless, momentum-based scrolling.
*   **Scroll-Triggered Reveals:** GSAP-powered animations that reveal content with cinematic "Expo" easing.
*   **Dynamic Transitions:** Page-to-page transitions that fade to black, simulating a system reboot.

### 3. Professional Sections
*   **Operational Divisions:** Interactive 3D cards for Robotics, AI, and Space Tech.
*   **The Core (Board):** "Cyber-Profile" member cards with hover-activated scanlines.
*   **Operations Center:** Dedicated space for featured upcoming events and a grayscale mission archive.
*   **Hall of Records:** Structured merit section for published research papers and competition awards.

### 4. Dynamic Data Architecture
*   **Universal Template:** A single `team-details.html` file that dynamically generates content based on URL parameters (e.g., `?id=robotics`), making the site incredibly easy to scale.

---

## 🛠️ Technology Stack

| Layer | Technology |
| :--- | :--- |
| **Styling** | Tailwind CSS (Utility-first) |
| **Motion** | GSAP (GreenSock Animation Platform) |
| **3D Engine** | Three.js (WebGL Point Clouds) |
| **Fluid Engine** | WebGL Shader-based Simulation |
| **Typography** | Syncopate (Headers), Space Grotesk (Body), JetBrains Mono (Tech Labels) |
| **Smooth Scroll** | Lenis by Studio Freight |

---

## 🎨 Color Palette (Logo Sampled)
*   **Deep Space Navy:** `#0B1118` (Primary Background)
*   **Eureka Gold:** `#C5A16F` (Primary Accents & Fluid)
*   **Ethereal Blue:** `#A3C4D9` (Secondary Technical Accents)
*   **Off-White:** `#FDF6E3` (Text for Readability)

---

## 🚀 Getting Started

1.  **Clone the Repository:**
    ```bash
    git clone https://github.com/your-username/eureka-club.git
    ```
2.  **Run Locally:**
    Since this project uses WebGL and external scripts, it is best viewed via a local server (like **Live Server** in VS Code).
3.  **Add a New Team:**
## 📂 Project Structure
```text
├── index.html                  # Main Cinematic Landing Page
├── team-details.html           # Dynamic Master Template for Divisions
├── dashboard.html              # Dynamic Admin Operations Control Center
├── components/                 # React UI Template Modules (shadcn/ui compatible)
│   └── ui/
│       ├── image-auto-slider.tsx  # Responsive infinite image slider
│       ├── splite.tsx             # Interactive 3D Spline scene component
│       ├── spotlight.tsx          # Aceternity static glow spotlight
│       ├── spotlight-hover.tsx    # Ibelick cursor dynamic spotlight
│       └── card.tsx               # Shadcn Card layout primitives
├── demo.tsx                    # React developer imports & components demo
├── package.json                # Project NPM dependencies & configuration
├── .gitignore                  # GitHub ignore definitions for local environments
└── README.md                   # Technical collective documentation
```

---

## 🚀 Getting Started

### 1. Run Static Environment
Since this project is a hybrid static web app with advanced WebGL features, you can run the primary pages (`index.html`, `team-details.html`, `dashboard.html`) immediately using a local development server (such as **Live Server** in VS Code). The past events and team divisions are loaded live from a **Supabase database** instance.

### 2. Run React Template Components
To compile or work on the newly added React components:
1. Ensure you have **Node.js** installed.
2. Initialize and install requirements:
   ```bash
   npm install
   ```
3. Use the components in your custom React/TypeScript configurations or follow the blueprints inside `demo.tsx`.

---

## 📝 Performance Optimization (Lite Mode vs Normal Mode)
EUREKA features an HUD-styled floating visual mode toggle (stored in `localStorage` to persist globally). 
* **NORMAL MODE:** Loads cinematic Three.js WebGL particle universes, custom handwriting SVG drawing preloaders, dynamic hover tiltparallax coordinates, rolling stats counts, and interactive 3D Spline backgrounds.
* **LITE MODE:** Snappily purges WebGL contexts, destroys Lenis smooth scrolls, converts GSAP stagger timelines to instant CSS layouts, bypasses cursor coordinate triggers, and falls back to manual tracks to preserve system CPU and RAM frames.

---

## 🛡️ License
Distributed under the MIT License. See `LICENSE` for more information.

**System Status: [ STABLE ]**  
**Eureka Technical Club // Beyond Boundaries**

## Creator
**Name: Sayujya Tiwari**