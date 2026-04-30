# Worknoon WordPress Assessment

## 📌 Project Overview
This repository contains the completed tasks for the Worknoon WordPress Developer Assessment. The project demonstrates the ability to build a high-performance, responsive WordPress landing page integrated with SEO best practices and modern system architecture.

---

## ⚙️ Setup Instructions
To view or replicate this project locally:
1. **Clone the Repository:** 
   `git clone https://github.com/thedevbuilder/worknoon-wordpress-assessment.git`
2. **Environment:** Import the project into **Local WP** or a standard **XAMPP** environment.
3. **Database:** Import the included `.sql` database file to restore page structures and Elementor settings.
4. **Theme/Plugins:**
   - Move the custom theme or child theme files to `/wp-content/themes/`.
   - Ensure **Elementor** is installed and active.
5. **Analytics:** The **Umami** tracking script is pre-integrated into the header; ensure the `data-website-id` is updated for your specific instance.

---

## 🛠 Tools & Technologies Used
* **CMS:** WordPress (Core system for scalable content management)[cite: 1].
* **Page Builder:** **Elementor** (Used for building the Hero, Services, and Testimonial sections)[cite: 1].
* **Analytics:** **Umami** (Chosen as a lightweight, privacy-first alternative to Google Analytics to ensure higher performance scores)[cite: 1].
* **Forms:** Integrated via Elementor/Plugin to handle lead generation[cite: 1].

---

## 🏗 System Architecture Overview
* **Front-end Layer:** Utilizes Elementor for layout flexibility while leveraging custom CSS overrides to reduce the need for heavy third-party add-ons[cite: 1].
* **Optimization Layer:** Assets are optimized via WebP image formats and minimal script execution to ensure page speed targets are met[cite: 1].
* **Telemetry Layer:** A decentralized analytics approach using Umami to provide real-time data without the overhead of traditional tracking cookies[cite: 1].

---

## 🚀 Challenges & Resolutions
* **Challenge:** Centering sticky UI elements within the Elementor container grid.
  - **Resolution:** Implemented a CSS transform fix (`left: 50%; transform: translateX(-50%);`) to force absolute centering regardless of parent column width.
* **Challenge:** Maintaining high performance while utilizing a visual page builder.
  - **Resolution:** Stripped unnecessary bloat by using custom CSS for the Carousel and Gradients instead of installing additional Elementor widget packs.
* **Challenge:** Ensuring modern analytics were ad-blocker resistant.
  - **Resolution:** Deployed Umami as a lightweight script in the header, avoiding the privacy and performance pitfalls of standard Google Analytics[cite: 1].

---

## 📂 Repository Structure
- `/schema`: Contains JSON-LD files for Organization and Person schemas (Section B)[cite: 1].
- `/docs`: Includes `knowledge-panel-strategy.md` (Section C) and `seo-diagnosis.md` (Section D)[cite: 1].
- `/theme-files`: Contains the exported theme/plugin code used for the landing page (Section A)[cite: 1].
- `short-answers.md`: Answers to the technical SEO questions (Section E)[cite: 1].

---

## 🎥 Demo Video
A full walk-through of the project, architecture, and SEO strategy can be found here:
**[Link to your Loom/YouTube Video]**[cite: 1]