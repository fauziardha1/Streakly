
# Streakly - Habit Tracker App

Streakly is a habit tracker app designed to help users build, track, and maintain positive habits. The app empowers users to set goals, track their progress, and level up as they achieve their daily, weekly, or monthly targets. With intuitive UI, customizable reminders, and progress analytics, Streakly aims to motivate users towards consistent growth and self-improvement.

## Features

- **User Registration & Authentication**: Sign up and log in using email, Google, or Apple accounts.
- **Create & Customize Habits**: Personalize habits with names, frequencies, time of day, and categories (e.g., health, productivity).
- **Track Progress**: Visualize progress with charts and habit streaks for daily, weekly, and monthly views.
- **Reminders & Notifications**: Get notified about upcoming habits based on user preferences.
- **Dark Mode Support**: Choose between light and dark themes for a comfortable user experience.
- **Reward System**: Earn virtual rewards and badges for habit consistency.
- **Data Backup & Sync (Optional)**: Cloud-based data sync for access across multiple devices.
- **Share Progress**: Share achievements and streaks with friends and on social media.

## Tech Stack

- **Platform**: iOS (Swift)
- **Architecture**: Clean Architecture for modularity and maintainability
- **Database**: Realm or Core Data for efficient data storage
- **Notifications**: Local notifications using UNUserNotificationCenter
- **Analytics**: Built-in analytics for tracking user progress
- **Cloud Services**: Optional cloud sync for data backup and restoration

## Requirements

- **Xcode**: Version 12.0 or later
- **iOS Deployment Target**: iOS 12.0 or later
- **Swift**: Version 5.0 or later

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/fauziardha1/Streakly.git
   ```
2. **Open the Project**:
   - Open `Streakly.xcodeproj` or `Streakly.xcworkspace` in Xcode.

3. **Install Dependencies**:
   - If using CocoaPods or Swift Package Manager, run:
     ```bash
     pod install
     ```
     or configure packages via Xcode.

4. **Set Up Firebase (if using)**:
   - Add your `GoogleService-Info.plist` file to the project.
   - Follow Firebase setup documentation for iOS.

5. **Build and Run**:
   - Select your target device/emulator and click the **Run** button in Xcode.

## Usage

1. **Sign Up/Login**: Create an account using your email or a social login (Google/Apple).
2. **Create Habits**: Add and customize habits with different frequencies and reminders.
3. **Track Your Progress**: Mark habits as completed and visualize your progress through streaks and analytics.
4. **Set Notifications**: Enable notifications to receive daily or weekly habit reminders.
5. **Earn Rewards**: Achieve consistency to earn badges and level up.

## Project Structure

```
Streakly/
├── App/
│   ├── Delegates/
│   ├── Utilities/
│   └── Extensions/
├── Data/
│   ├── Models/
│   ├── Database/
│   └── Network/
├── Domain/
│   ├── Entities/
│   ├── UseCases/
│   └── Repositories/
├── Presentation/
│   ├── ViewControllers/
│   ├── Views/
│   └── ViewModels/
└── Resources/
    ├── Assets/
    ├── Localizations/
    └── Storyboards/
```

## Contributing

Contributions are welcome! Follow these steps:

1. **Fork the Repository**
2. **Create a Branch** (`feature/new-feature` or `fix/bug-fix`)
3. **Commit Your Changes**: Ensure your code follows the coding guidelines.
4. **Push to the Branch**: Submit a pull request.

## Roadmap

- [ ] Complete user authentication and sign-up flows
- [ ] Implement habit creation and customization features
- [ ] Integrate notifications for habit reminders
- [ ] Add analytics for tracking user progress
- [ ] Implement dark mode support
- [ ] Launch MVP and gather user feedback

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Contact

For questions or support, please contact [fauziardasaputra@gmail.com].

---

Happy coding with Streakly! 🌱🚀

