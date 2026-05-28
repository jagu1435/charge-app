=== अतिरिक्त कार्यभार नोंदवही — Android App ===

हे PWA (Progressive Web App) आहे.

ANDROID वर APP कसे Install करावे:
=====================================
पद्धत १ — Chrome Browser (सर्वात सोपी):
1. index.html फाईल Google Drive मध्ये upload करा
2. Chrome मध्ये उघडा
3. Chrome menu (⋮) → "Add to Home Screen" दाबा
4. "Install" दाबा → App Home Screen वर येईल

पद्धत २ — Local Server (Offline):
1. फोनमध्ये "Simple HTTP Server" app install करा
2. या folder ला point करा
3. Chrome मध्ये localhost उघडा → Install करा

DATA:
- Data localStorage मध्ये कायमस्वरूपी राहतो
- App uninstall केले तरी data राहतो
- Backup साठी App मधील "📦 Backup" वापरा

FILES:
- index.html   → मुख्य App
- manifest.json → App माहिती
- sw.js         → Offline support
