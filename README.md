# DupeSleuth-Pro
DupeSleuth Pro finds and manages duplicate or similar photos and videos on Windows. It scans folders fast, detects exact or near matches, previews images, GIFs, and videos, and lets you auto-select which to keep (newest, oldest, largest, shortest path) before moving or deleting duplicates safely.

DupeSleuth Pro is a Windows desktop tool that helps you clean up massive folders full of photos and videos by automatically finding duplicate and similar files — even if they’ve been renamed, resized, or re-encoded.

It’s designed for speed, accuracy, and full control.

🔍 What It Does
• Scans any folder (and all its subfolders) for photos and videos — .jpg, .jpeg, .png, .gif, .mp4, .mov
• Finds exact duplicates using cryptographic SHA-256 hashing for 100% accuracy.
• Optionally performs byte-for-byte verification for guaranteed matches.
• Detects visually similar files using perceptual hashing — useful for resized or compressed images and re-encoded videos.
• Displays all matches in an easy-to-browse list with thumbnails and group numbers.
• Lets you preview any file (images, animated GIFs, or video stills) with a double-click.
• Allows you to auto-select duplicates to keep one copy based on your preferred rule:
  - Keep newest
  - Keep oldest
  - Keep shortest path
  - Keep largest file
• Lets you move unwanted duplicates to another folder or delete them safely to the Recycle Bin.

⚙️ How It Works
1. Groups files by size first (fast pre-filter).
2. Calculates file hashes in parallel using all your CPU cores for NVMe-speed performance.
3. Optionally compares perceptual image/video fingerprints to spot near-duplicates.
4. Shows every duplicate group so you can review before taking action.

💡 Why It’s Useful
• Perfect for photographers, videographers, or anyone with huge media archives.
• Helps reclaim disk space and organize messy folders without risking important files.
• Works entirely offline, directly on your local drives — no cloud, no uploads.

FFmpeg.exe Included.
