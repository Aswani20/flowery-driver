# 🌸 Flowery Driver App

A modern **Flutter Flowery application** built with Clean Architecture.  
The app allows driver to browse orders, add pick it up from store, and manage deliver it to user.

[![Flutter](https://img.shields.io/badge/Flutter-3.24-blue?logo=flutter)](https://flutter.dev)
[![Stars](https://img.shields.io/github/stars/Aswani20/flowery-driver?style=social)](https://github.com/Aswani20/flowery-driver/stargazers)
[![Issues](https://img.shields.io/github/issues/Aswani20/flowery-driver)](https://github.com/Aswani20/flowery-driver/issues)
[![License](https://img.shields.io/github/license/Aswani20/flowery-driver)](LICENSE)
[![Forks](https://img.shields.io/github/forks/Aswani20/flowery-driver?style=social)](https://github.com/Aswani20/flowery-driver/network/members)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/Aswani20/flowery-driver/pulls)
[![Made with Love](https://img.shields.io/badge/Made%20with-%F0%9F%92%9F-pink)](https://github.com/Aswani20/flowery-driver)


## 📱 Features
- 🔑 User authentication (Signup / Login with JWT)
- 🛒 pick, deliver, orders from the stor to user
- 💳 Checkout process
- 📦 Product listing and details
- 🎨 Responsive UI with Material Design
- 🧱 Clean Architecture (API, Data, Domain, Presentation layers)


## 📡 API Documentation

This app communicates with a custom backend to manage products, carts, and orders.  


## Screenshots

Here are some screenshots of the app in action:

<p align="center">
  <img src="assets/screenshots/login.png" alt="Login Screen" width="20%" />
  <img src="assets/screenshots/apply1.png" alt="Register Screen" width="20%" />
  <img src="assets/screenshots/apply2.png" alt="Register Screen" width="20%" />
  <img src="assets/screenshots/forget_password.png" alt="Forget Screen" width="20%" />
  <img src="assets/screenshots/otp.png" alt="Otp Screen" width="20%" />
  <img src="assets/screenshots/success_otp.png" alt="Otp Screen" width="20%" />
  <img src="assets/screenshots/home_tab.png" alt="Home Screen" width="20%" />
  <img src="assets/screenshots/reject_order.png" alt="Reject Order" width="20%" />
  <img src="assets/screenshots/accept_order.png" alt="Accept Order" width="20%" />
  <img src="assets/screenshots/my_orders.png" alt="My Orders Screen" width="20%" />
  <img src="assets/screenshots/order_details.png" alt="Order Details Screen" width="20%" />
  <img src="assets/screenshots/profile_tab.png" alt="Profile Screen" width="20%" />
  <img src="assets/screenshots/edit_profile.png" alt="Edit Profile Screen" width="20%" />
  <img src="assets/screenshots/language.png" alt="Language creen" width="20%" />
</p>


## 🚀 Getting Started

### Prerequisites
- [Flutter SDK](https://docs.flutter.dev/get-started/install) (>= 3.x)
- Android Studio / VSCode
- Emulator or physical device

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/Aswani20/flowery-driver.git
    ```

2. Navigate to the project directory:
    ```bash
    cd flowery-driver
    ```

3. Install dependencies:
    ```bash
    flutter pub get
    ```

4. Run the app:
    ```bash
    flutter run
    ```

### Testing

1. Run the app:

    ```bash
    flutter test
    ```

## 🤝 Contributing

- Fork the repo

- Create your feature branch (git checkout -b feature/YourFeature)

- Commit changes (git commit -m 'Add some feature')

- Push to branch (git push origin feature/YourFeature)

- Open a Pull Request

## 📜 License

Distributed under the MIT License. See LICENSE for more information.


## 👨‍💻 Author

1. Abdelrahman Youssef
2. Moataz Ebrahim
3. Wasim Ghonim
4. Yassen Ahmed


## Folder Structure

```text
lib/
│
├── core/
│   ├── aiLayer/
│   ├── classes/
│   ├── config/
│   ├── di/
│   ├── enum/
│   ├── errors/
│   ├── functions/
│   ├── helpers/
│   ├── localization/
│   ├── models/
│   ├── services/
│   ├── utils/
│   └── widgets/
│
├── features/
│   ├── auth/
│   ├── mainLayout/
│   ├── orderDetails/
│   └── resetPassword/
│
├── firebase_options.dart
└── main.dart
