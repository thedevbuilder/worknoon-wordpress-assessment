# Section E: Short Answer Questions

### 1. Difference between Google Knowledge Graph and Google Knowledge Panel
* **The Knowledge Graph** is Google's behind-the-scenes database that stores interconnected facts about entities (people, places, things) and their relationships.
* **The Knowledge Panel** is the visual UI element that appears on the right side of search results, pulling data from the Knowledge Graph to present a summary of an entity .
* **In short:** The Graph is the structured data repository; the Panel is the frontend display of that data .

### 2. How Google Determines Entity Identity
Google uses a process called **Reconciliation** to determine identity :
* **Identifier Matching:** It looks for unique identifiers, such as the `sameAs` schema property, to link different URLs to the same entity .
* **Attribute Consistency:** It compares attributes like Name, Address, Phone (NAP), and Founder details across high-authority sources such as LinkedIn and official websites .
* **Contextual Association:** It uses Natural Language Processing (NLP) to analyze how a brand is mentioned in external content to confirm it is a distinct, authoritative entity .

### 3. When to Create Custom Post Types (CPT) Instead of Pages
You should opt for a **Custom Post Type** when the content :
* **Follows a Repeated Schema:** If you are managing data with a consistent structure, such as "Testimonials" or "Services," a CPT allows for standardized data entry .
* **Needs Unique Archive Logic:** When you require a dedicated archive page with specific filtering or sorting that differs from standard pages .
* **Scalability:** When you have a large volume of similar items that would clutter the "Pages" menu and make the dashboard difficult to navigate .

### 4. Recommended Plugins for Speed Optimization and Why
* **WP Rocket:** A comprehensive tool that handles page caching, GZIP compression, and delayed JavaScript execution .
* **Perfmatters:** A lightweight script manager that allows you to disable unnecessary WordPress bloat (like Emojis or Dashicons) on a per-page basis to reduce HTTP requests .
* **Imagify / ShortPixel:** Essential for converting images to WebP format and performing compression to reduce the Largest Contentful Paint (LCP)
* **Asset CleanUp:** Useful for unloading specific CSS/JS files from pages where they are not needed to keep the page weight minimal