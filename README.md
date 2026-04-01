# RBI Grade B | Prep Hub Elite

A high-performance, **locally-hosted digital library** and strategy dashboard designed specifically for **RBI Grade B** aspirants. This application provides an integrated interface to manage study materials, track progress, and access official RBI resources within a single, "Consultant-Grade" professional environment.

---

## 🚀 Key Features

### 1. **Integrated Study Interface**
* **Unified Sidebar:** Navigate seamlessly between **Phase I** (Quant, English, Reasoning) and **Phase II** (ESI, Finance, Management) materials.
* **Dynamic Viewport:** Content is rendered via an optimized `iframe` system, ensuring that navigated pages feel like native parts of the application.
* **Focus Mode:** Automatic "Full Screen" triggers upon navigation, hiding the sidebar and header to eliminate distractions during deep study sessions.

### 2. **Financial Utility & Personalization**
* **Live Economic Clock:** A real-time header clock displaying the day, date, and time in `en-IN` format, essential for tracking time-sensitive financial updates.
* **Integrated Support Portal:** A built-in UPI donation system with **Custom Amount Validation** (Minimum ₹10) and one-tap "Copy UPI ID" functionality.

### 3. **Professional UX/UI**
* **Tailwind CSS 3.0:** Built with a modern, "FinTech" aesthetic using the **Plus Jakarta Sans** typeface.
* **Responsive Design:** Fully adaptive for Desktop, Tablet, and Mobile views with a smooth, cubic-bezier transition sidebar.
* **High-Density Footer:** Minimalist footer containing quick links to the **Official RBI Website**, **RBI Bulletins**, and developer contact info.

---

## 🛠️ Technical Stack

| Component | Technology |
| :--- | :--- |
| **Styling** | Tailwind CSS (via CDN) |
| **Icons** | Font Awesome 6.4.0 (Pro-look) |
| **Typography** | Google Fonts (Plus Jakarta Sans) |
| **Logic** | Vanilla JavaScript (ES6+) |
| **Layout** | CSS Flexbox & Absolute Positioning |

---

## 📂 File Structure

To run this dashboard, ensure your local directory is structured as follows:

```text
/RBI-Prep-Hub
├── index.html              <-- Main Dashboard (The file provided)
├── RBI_Grade-B.html         <-- Strategy Overview Content
├── Quant-Paper-I.html       <-- Phase I: Quant Content
├── English-Paper-I.html     <-- Phase I: English Content
├── RA-Paper-I.html          <-- Phase I: Reasoning Content
├── ESI-Paper-II.html        <-- Phase II: ESI Content
├── Finance-Paper-II.html    <-- Phase II: Finance Content
├── Management-Paper-II.html <-- Phase II: Management Content
└── English-Paper-II.html    <-- Phase II: Descriptive Content
