````markdown
# 🧰 Browser Developer Tools (DevTools)

Browser Developer Tools (DevTools) are built-in tools in modern browsers like Chrome, Firefox, and Edge. They allow developers to **inspect, debug, and analyze web applications** directly in the browser.

They help you understand:

- Structure of a webpage (HTML)
- Styling (CSS)
- Behavior (JavaScript)
- Network activity (API calls)
- Performance and storage

---

## 📌 How to Open DevTools

- Right-click → **Inspect**
- Shortcut:
  - `F12`
  - `Ctrl + Shift + I`

---

# 🔍 Main DevTools Panels

---

## 🧱 1. Elements Panel

The **Elements panel** shows the **DOM (Document Object Model)** of the webpage.

### What You Can Do

- View and edit HTML structure
- Modify CSS styles in real-time
- Enable/disable CSS rules
- Inspect layout (margin, padding, border)
- Test UI changes instantly

### Example

```html
<div class="box">
  Hello World
</div>
````

You can:

* Edit text directly
* Add/remove elements
* Change classes and styles

### Layout Box Model

Displays:

* Margin
* Border
* Padding
* Content

---

### 🖼️ Add Image (Elements Panel)

[ <img width="1857" height="762" alt="Screenshot from 2026-05-06 12-43-38" src="https://github.com/user-attachments/assets/91fb3dd5-e4ee-4bf6-85b3-d0a12d8e114f" />
]

---

## 🖥️ 2. Console Panel

The **Console** is used to run JavaScript and debug errors.

### What You Can Do

* Execute JavaScript code
* View errors and warnings
* Log messages
* Inspect variables and objects

### Common Methods

```javascript
console.log("Hello");
console.error("Error occurred");
console.warn("Warning");
```

### Example Error

```
Uncaught TypeError: undefined is not a function
```

### Use Cases

* Debug JavaScript issues
* Test functions quickly
* Check runtime errors

---

### 🖼️ Add Image (Console Panel)

[ Insert Screenshot of Console Panel Here ]

---

## 🌐 3. Network Panel

The **Network panel** shows all requests made by the webpage.

### What You Can See

* API calls (GET, POST, etc.)
* Status codes (200, 404, 500)
* Request and response data
* Headers and payload
* Load time of resources

### Use Cases

* Debug API failures
* Analyze slow requests
* Inspect request headers and responses

---

### 🖼️ Add Image (Network Panel)

[ Insert Screenshot of Network Panel Here ]

---

## ⚙️ 4. Sources Panel

The **Sources panel** is used for debugging JavaScript.

### Features

* View source files
* Set breakpoints
* Pause and step through code
* Inspect variable values during execution

### Debugging Flow

1. Set breakpoint
2. Reload page
3. Execution pauses
4. Analyze variables and flow

---

### 🖼️ Add Image (Sources Panel)

[ Insert Screenshot of Sources Panel Here ]

---

## 📊 5. Application Panel

The **Application panel** is used to inspect browser storage.

### Includes

* Cookies
* Local Storage
* Session Storage
* IndexedDB

### Example

```
sessionid=abc123
```

### Use Cases

* Debug login sessions
* Check stored tokens
* Analyze browser data

---

### 🖼️ Add Image (Application Panel)

[ Insert Screenshot of Application Panel Here ]

---

## 🚀 6. Performance Panel

The **Performance panel** helps analyze page performance.

### Shows

* Page load time
* Rendering performance
* JavaScript execution time

### Use Cases

* Identify slow parts of website
* Optimize performance

---

### 🖼️ Add Image (Performance Panel)

[ Insert Screenshot of Performance Panel Here ]

---

# 🧠 Why DevTools Are Important

DevTools are essential for:

* Debugging frontend issues
* Testing UI changes
* Monitoring API calls
* Analyzing performance
* Inspecting browser storage
* Security analysis (useful in SOC)

---

# 📌 Key Concepts

## DOM Inspection

View and edit webpage structure in real-time.

## Debugging

Identify and fix JavaScript errors.

## Network Analysis

Monitor requests and responses.

## Storage Inspection

Check cookies and browser storage.

---

# ✅ Final Summary

DevTools provide everything needed to work with web applications:

* **Elements** → HTML & CSS inspection
* **Console** → JavaScript debugging
* **Network** → API and request analysis
* **Sources** → Code debugging
* **Application** → Storage inspection
* **Performance** → Speed optimization

They are essential for:

* Web Developers
* Security Analysts
* SOC Engineers
* Bug Bounty Hunters

---

```
```
