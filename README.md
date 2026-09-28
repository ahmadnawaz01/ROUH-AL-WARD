# Rouh Al Ward Spa & Wellness - Luxury WhatsApp Landing Page

A luxury, high-converting animated landing page designed specifically for **Rouh Al Ward Spa & Wellness (روح الورد)** in Riyadh. Featuring a dark obsidian and metallic gold aesthetic matching the official brand emblem, animated ambient particle physics, bilingual English/Arabic support, and one-tap WhatsApp appointment booking configured via `.env`.

---

## 🌟 Key Features

1. **Exact Brand Matching**:
   - Palette inspired by the gold and obsidian logo: deep midnight backgrounds, warm amber glows, and metallic gold accents.
   - Dual-ring rotating halo around the brand emblem with subtle depth animations.
   - Luxury serif and Arabic typography (`Cinzel`, `Cormorant Garamond`, `Cairo`, `Amiri`).

2. **Full Environment Configuration (`.env`)**:
   - WhatsApp phone number: `VITE_WHATSAPP_NUMBER`
   - Default pre-filled booking message: `VITE_DEFAULT_MESSAGE`
   - Brand name, tagline, and location in English & Arabic.

3. **Interactive WhatsApp CTAs**:
   - **Primary CTA Button**: Pulsating gold/emerald glow with shimmer effects and ripple feedback.
   - **Special Sunday Offer Banner**: Direct booking button with the promotional package pre-filled (*أول زيارتين ٢٥٠ ريال / الثالثة ٣٠٠ ريال*).
   - **Quick Inquiry Chips**: 1-click topics (Booking, Sunday Offer, Full Menu & Pricing, Location & Hours) that dynamically update the WhatsApp chat URL.
   - **Direct Copy Phone Number**: With tooltip confirmation.

4. **Bilingual Support (EN / AR)**:
   - Real-time instant language switcher toggling full Arabic RTL (Right-to-Left) and English layouts.

5. **Ambient Particle System**:
   - Lightweight canvas rendering golden embers/sparkles floating gently in the background.

---

## 🚀 Quick Start

### 1. Configure Environment Variables
Edit [.env](file:///d:/Github/whatsapp%20landing%20page/.env) to set your phone number and message:

```env
VITE_WHATSAPP_NUMBER=966548060848
VITE_DEFAULT_MESSAGE=Hello Rouh Al Ward Spa & Wellness, I would like to inquire about booking an appointment.

VITE_COMPANY_NAME=ROUH AL WARD
VITE_COMPANY_TAGLINE=SPA & WELLNESS
VITE_COMPANY_LOCATION=RIYADH
VITE_COMPANY_NAME_AR=روح الورد
```

### 2. Run Development Server
```bash
npm install
npm run dev
```
Open [http://localhost:5173](http://localhost:5173) in your browser.

### 3. Build for Production
```bash
npm run build
```
The optimized production bundle will be generated in the `dist/` directory, ready to deploy to Vercel, Netlify, Cloudflare Pages, or any web host.
