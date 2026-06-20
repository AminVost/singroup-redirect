````markdown
# Smart Traffic Gateway (Social Media Router)

A lightweight, highly optimized static web gateway designed to ensure seamless traffic routing from social media platforms (specifically Instagram) to external e-commerce storefronts.

## 🎯 The Problem & Solution
**The Challenge:** In certain network environments, or due to the aggressive caching and limitations of in-app browsers (like the Instagram in-app browser), users frequently encounter blank pages or broken links when trying to visit a business's external website from a social media story or bio.

**The Solution:** This project acts as an intelligent intermediary layer. When a user clicks a link on social media, they are instantly routed through this highly optimized static gateway. It effectively bypasses in-app browser rendering issues and network bottlenecks, redirecting the user safely and swiftly to the target platform.

## 🏛 Tech Stack & Architecture
To ensure zero-latency loading and maximum compatibility, this gateway is built without heavy frameworks:
* **Core:** Pure HTML5, CSS3, and Vanilla JavaScript.
* **Infrastructure:** Configured for edge-network static hosting with custom DNS mapping (`CNAME`).

## 🚀 Key Features
* **Millisecond Redirection:** Extremely low DOM payload ensures users are routed to the main shop almost instantly.
* **Cross-Browser Reliability:** Specifically engineered to overcome the "blank screen" issue commonly found in iOS/Android social media in-app browsers.
* **Branded Fallback UI:** Includes a clean, branded loading state (`index.html`) and error handling (`404.html`) to maintain brand trust during network delays.

## 📄 Usage
This structure is designed to be deployed directly to static hosting services (like GitHub Pages or Cloudflare Pages). Modify the destination URL within the core scripts and attach your custom domain via the `CNAME` file.
