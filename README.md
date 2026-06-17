# Dynamic Wrapper

Dynamic Wrapper is a high-performance, single-file progressive web application (PWA) designed to serve as an intelligent shell for your favorite web tools, dashboard dashboards, and documentation hubs. Built entirely with vanilla technologies and Tailwind CSS, it streamlines context switching by packaging navigation controls, quick launch tiles, persistent sessions, and developer diagnostics into a single elegant interface.

![Dynamic Wrapper UI](https://img.shields.io/badge/UI-Tailwind%20CSS-blueviolet?style=for-the-badge)
![JS](https://img.shields.io/badge/Vanilla-JavaScript-yellow?style=for-the-badge)
![PWA](https://img.shields.io/badge/PWA-Capable-orange?style=for-the-badge)

<img width="1562" height="640" alt="github_social_tagline" src="https://github.com/user-attachments/assets/e4878901-22dc-4f99-a45d-9cbf641fe0f9" />

## Features

- **Quick Launch Tiles Customization:** Pre-configured shortcuts for frequent web targets (Wikipedia, Archive.org, etc.) with the ability to add, configure, and instantly remove your own personalized site tiles.
- **Omni-Search Bar & Engine Swapper:** Seamlessly input raw URLs or switch search contexts natively between DuckDuckGo, Google, Bing, and Wikipedia directly within the address wrapper.
- **True Focus Mode (`F11`):** Completely hides navigation wrappers and control headers with a single toggle, dedicating 100% of the screen geometry to your active web application workspace.
- **Intelligent Cross-Origin Diagnostics:** Automatically monitors frame load thresholds. Since browser policies natively obscure specific cross-origin errors, the wrapper analyzes anomalies and alerts you if a site is utilizing restrictive `X-Frame-Options` or `Content-Security-Policy` directives, offering a clean external target link fallback.
- **Local Storage Synchronization:** Locally caches user configurations, your last visited path, structural navigation history, and an interactive bookmark registry entirely inside your browser sandbox. No backend required.
- **Responsive Glassmorphic Layout:** Engineered natively to adapt from high-end ultra-wide monitors to narrow mobile screens with compact, touch-friendly UI compromises.

## Keyboard Shortcuts Matrix

Boost your productivity inside the workspace with integrated hardware hotkeys:

| Shortcut | Action Description |
| :--- | :--- |
| `Enter` | Commit address input / query active engine |
| `Ctrl + R` | Hard reload the current embedded application frame |
| `Alt + Home` | Kill current frame instance and return to home dashboard |
| `F11` | Toggle Focus Mode (Enter/Exit distracting header frame) |

<img width="2446" height="1303" alt="dw" src="https://github.com/user-attachments/assets/8b8256cc-aebe-4931-96f6-87df5fd5cded" />

## Installation

Because Dynamic Wrapper is built entirely in a unified, context-aware single file, deployment is entirely seamless:

### Direct Local Execution
1. Clone the repository or download the source file:
   ```bash
   git clone https://github.com/vojislav77.github.io/dynamic-wrapper.git
2. Navigate into the directory and open index.html directly in any standard, modern browser.

## Understanding Embedding Security (Why some sites stay blank)

Many web giants (like Google, Facebook, or online banking applications) actively broadcast an administrative security header:

    X-Frame-Options: SAMEORIGIN

This is a standard browser security measure implemented to prevent Clickjacking attacks. Dynamic Wrapper’s integrated Feature 4 Security Diagnostics Interface handles this gracefully by flagging frozen or refused handshakes and providing an isolated "Open in New Tab" link shortcut so your workflow remains completely uninterrupted.

## License

This project is licensed under the MIT License - feel free to modify, expand, or repurpose it for your personal infrastructure.
