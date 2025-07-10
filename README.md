# Food Delivery App

![Food Delivery App Banner](assets/images/banner.png)

A modern, feature-rich food delivery application built with Flutter that connects hungry customers with local restaurants. Order your favorite meals with just a few taps!

## Features

- **User Authentication**: Secure signup/login with email, phone, or social accounts
- **Restaurant Discovery**: Browse nearby restaurants with advanced filtering options
- **Menu Browsing**: View complete menus with detailed item descriptions and images
- **Customizable Orders**: Add special instructions and customize food items
- **Real-time Order Tracking**: Track your food from preparation to delivery
- **Multiple Payment Methods**: Credit/debit cards, digital wallets, and cash on delivery
- **Loyalty Program**: Earn points and redeem rewards
- **Ratings & Reviews**: Rate restaurants and delivery experience
- **Order History**: View past orders and easily reorder favorites
- **Address Management**: Save multiple delivery locations
- **Promo Codes**: Apply discount codes for special offers
- **In-app Chat**: Communicate with customer service or delivery personnel

## Screenshots

<div style="display: flex; flex-wrap: wrap; gap: 10px;">
  <img src="screenshots/login_screen.png" width="200" alt="Login Screen">
  <img src="screenshots/home_screen.png" width="200" alt="Home Screen">
  <img src="screenshots/restaurant_details.png" width="200" alt="Restaurant Details">
  <img src="screenshots/cart_screen.png" width="200" alt="Cart Screen">
  <img src="screenshots/checkout_screen.png" width="200" alt="Checkout Screen">
  <img src="screenshots/order_tracking.png" width="200" alt="Order Tracking">
</div>

## Technology Stack

- **Frontend**: Flutter/Dart (98.9% of codebase)
- **State Management**: Provider/BLoC pattern
- **Backend**: Firebase (Authentication, Firestore, Functions)
- **Maps & Location**: Google Maps API
- **Payment Processing**: Stripe/PayPal integration
- **Notifications**: Firebase Cloud Messaging
- **Analytics**: Firebase Analytics

## Getting Started

### Prerequisites

- Flutter SDK (2.5.0 or higher)
- Dart SDK (2.14.0 or higher)
- Android Studio / VS Code with Flutter extensions
- Firebase account
- Google Maps API key

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/AbdullahManzoor-code/food_delivery_App.git
   ```

2. Navigate to the project directory:
   ```bash
   cd food_delivery_App
   ```

3. Install dependencies:
   ```bash
   flutter pub get
   ```

4. Configure Firebase:
   - Create a new Firebase project
   - Add Android and iOS apps in Firebase console
   - Download and place `google-services.json` in `android/app`
   - Download and place `GoogleService-Info.plist` in `ios/Runner`

5. Set up your Google Maps API key:
   - Create an API key in Google Cloud Console
   - Add it to `android/app/src/main/AndroidManifest.xml`
   - Add it to `ios/Runner/AppDelegate.swift`
   - Create a `.env` file with your API key

6. Run the app:
   ```bash
   flutter run
   ```

## Project Structure

```
lib/
├── config/         # App configuration, themes, routes
├── core/           # Core utilities and base classes
├── data/           # Data models and repositories
├── features/       # Feature modules
│   ├── auth/       # Authentication screens and logic
│   ├── home/       # Home screen and related features
│   ├── restaurant/ # Restaurant listing and details
│   ├── cart/       # Shopping cart functionality
│   ├── checkout/   # Order placement and payment
│   └── profile/    # User profile management
├── services/       # API services and external integrations
├── utils/          # Helper functions
├── widgets/        # Reusable UI components
└── main.dart       # Entry point
```

## Usage

### For Customers

1. Create an account or log in
2. Browse restaurants or search for specific cuisine
3. Select a restaurant to view its menu
4. Add items to your cart
5. Proceed to checkout
6. Select delivery address and payment method
7. Track your order in real-time
8. Enjoy your meal and leave a review!

### For Developers

- Check out the `docs` folder for detailed documentation
- Run `flutter test` to execute the test suite
- Use `flutter build apk` or `flutter build ios` to generate release builds

## Contributing

We welcome contributions to improve the Food Delivery App:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

Please ensure your code follows our coding standards and includes appropriate tests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

Abdullah Manzoor - [GitHub Profile](https://github.com/AbdullahManzoor-code)

Project Link: [https://github.com/AbdullahManzoor-code/food_delivery_App](https://github.com/AbdullahManzoor-code/food_delivery_App)
