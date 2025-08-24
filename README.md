# Daily Learning Planner

A single-page web application for organizing, tracking, and visualizing daily tasks with a monthly heatmap, customizable templates, and interactive progress tracking. All data is stored locally in your browser.

### [Live Demo](https://spidersnipero.github.io/Daily-planner/) 

https://spidersnipero.github.io/Daily-planner/

## Features

* **Progress Visualization:**
    * **Monthly Heatmap:** Get an at-a-glance view of your monthly activity, with days color-coded by task completion percentage.
    * **Circular Progress Bars:** Each day's summary includes a circular progress bar showing the overall completion rate.
* **Customizable Planning:**
    * **Dynamic Templates:** Add or remove categories (e.g., "DSA," "Gym") on any day. Changes update the default template for future plans without altering past entries.
    * **Smart Defaults:** New daily plans are automatically created using the template from your most recently planned day.
* **Interactive UI:**
    * **Collapsible Summaries:** Daily plans are displayed as collapsible dropdowns to keep the dashboard clean. Current and future days are expanded by default.
    * **Weekly Pagination:** Navigate through your plans week by week (Sunday to Saturday).
    * **Dark & Light Modes:** Toggle between themes with a convenient header button. Your preference is saved automatically.

## How to Run Locally

This project is a single HTML file with no build dependencies.

1.  **Clone the repository:**
    ```
    git clone git@github.com:spidersnipero/Daily-planner.git
    ```
2.  **Navigate to the project directory:**
    ```
    cd your-repo-name
    ```
3.  **Open the `index.html` file** in your web browser.

## Tech Stack

* **HTML**
* **Tailwind CSS** (via CDN)
* **JavaScript (ES6+)**
* **Browser Local Storage**
