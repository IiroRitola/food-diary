# 🍽️ Ruokapäiväkirja (Food Diary)

A comprehensive Finnish personal food diary web application for tracking meals, hunger levels, symptoms, and dietary patterns. Built as a Progressive Web App with instant access and local data storage.

## ✨ Features

### 📱 **Mobile-First Design**
- 📲 PWA (Progressive Web App) - installable on mobile devices
- ⚡ Optimized startup performance for iOS home screen
- 📱 Mobile-optimized touch interface
- 🌙 Dark mode support
- 🔄 Works offline once installed

### 🍽️ **Food Tracking**
- ⏰ Quick meal entry with time, location, and foods
- 🔢 Hunger and satiety tracking (1-10 scale)
- 💭 Mood and feelings logging
- ⚕️ Symptom tracking for food reactions
- ✏️ **Edit existing entries** (perfect for adding symptoms later)

### 📊 **Data Management**
- 💾 Smart local storage (localStorage/IndexedDB/memory fallback)
- 📅 Daily view with historical data access
- 🔄 Change dates to view previous entries
- 🧹 Clean, readable entry display format

### 📈 **Export & Analysis**
- 📋 **Excel-optimized CSV export** (separate food/amount columns)
- 📊 Daily or complete data export
- 💾 JSON backup/restore functionality
- 🔄 Data migration between devices

### 🎨 **User Experience**
- 🚀 **No password required** - instant access
- 🎯 Quick-fill buttons (home, work, restaurant)
- ⚡ "Now" button for current time
- 📝 Dynamic food table (add/remove items)
- 🖼️ Visual edit mode with yellow highlighting

## 🚀 Getting Started

1. **Visit the app**: [https://iiroritola.github.io/food-diary/](https://iiroritola.github.io/food-diary/)
2. **Add to home screen** (recommended for best experience)
3. **Start tracking** - no setup required!

### 📱 Installing as PWA
- **iPhone**: Safari → Share → Add to Home Screen
- **Android**: Chrome → Menu → Add to Home Screen

## 📖 How to Use

### **Adding Entries**
1. App opens to today's date automatically
2. Fill in meal time, location, and foods
3. Add hunger/satiety levels and any symptoms
4. Click "Lisää merkintä" to save

### **Editing Entries**
1. Find the entry in "Päivän merkinnät" section
2. Click "✏️ Muokkaa" 
3. Form fills with existing data
4. Make changes and click "Tallenna muutokset"
5. Perfect for adding symptoms that appear later!

### **Viewing Historical Data**
1. Change the date field at the top
2. View entries from any previous day
3. Edit or delete old entries as needed

### **Exporting Data**
- **Daily CSV**: Perfect for single-day analysis
- **All Data CSV**: Excel-ready format with separate columns
- **JSON Backup**: Complete data export for migration

## 🏗️ Technical Details

### **Architecture**
- Single-file HTML application
- Embedded CSS and JavaScript
- No external dependencies
- Progressive enhancement

### **Data Storage**
- **Primary**: localStorage (persistent)
- **Fallback**: IndexedDB (if localStorage blocked)
- **Emergency**: Memory only (session-based)
- **Format**: JSON with date-based organization

### **Compatibility**
- ✅ Modern web browsers
- ✅ iOS Safari (PWA support)
- ✅ Chrome/Edge (full PWA features)
- ✅ Works offline after first load

## 🔒 Privacy & Data

- **100% Local**: All data stays on your device
- **No Servers**: No data sent to external services
- **No Tracking**: No analytics or user tracking
- **No Accounts**: No registration or login required

⚠️ **Data Loss Prevention**: Use the backup export feature regularly, especially if using private browsing mode.

## 📊 CSV Export Format

The exported CSV is optimized for Excel analysis:

| Aika | Paikka | Ruuat ja juomat | Määrä | Nälän aste/tunteet | Oireet |
|------|--------|-----------------|-------|-------------------|---------|
| 12:30 | Koti | apple | 1 medium | Nälkä: 4/10, Kylläisyys: 7/10 | |
| | | banana | 1 large | | |

Perfect for creating charts and analyzing eating patterns!

## 🛠️ Development

Built with vanilla HTML, CSS, and JavaScript for maximum compatibility and performance.

### **Key Features Implementation**
- PWA manifest with proper icons
- Service Worker for offline capability
- Smart storage detection and fallbacks
- Mobile-optimized touch interfaces
- Excel-compatible CSV generation

## 📄 License

See LICENSE file for details.

---

**Made for personal food tracking and dietary pattern analysis** 🍽️📊 