# 2340ExtraCredit

Reference Images: https://imgur.com/a/MvX0rbO 

Project Overview
WanderSync, is an itinerary app that helps simplify trip planning and management. The app allows users to collaborate by inviting others to join trip planning. In shared groups, participants can contribute comments to streamline communication and coordination.

Reflections
This course was an great learning experience for me and my team. Personally, I gained a better understanding of the importance of communication. Effective teamwork requires clear task allocation to avoid people working on the same thing. We struggled with this sometimes. Two team members unintentionally working on the same task and causing merge conflicts.

Through this project, I gained valuable technical skills. I became well versed in using Android Studio and learned about  fragments, which greatly helped with our UI design. Fragments allowed us to efficiently reuse a single Home Page across different sections, simplifying modifications.

Another significant takeaway was working with Firebase, a tool I had not used that much before. Using Realtime Database, we achieved seamless data synchronization, which played a pivotal role in enhancing our app. One of my key contributions was helping in developing the the database using Firebase. The class really helped me grasp the fundamentals.


Design & Architecture
Architecture
Our architecture focused on creating a smooth and intuitive user experience:

Frontend: Built using Android Studio to provide a visually appealing and user-friendly interface.
Backend: Powered by Firebase, enabling real-time data management and synchronization across devices. The Firebase Realtime Database served as the backbone for storing user information, managing reservations, and facilitating trip planning.
Design Patterns
We adopted several design patterns to ensure maintainable and scalable code:

Strategy Pattern:
This pattern allowed us to provide users with multiple sorting methods for their reservations, making trip organization more flexible.

Creator Pattern (GRASP):
We applied the Creator pattern by having the TripPlanner class generate instances of the Vacation class. This approach was logical, as TripPlanner holds all the detailed information needed by the Vacation class.

Class Diagram
Design Class Diagram
Diagram showcasing the structure of classes used in WanderSync.

Overall Design Diagram
High-level diagram illustrating the design and interactions within WanderSync.

WanderSync Contributors
A special thank you to our team members for their efforts and contributions:

Sammith D.: Firebase Integration
Tucker Ritti: Programming
Vasili Fovos: Debugging
Moksh Shah: Frontend Development
Samarth Tewari: Firebase Integration
