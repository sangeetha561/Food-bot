# 🍳 CraveCraft AI — Real-Time Gourmet Food & Recipe Recommendation Chatbot

[![GitHub Pages](https://img.shields.io/badge/Deployment-GitHub%20Pages-brightgreen?logo=github)](https://pages.github.com/)
[![Built With](https://img.shields.io/badge/Tech-Vanilla%20JS%20%7C%20TailwindCSS%20%7C%20Web%20APIs-orange)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

An interactive, food-themed conversational AI chatbot that delivers **real-time personalized culinary recommendations**, deep nutritional insights, recipe steps, servings scaling, and meal planning. Designed with a modern gourmand aesthetic, tactile micro-animations, synthesized audio cues, voice dictation, and an interactive craving roulette wheel.

Deployable immediately to **GitHub Pages** as a standalone single-file web application with zero complex build tooling or server requirements.

---

## ✨ Features at a Glance

### 💬 1. Conversational AI Culinary Engine
- **Autonomous Local NLP Engine**: Instant, zero-latency culinary reasoning matching mood, cravings, time limits, and dietary choices.
- **Natural Language Parsing**: Detects cuisines (*Italian, Japanese, Mexican, Indian, Mediterranean, Thai, etc.*), dietary tags (*Vegan, Keto, Gluten-Free, Halal, etc.*), and contextual sentiments (*post-workout recovery, cozy comforting dinner, late-night cravings*).
- **Optional Live Generative AI**: Supports plugging in your own **Google Gemini 1.5** or **OpenAI GPT-4o Mini** API key for streaming generative conversations directly in the settings panel.

### 🍱 2. Rich Interactive Recommendation Cards
- **High-Definition Food Visuals**: Curated food photography for every dish.
- **Match Score Algorithm**: Dynamic percentage match indicator calculated based on your active lifestyle criteria.
- **Micro-Macro Breakdown**: Immediate visibility into Protein, Carbohydrates, Healthy Fats, and Total Caloric load.
- **One-Click Action Buttons**: Direct modal inspection for step-by-step instructions, grocery list synchronization, and wine/beverage pairing suggestions.

### 📖 3. Interactive Recipe Inspector & Scaler
- **Dynamic Servings Scaler**: Effortlessly adjust portions from 1 to 12 servings; ingredient measurements recalculate automatically.
- **Preparation Checklist**: Interactive check-off items for prepping mise-en-place.
- **Built-in Kitchen Timer**: Real-time 15-minute countdown timer with auditory chime alerts when simmering is complete.
- **Executive Chef Pro-Tips**: Authentic culinary secrets for restaurant-quality flavor execution.

### 🥬 4. Fridge Raid / Pantry Alchemy Mode
- Got random ingredients in your kitchen? Type in items (*e.g., "tomatoes, eggs, garlic, sourdough"*) or add them as pantry tags.
- CraveCraft matches dishes using what you already have, reducing food waste and grocery runs.

### 🎡 5. Craving Roulette Wheel
- Can't decide what to eat? Spin the physics-driven Canvas Craving Wheel.
- Smooth ease-out deceleration, real-time auditory ticking, and confetti celebration upon landing on a winning meal.

### 🛒 6. Meal Planner & Smart Grocery Drawer
- Bookmark favorite recommendations to your personal Meal Planner.
- Batch export required ingredients into a categorized shopping list (*Produce, Protein, Dairy, Pantry*).
- One-click **Copy to Clipboard** (formatted for messaging apps) and **Printable Checklist** support.

### 🎙️ 7. Voice Dictation & Text-to-Speech
- **Voice Input (Web Speech Recognition API)**: Speak your craving directly into your microphone (*"Give me a spicy 15-minute high protein dinner"*).
- **Voice Chef (SpeechSynthesis API)**: Hear the AI Chef narrate recommendations and nutritional rationale out loud.

### 🔊 8. Web Audio Synthesizer
- Built-in procedural sound effects (click pops, gentle chimes, ticking wheel, and victory fanfare) with no external audio file dependencies.
- Toggle sound on/off anytime from the top navigation bar.

### 🌓 9. Modern Gourmand Design & Dark Mode
- Warm culinary color palette with glassmorphism, floating ambient particle canvas, and silky animations.
- Complete Light / Dark mode toggle with persistent local storage.

---

## 🚀 Live Demo & GitHub Pages Deployment

### Quick Deployment in 3 Steps:
1. **Fork or Push to GitHub**:
   Upload `index.html` to the root directory of your repository.
2. **Enable GitHub Pages**:
   - Go to your repository **Settings** > **Pages**.
   - Under **Build and deployment** > **Source**, choose **Deploy from a branch**.
   - Select `main` (or `master`) branch and folder `/ (root)`, then click **Save**.
3. **Enjoy your live site**:
   Your chatbot will be live at `https://<username>.github.io/<repository-name>/` in seconds!

---

## 🛠️ Technology Stack

| Layer | Technology |
|---|---|
| **Structure** | Semantic HTML5, ARIA accessibility attributes |
| **Styling** | Tailwind CSS (JIT CDN), Custom Food Gradients, Glassmorphism |
| **Typography** | Google Fonts (*Outfit*, *Plus Jakarta Sans*, *Playfair Display*) |
| **Icons** | Font Awesome 6 Pro / Free CDN |
| **Animations & Confetti** | Canvas-Confetti, CSS3 Keyframes, HTML5 Canvas particles |
| **Logic & NLP** | Modern Vanilla JavaScript (ES6+ Classes, State Management) |
| **APIs Used** | Web Speech API (Recognition & Synthesis), Web Audio API, LocalStorage |

---

## 💻 Local Preview

Simply double-click `index.html` to open it in any modern browser (Chrome, Edge, Firefox, Safari).

Alternatively, serve with a lightweight local server:
```bash
# Using Python 3
python -m http.server 8000

# Using Node (npx)
npx serve
```
Then visit `http://localhost:8000` in your browser.

---

## 🥗 Curated Recipe Database

The built-in culinary intelligence includes 24+ global handcrafted dishes across multiple categories:

- **Italian**: *Wild Mushroom & Truffle Pappardelle*, *Artisan Neapolitan Pizza Margherita*, *Creamy Tuscan Garlic Chicken*
- **Japanese & Asian**: *Kyoto-Style Shoyu Ramen*, *Hawaiian Spicy Ahi Poke Bowl*, *Spicy Kimchi Bokkeumbap*, *Steamed Crystal Har Gow*
- **Mediterranean & Middle Eastern**: *Pan-Seared Lemon Herb Salmon*, *Chickpea & Quinoa Mezze Bowl*, *Golden Herb Falafel*, *Skillet Shakshuka*, *Greek Lemon & Oregano Chicken*
- **Indian**: *Murgh Makhani (Butter Chicken)*, *Dhabha Style Creamy Palak Paneer*
- **Mexican & Latin**: *Slow-Braised Birria Beef Tacos*, *Char-Grilled Chimichurri Flank Steak*
- **American Comfort & High-Protein**: *Double Truffle Cheddar Smash Burger*, *Four-Cheese Lobster Macaroni*, *Smashed Avocado Tartine*
- **Thai & Vietnamese**: *Thai Coconut Green Curry*, *Lemongrass Tofu Banh Mi*
- **Desserts & Breakfast**: *Molten Chocolate Lava Cake*, *Uji Matcha Basque Cheesecake*, *Amazonian Acai Bowl*

---

## 📄 License

This project is open-source and released under the **MIT License**. Feel free to use, customize, and share!
