# pro-synth-pdf
ProSynth: Advanced local-first PDF engine. Zero-Knowledge architecture ensures 100% privacy – data never leaves the browser. Optimized for mass synthesis (500+ pages) with automatic scaling and sorting. Engineering precision for sensitive documentation.
ProSynth: Advanced Client-Side PDF Synthesis Engine

ProSynth is a professional-grade document synthesis engine built for environments where data integrity, operational security (OPSEC), and processing speed are non-negotiable. Designed for legal, administrative, and strategic workflows, it allows for high-volume compilation of image assets (JPG, PNG, WEBP) into standardized PDF documents.

🚀 Core Philosophy: Local-First Privacy

ProSynth utilizes a strict Zero-Knowledge Architecture. Unlike cloud-based converters, all binary synthesis is performed entirely within the local browser context. This ensures that sensitive documentation—whether legal evidence, financial records, or internal memos—never leaves the secure environment of the user's isolated machine.

🛠 Technical Specifications

Massive Batch Support: Stabilized memory management for handling 500+ high-resolution pages in a single synthesis cycle.

Asynchronous Processing: Utilizes non-blocking Blob reading and Promise-based execution to prevent UI thread locking during heavy DOM operations.

Numerical Sorting Logic: Custom localeCompare algorithm ensures automated, logical pagination based on original file nomenclature.

Adaptive Canvas Engine: Dynamically calculates aspect ratios to perfectly fit images to A4 specifications (210x297mm) while preserving original image integrity and preventing visual distortion.

📖 Quick Start

Clone the repository or simply deploy the index.html file in any modern, Chromium-based or WebKit browser.

Drag and drop your image assets into the designated drop zone.

Review the automatically sorted preview grid.

Execute PDF generation to synthesize the binary and download your document locally.

Lead Architect: Jakub Wielogórski

Specialist in Privacy Engineering & Workflow Automation.
