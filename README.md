W Safe - A Women Safety Application
## _Feel Safe Everywhere_

W-Safe is a comprehensive women safety application designed to empower and protect women in times of distress. This Android application combines advanced features to provide a reliable safety solution. With W-Safe, women can feel more confident and secure, knowing that help is just a tap away. It is built using Java in Android Studio.The app enables users to quickly alert trusted contacts and share their real-time location during emergencies.

Features

- **One-Tap SOS Alert**  
  Instantly send an emergency alert to predefined contacts with your live location and a custom message.

- **Real-Time Location Sharing**  
  Continuously share your live GPS location with trusted contacts during emergencies.

- **Trusted Contacts Management**  
  Add or remove emergency contacts who will be notified in distress situations.

- **Location Tracking**  
  Background service to track and share location without keeping the app open.

- **Custom Alert Message**  
  Customize the emergency message to inform contacts about your situation.

- **Voice Activation (Optional)**  
  Trigger emergency alerts using voice commands or keywords.

- **Data Privacy & Security**  
  All personal data is stored securely and shared only with trusted contacts.

 Technologies Used

- **Frontend**: Java (Android Studio)
- **Backend (Optional)**: Firebase Realtime Database or Firestore
- **Location Services**: Google Maps API, Android LocationManager
- **Push Notifications**: Firebase Cloud Messaging (FCM)
- **Authentication**: Firebase Auth (optional)
- **Design**: XML, Material Design Components

 Installation & Setup

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/wsafe-app.git
   cd wsafe-app
Open in Android Studio

Open Android Studio

Select "Open an existing project" and choose the cloned folder

Set Up Firebase (if used)

Create a Firebase project

Download google-services.json and place it in app/ directory

Enable required services (Authentication, Realtime Database, FCM)

Run the App

Connect your Android device or start an emulator

Click Run

Project Structure
css
Copy
Edit
WSafe/
│
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/
│   │   │   ├── res/
│   │   │   └── AndroidManifest.xml
├── google-services.json
├── build.gradle
└── README.md


Future Enhancements
SMS-based alerts for non-internet zones
Hidden audio/video recording during emergency
Wearable device support (e.g., smartwatches)
Emergency history and analytics
Nearby police station locator
License

Acknowledgements
Google Maps Platform
Firebase
Android Developer Docs



### Key Features
- Shake Detector: Trigger emergency actions by shaking the device 5 times, such as sending SOS alerts and activating the siren.
- GPS Tracking: Retrieve the user's last known location and share it with registered contacts for quick assistance.
- SOS Messaging: Send distress messages to multiple registered contacts, notifying them of the user's situation and location.
- Siren Sound: Attract attention and deter potential threats by activating a loud siren sound.
- Find Nearby Police Stations and Hospitals: Quickly locate the nearest police stations and hospitals in case of emergencies.
- Women Safety Laws: Access information on relevant laws and regulations to stay informed and empowered.
- Self Defense Videos: Watch short instructional videos on self-defense techniques during critical situations.
- National Helplines: Directly call 5 national helpline numbers for immediate support and guidance.
- Panic button: Emergency Calling to a registered mobile number.

### Usage
1. Launch the W-Safe application on your Android device.
2. Grant Permissions and Register Emergency contacts. 
3. Familiarize yourself with the features and functionalities provided.
4. In case of an emergency, press the panic button or shake the device to activate the SOS alert.
5. The application will send distress messages to your registered contacts along with your current location.
6. Stay aware of nearby police stations and hospitals using the respective features.
7. Refer to the women safety laws and self-defense videos for additional support and knowledge.

