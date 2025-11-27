# 👗 OutfitFLEX – AI Virtual Wardrobe Assistant

OutfitFLEX is a smart, AI-assisted virtual wardrobe and outfit planning application designed to help users organize their clothing, plan daily outfits, and receive intelligent styling recommendations. It combines a React Native (Expo) mobile frontend with an Express.js backend and Cloudinary-based image handling, with future support for ML-driven outfit suggestions.

---

## 🚀 Features

### 🧥 **Digital Wardrobe Management**
- Upload clothing items with images
- Automatically store and manage item categories, colors, and metadata
- Organized wardrobe view for easy browsing

### 👚 **Outfit Creation & Planning**
- Combine multiple clothing items into a complete outfit
- Add details like occasions, seasons, style names, and notes
- Save and manage outfit combinations

### 🎨 **Smart Style Suggestions (Future ML)**
- Outfit recommendation engine using image features and color matching
- Suggestions based on:
  - Personal preferences
  - Color compatibility
  - Occasions
  - Style types
  - Seasonal context

### ☁️ **Cloud Storage**
- Seamless image upload and retrieval via Cloudinary

### 🔐 **Authentication**
- Secure signup/login (via Supabase earlier; currently integrating custom backend workflows)

---

## 🛠️ Tech Stack

### **Frontend**
- React Native (Expo SDK 53)
- TypeScript
- Context API for state management
- Tailwind via NativeWind (if included)
- React Navigation

### **Backend**
- Node.js + Express.js
- Cloudinary for image upload
- REST API architecture
- Authentication & token handling (planned enhancements)

### **Database**
- (Handled externally by other team member — e.g., PostgreSQL/Supabase/MongoDB)

### **AI/ML (Upcoming Enhancements)**
- Clothing image classifier (CNN)
- Color detection model
- Feature extractor for similarity matching
- Outfit suggestion engine with trend awareness




