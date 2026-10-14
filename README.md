# ProX
All in one content creation suite for the web. Supports low-end devices as well as hardware acceleration for H.264/H.265

My name is Matthew, and my goal is to create a semi-professional suite of web applications for video editing, photo editing, graphic design, and 3D modeling.

You might wonder why I started this project. Currently, there is a severe shortage of professional-grade creative tools accessible on budget-friendly devices like Chromebooks and tablets. While options like CapCut exist, they are often clunky and lock essential features behind a subscription paywall or watermarks—a monetization model many creators find exhausting. Adobe offers mobile versions for Android, but they are heavily stripped down and lack true utility.

To bridge this gap, I spent several days developing a web-based platform that delivers professional-level features without watermarks, expensive monthly subscriptions, or high upfront costs.

Pro X offers a robust set of features across creative disciplines:

    Advanced Editing Tools: Lasso selection, chroma key, custom LUTs, and multiple video layers.

    Enhancements: A wide library of effects, precise color correction, and flexible gradient maps.

    Performance & Rendering: Hardware-accelerated encoding for H.264, H.265, and ProRes.

    Export Control: Full customization options for resolution, frame rate, bitrate, and color profiles.

Troubleshooting Tip: If your file is not downloading, right-click the download button and select "Save as." and type in the name of the file followed by the file's type (i.e JPG, PNG, WEBP, mp4, MOV, etc.)

STUDIO EDITOR PRO X — SYSTEM REQUIREMENTS

MINIMUM REQUIREMENTS
--------------------
CPU: Intel Core i5-4200U or AMD A10-5750M equivalent
CPU Cores/Threads: 2 cores / 4 threads
CPU Clock Speed: 1.6 GHz base or equivalent
RAM: 4GB (8GB Required for Video Editing at 1080p30) 
GPU: Intel HD Graphics 4400, AMD Radeon HD 8650G, or NVIDIA GeForce GT 730 equivalent
VRAM: Integrated graphics supported; dedicated VRAM not required
Operating System: Windows 10 64-bit, compatible macOS, or Linux distribution
Browser: Modern browser supporting required APIs
Storage: 2 GB free space minimum, plus additional space for media
Display: 1280 x 720
Internet: Required for initial FFmpeg.wasm download

RECOMMENDED REQUIREMENTS
------------------------
CPU: Intel Core i5-8250U or AMD Ryzen 5 3500U or better
CPU Cores/Threads: 4 cores / 8 threads
CPU Clock Speed: 2.0 GHz+ base, 3.4 GHz+ boost preferred
RAM: 16 GB or more
GPU: Intel UHD Graphics 620 or newer, AMD Radeon RX 570, or NVIDIA GeForce GTX 1650
VRAM: 4 GB dedicated VRAM preferred
Operating System: Windows 11 64-bit, recent macOS, or recent Linux distribution
Browser: Latest Google Chrome, Microsoft Edge, Mozilla Firefox, or Safari
Storage: SSD with at least 10 GB free space
Display: 1920 x 1080 or higher
Internet: Broadband connection recommended

REQUIRED BROWSER APIS
---------------------
- HTML5 Canvas 2D
- Web Audio API
- MediaRecorder API
- WebAssembly (Wasm)
- JavaScript
- File API
- Web Workers
- Web GL 2.0

SUPPORTED WORKLOADS
-------------------
- Photo editing
- Audio editing and processing
- 720p30 video editing
- 1080p30 video editing

IMPORTANT NOTES
---------------
These specifications are proposed compatibility targets, not hardware requirements enforced by the application itself. Actual performance depends on the browser, media codecs, project complexity, and available memory. GPU acceleration and codec support vary by system and browser.

Studio Editor Pro X requires an internet connection to download FFmpeg.wasm when it is not already cached.
