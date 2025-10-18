**Core Features (v1)**

1. Voice-based Interaction: You say “I wanna learn painting,” and it replies with voice like a friendly assistant.

2. Smart Search: Fetches top-rated local instructors (using Google Maps API).

3. Call Integration: Gives a list of numbers of top rated mentors. Lets you directly call listed mentors without leaving the app.

4. Feedback Loop: After you visit a place, it asks, “How was the session?” and tunes future results.

5. Top 5 Nearby Picks: Displays best 5 options (distance, rating, price, contact number).


**Tech stack**

**Frontend (Mobile App)**: React Native + Expo (fastest to learn + deploy)

**Voice Assistant:**

**1. Speech-to-text:** Google Speech API or Expo Speech

**2. Text-to-speech:** Expo Speech / react-native-tts

**Backend**: Node.js (Express) or Firebase

**Database**: Firebase Firestore or MongoDB

**APIs for search:** Google Places API

**Phone call integration:** React Native Linking module (Linking.openURL('tel:<number>'))

**Deployment**: Google Play (via Expo build)