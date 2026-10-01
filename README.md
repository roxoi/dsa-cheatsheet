<h3 align="center">
  <a href="https://rajendrapancholi.vercel.app/">
    <img src="./assets/logo.svg" alt="Logo" width="80" height="80" />
  </a>
  <br>Hi there 👋<br>
  I'm Rajendra Pancholi - Full Stack Developer (MERN)
</h3>

<div align="center">

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=2E9EF7&center=true&vCenter=true&width=750&lines=DSA+Pattern+Recognition+Cheat-Sheet+%F0%9F%A7%A0;Spot+the+clue%2C+find+the+technique;22%2B+topics+from+Arrays+to+Segment+Trees;Copy-ready+C%2B%2B+examples+for+every+pattern;Searchable%2C+dark-themed%2C+single+HTML+file;Built+for+interview+prep+%26+competitive+programming+%F0%9F%9A%80)](https://git.io/typing-svg)

</div>

---

# DSA Pattern Recognition Cheat-Sheet

A searchable, single-file field manual that maps the **clue in a problem statement** to the **algorithm or data-structure pattern** it points to, with copy-ready C++ examples. No installation, no build step, no dependencies to manage. It runs entirely in your browser.

![License](https://img.shields.io/badge/license-MIT-green)
![HTML5](https://img.shields.io/badge/HTML5-E34C26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat&logo=cplusplus&logoColor=white)

## ✨ Features

### Pattern Recognition
- **"When you see… → Pattern" tables** - Read the left column as the clue, the right column as the technique
- **23 topic sections plus a Master Index** - From operator precedence to rerooting DP
- **Easy / Medium / Hard grouping** - Patterns are ordered so later ones build on earlier ones
- **Complexity tables** - Time, space and stability at a glance for sorting algorithms
- **Closing decision rule** - Three questions to ask when you're stuck

### Worked C++ Examples
- **Copy-ready snippets** - One-click copy button on every code block
- **Syntax Highlighting** - C++ highlighting via highlight.js with a custom palette
- **Classic problems covered** - Kadane, 3Sum, KMP, LRU/LFU Cache, Dijkstra, Bellman-Ford, Kruskal, Segment Tree, Fenwick Tree, Digit DP, TSP, LCA and more
- **Assumed headers** - Every snippet assumes `#include <bits/stdc++.h>` and `using namespace std;`

### Navigation & UX
- **Live Search** - Filter patterns, rows and examples as you type
- **Sticky Sidebar Index** - Jump to any topic instantly
- **Active Section Highlighting** - Sidebar tracks where you are while scrolling
- **Dark Theme** - Easy on the eyes for long study sessions
- **Responsive Layout** - Collapsible menu on small screens
- **Custom Scrollbars** - Slim, themed scrollbars (Chromium and Firefox)

## Quick Start

### Option 1: Open Online
```
https://roxoi.github.io/dsa-cheatsheet
```

### Option 2: Download & Run Locally
1. Download `index.html`
2. Open it in any modern web browser
3. Start recognizing patterns!

> Fonts (Google Fonts) and highlight.js (cdnjs) load from a CDN, so an internet connection is needed for the full look. Everything still works without it, just with fallback fonts and no code coloring.

## How to Use

```
Find a pattern      → Type a keyword in the "Filter patterns…" box
Jump to a topic     → Click it in the sidebar
Copy an example     → Click "copy" at the top-right of any code block
Not sure where?     → Open the Master Index (∞) at the bottom
```

## Topics Covered

| #  | Topic | #  | Topic |
|----|-------|----|-------|
| 00 | C++ Operator Precedence | 12 | Binary Trees |
| 01 | Sorting Techniques | 13 | Binary Search Trees |
| 02 | Arrays | 14 | Graphs |
| 03 | Binary Search | 15 | Dynamic Programming |
| 04 | Strings | 16 | Tries |
| 05 | Linked List | 17 | Strings - Advanced |
| 06 | Recursion (Pattern-wise) | 18 | Segment Trees & Fenwick |
| 07 | Bit Manipulation | 19 | Math & Number Theory |
| 08 | Stack and Queues | 20 | Advanced DP |
| 09 | Sliding Window & Two Pointer | 21 | Advanced Union-Find |
| 10 | Heaps | 22 | Advanced Tree Patterns |
| 11 | Greedy Algorithms | ∞  | Master Recognition Index |

Sections 18-22 are the **"Beyond A2Z" competitive-programming extensions**.

## Example: How the Tables Read

| When you see… | Pattern |
|---------------|---------|
| Subarray sum equals K | Prefix sum + HashMap |
| Minimize the max / maximize the min | Binary search on the answer |
| Next greater element | Monotonic stack |
| Shortest path with weights | Dijkstra's |
| Kth largest / smallest | Heap or Quickselect |

## Deploy to GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [github.com/new](https://github.com/new)
2. Repository name: **dsa-cheatsheet** (this becomes the URL path)
3. Add description: "Searchable DSA pattern recognition cheat-sheet with C++ examples"
4. Click "Create repository"

### Step 2: Clone & Setup

```bash
# Clone the repository
git clone https://github.com/roxoi/dsa-cheatsheet.git

# Navigate to folder
cd dsa-cheatsheet

# Add the cheat-sheet file as index.html
```

### Step 3: Push to GitHub

```bash
git add .
git commit -m "Initial commit: Add DSA pattern cheat-sheet"
git push -u origin main
```

### Step 4: Enable GitHub Pages

1. Go to your repository **Settings**
2. Open **Pages** in the sidebar
3. Under **Build and deployment**, choose **Deploy from a branch**
4. Select the **main** branch and **/ (root)**, then click **Save**
5. Wait 1-2 minutes for deployment

Your cheat-sheet will be live at:
```
https://roxoi.github.io/dsa-cheatsheet
```

## Repository Structure

```
dsa-cheatsheet/
├── index.html          # The entire cheat-sheet (HTML + CSS + JS)
├── README.md           # This file
├── LICENSE             # MIT License
└── .gitignore          # Git ignore file
```

## Technologies Used

- **highlight.js 11.9.0** - C++ syntax highlighting (via cdnjs)
- **Google Fonts** - Newsreader (text) and IBM Plex Mono (code and labels)
- **Vanilla JavaScript** - Search, copy buttons, scroll-spy, mobile menu
- **HTML5 & CSS3** - CSS variables, flexbox, `IntersectionObserver`

## Tips & Tricks

1. **Start from the clue, not the topic** - Search for the phrase from the problem, like "next greater" or "kth smallest"
2. **Use the Master Index** - When two sections seem plausible, the index gives the fastest first guess
3. **Read the example after the table** - The pattern name tells you *what*, the code shows *how*
4. **Check the neighbors** - Many rows cross-reference Advanced sections (for example Manacher's, Kruskal's)
5. **Practice recall** - Cover the right column and try to name the pattern from the clue alone

## Use Cases

- Coding interview preparation
- Competitive programming revision
- Quick last-minute DSA review
- Learning algorithm recognition, not just implementation
- Building your own pattern notes
- Teaching and mentoring

## Browser Compatibility

| Browser | Support |
|---------|---------|
| Chrome/Edge | Full |
| Firefox | Full |
| Safari | Full |
| Mobile Browsers | Full (collapsible sidebar) |

## Contributing

Found a wrong pattern, a missing problem, or a bug in an example? Issues and pull requests are welcome!

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/new-pattern`)
3. Commit your changes (`git commit -m 'Add new pattern'`)
4. Push to the branch (`git push origin feature/new-pattern`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact & Social

- **Email** - roxoi0x01@gmail.com
- **GitHub** - [@roxoi](https://github.com/roxoi)
- **Portfolio** - [roxoi.com](https://roxoi.github.io)
## Acknowledgments

- **highlight.js** - For lightweight code highlighting
- **Google Fonts** - For Newsreader and IBM Plex Mono
- **The DSA community** - For the problems and patterns this sheet organizes

---

**Made with ❤️ by [Roxoi](https://github.com/roxoi)**

> "Don't memorize solutions. Recognize patterns."
