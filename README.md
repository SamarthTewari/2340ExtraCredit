# 2340ExtraCredit

Project Overview
Our project, WanderSync, is an itinerary app designed to simplify trip planning and management. It offers an array of features to enhance the user experience. For example, users can organize trips by inputting locations, destinations, and trip durations. Additionally, the app allows users to collaborate by inviting others to join trip planning. In shared groups, participants can contribute comments to streamline communication and coordination.

Reflections
This course was an incredible learning experience for all of us. Personally, I gained a deeper understanding of the importance of communication in software engineering. Effective teamwork requires clear task allocation to avoid overlapping efforts. At times, we struggled with this, leading to two team members unintentionally working on the same task and causing merge conflicts.

Through this project, I also gained valuable technical skills. For instance, I became proficient in using Android Studio and learned about the concept of fragments, which greatly streamlined our UI design. Fragments allowed us to efficiently reuse a single Home Page across different sections, simplifying modifications.

Another significant takeaway was working with Firebase, a tool I had not used before. Leveraging Realtime Database, we achieved seamless data synchronization, which played a pivotal role in enhancing our app. One of my key contributions was developing the sign-in feature using Firebase. Although it was initially challenging, Professor Roy's instructional videos were instrumental in helping me grasp the fundamentals.

Design & Architecture
Architecture
Our app architecture focused on creating a smooth and intuitive user experience:

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
