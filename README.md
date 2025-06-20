# Engaging Student Support System (ESSS)

Scenario:
This project addresses the low engagement and usability challenges of existing student support systems at UCT. It is designed to help first-year students connect, collaborate, and access peer-based support in a more engaging, personalised environment. The system functions as a social platform where students can join interest-based groups, participate in discussions, and discover peers with shared academic backgrounds.

Specifications:
- Built using React Native and Javascript principles
- Integrated with Firebase for real-time data handling, authentication, and Firestore (NoSQL) database

Key features include:
- User registration & login with email-based authentication
- User profiles displaying academic year, degree, hometown, and interests
- Group system: students join predefined groups and view group members
- Discussion forums within each group using a third-party rich text discussion board component
- Forum posts and replies stored and retrieved using Firestore collections and snapshot listeners
- Backend logic centralised in a Firebase API module with helper methods for reads/writes
