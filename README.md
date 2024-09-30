Location Sharing App
This mobile application allows users to share their real-time location with GPS tracking, helping friends, family, and co-workers stay connected.

I built this app using Flutter, with Firebase and Firestore handling user authentication and data management.

Download the APK
Download the APK here
Open the file on your Android device. If prompted, select Google Drive and then Package Installer.
Grant the necessary permissions to install and start using the application.
Requirements
Flutter
If you encounter a missing dependencies error, run:

bash
Copy code
flutter pub get
Features
Live Location Sharing: Share your live location with group members using location markers on Google Maps.


Create Multiple Groups: Easily form groups with friends or family and share locations within each group.


Flexible Sign-In Options: Users can sign in by creating an account or using their Google accounts.


Profile Customization: Edit your name and profile picture after creating an account to personalize your experience.


How Location Sharing Works
The app continuously updates the device's location using GPS through the Google Maps API.
Location data is updated in each user's Firestore document and reflected in the group documents.
Other group members read the Firestore document to display your location on their maps.
Next Steps to Personalize Your README:

Replace Placeholder Text and Links:

Update "your-apk-download-link-here" with the actual URL where your APK can be downloaded.
Modify any sections to highlight unique features or contributions you've made.
Add Your Own Screenshots:

Replace "path-to-your-screenshotX.png" with the paths to your actual screenshots.
Upload your images to your GitHub repository or an image hosting service.
Ensure the images clearly showcase your app's interface and features.
For example:

markdown
Copy code
![Live Location Sharing](https://github.com/yourusername/yourrepo/blob/main/screenshots/live_location_sharing.png)
Customize the Content:

Add any new features you've implemented.
Share your personal motivation or story behind creating the app.
Include acknowledgments if you've collaborated with others or used additional resources.
Update the Installation Instructions:

If there are specific steps or prerequisites unique to your version, include them.
Provide troubleshooting tips based on your experience.
Add License and Contact Information:

Specify the license under which you're releasing the app (e.g., MIT, Apache 2.0).
Provide a way for users to contact you with feedback or questions.
markdown
Copy code
## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

Created by [Your Name](your-email@example.com) - feel free to reach out!
Example of a Personalized Section:

markdown
Copy code
## Motivation

I developed this app to solve the problem of coordinating meetups with friends in crowded places. By sharing real-time locations, we can find each other easily without endless phone calls or messages.

## Upcoming Features

- **Geofencing Alerts**: Get notified when a group member enters or leaves a designated area.
- **Location History**: View the location history of group members for the past 24 hours.
- **Privacy Controls**: Set timers for how long your location is shared with each group.
