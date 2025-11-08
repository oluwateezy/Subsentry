# Frontend (Client), React (or Vanilla JS/HTML) + Tailwind CSS, Fast, modular, and responsive.
# Backend/DB Google Firebase (Auth, Firestore), Secure user authentication and real-time database., Managed via Firebase console
# Hosting: Firebase Hosting
# Notifications: Firebase Cloud Messaging + Email API
# Core Data Model (Firestore)
# /artifacts/{appId}/users/{userId}/subscriptions
# Subscription Document Structure  
# {"id": "subscription-001",
  "name": "Netflix Premium",
  "cost": 19.99,
  "currency": "USD",
  "cycle": "monthly",
  "startDate": "2024-01-15T00:00:00Z",
  "nextRenewalDate": "2025-11-15T00:00:00Z",
  "category": "Entertainment",
  "userId": "johndoe-uid-12345",
  "isActive": true,
  "addedAt": "2025-10-20T10:30:00Z"}
