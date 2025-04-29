# Mobile Application Plan

## Platforms Targeted

- **Android 8.0+** – Fully supported
- **iOS 12+** – Emulator tested, real device partially

## Functionality Breakdown

| Feature               | Status  | Notes                      |
| --------------------- | ------- | -------------------------- |
| Medication scheduler  | Done    | Integrated with backend    |
| Notifications (FCM)   | Done    | Firebase setup successful  |
| Reminder edit support | Done    | Integrated with update API |
| Dose missed tracking  | Pending | Placeholder created        |

## Deployment Tools

- Expo Go for live testing
- Firebase Test Lab (token testing)
- SQLite emulator inspection for history

## Challenges

- Push notification test messages required real device
- iOS test limited due to Firebase key constraints
