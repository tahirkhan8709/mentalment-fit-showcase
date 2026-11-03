<p align="center">
  <img src="screenshots/logo.png" width="180" alt="Mentalmente Fit logo">
</p>

<h1 align="center">MENTALMENTE FIT</h1>
<p align="center"><b>by Dr. Pedrito</b><br>
A premium AI-powered health, fitness and nutrition mentor app.</p>

> This repository is a **showcase** (screenshots and feature overview). The source code is private.

---

## About

Mentalmente Fit is a mobile app (Android, built with Flutter) that combines daily health tracking, an AI health coach and direct access to a real mentor, Dr. Pedrito. It has a bold dark and yellow brand identity with a matching light theme.

| Splash (dark) | Splash (light) |
|---|---|
| <img src="screenshots/splash-dark.png" width="240"> | <img src="screenshots/splash-light.png" width="240"> |

## Features

### Daily tracking
- **Calories and macros:** a progress ring plus Protein, Carbs and Fats bars against a personal daily target.
- **Steps:** live step counter from the phone sensor.
- **Water intake:** one-tap glass counter with instant response.
- **Habit checklist:** sleep, supplements and meditation.

| Login | Home (dark) | Home (light) |
|---|---|---|
| <img src="screenshots/login.png" width="220"> | <img src="screenshots/home-dark.png" width="220"> | <img src="screenshots/home-light.png" width="220"> |

### Smart food scanner
- **Barcode mode:** scan a packaged product and get real nutrition data and a health score.
- **Food photo mode:** photograph a meal and AI estimates the dish, calories and macros. Results are estimates and can be added to the meal log in one tap.

| Barcode | Food photo | AI result |
|---|---|---|
| <img src="screenshots/scan-barcode.png" width="220"> | <img src="screenshots/scan-food-photo.png" width="220"> | <img src="screenshots/food-result.png" width="220"> |

### Nutrition log
Meals are logged for Breakfast, Lunch, Dinner and Snacks, by search, barcode or photo, with a day-by-day view.

<img src="screenshots/nutrition.png" width="220">

### AI Health Coach
- Chat with an AI coach in Dr. Pedrito's style, with voice input.
- Safety logic for red-flag symptoms (for example chest pain): the coach tells the user to seek urgent medical help.
- Stop generation, clear chat, and a **History** of past conversations that can be continued or deleted.

| Coach | History | Coach (light) |
|---|---|---|
| <img src="screenshots/coach.png" width="220"> | <img src="screenshots/coach-history.png" width="220"> | <img src="screenshots/coach-light.png" width="220"> |

### Mentor booking
Users can book a consultation with Dr. Pedrito, choosing a plan (Single, Monthly, VIP) and a mode (In-person, Video, WhatsApp). Bookings show status, WhatsApp contact and the doctor's notes.

<img src="screenshots/booking.png" width="220">

### Profile and membership
- Profile photo with view and remove options, editable health profile and personalised daily targets.
- Dark, Light or System appearance.
- Membership levels (Free, Premium, VIP) managed by the admin.
- Sign in with email or **Continue with Google**.

| Profile (dark) | Profile (light) |
|---|---|
| <img src="screenshots/profile-dark.png" width="220"> | <img src="screenshots/profile-light.png" width="220"> |

## Admin panel

A separate role-protected area for the mentor/admin:

- **Dashboard:** total users, new today, pending bookings, referrals and recent bookings.
- **Bookings:** confirm, complete or cancel consultations and add notes.
- **Users:** view users and set their membership.
- **Referrals, Announcements and Settings:** manage referrals, send in-app announcements and edit the weekly workout plan.

| Dashboard | Bookings | Users and membership |
|---|---|---|
| <img src="screenshots/admin-dashboard.png" width="220"> | <img src="screenshots/admin-bookings.png" width="220"> | <img src="screenshots/admin-users.png" width="220"> |

## Tech stack

- **Flutter** and **Dart**, Riverpod for state, go_router for navigation
- **Firebase:** Authentication (email and Google), Cloud Firestore with security rules, App Check
- **Gemini** (via Firebase AI) for the coach and food photo analysis
- **Open Food Facts** for barcode product data
- **Cloudinary** for profile photos
- Device sensors and camera: step counter, barcode scanner, image picker, speech to text

## Disclaimer

The app provides general wellness guidance and is not a substitute for professional medical advice. AI food estimates are approximate.

---

<p align="center">Built by <a href="https://github.com/tahirkhan8709">Tahir Khan</a></p>
