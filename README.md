Worksync – Role-Based Task Management App
📌 Overview

Worksync is a Flutter-based productivity and task management application designed to streamline collaboration within organizations. It provides role-based dashboards for Admins, Supervisors, and Employees, ensuring structured workflows, secure access, and efficient task monitoring.

✨ Features

Role-Based Dashboards

Admin: Manage users, approve/reject requests, and monitor overall tasks.

Supervisor: Assign tasks, review progress, and manage employees.

Employee: View tasks, submit updates, and collaborate with team members.

Secure Access Control – Firestore rules enforce role-based access to data and documents.

User Request & Approval System – Admins can approve/reject user registrations and trigger automated feedback.

Scalable Task Management – Assign, monitor, and complete tasks in real-time.

Clean Navigation – Centralized role-based routing and dashboard navigation.

🛠️ Tech Stack

Frontend: Flutter, Dart

Backend: Firebase, Cloud Functions

Database: Firestore

UI: Bootstrap (integrated with Flutter styling where required)

🚀 Installation & Setup

Clone the repository:

git clone https://github.com/your-username/worksync.git
cd worksync


Install dependencies:

flutter pub get


Connect your project to Firebase:

Add your google-services.json (Android) and GoogleService-Info.plist (iOS).

Enable Authentication, Firestore, and Cloud Functions in Firebase Console.

Run the app:

flutter run


🤝 Contribution

Contributions are welcome! Feel free to open an issue or submit a pull request.

📄 License

This project is licensed under the MIT License.
