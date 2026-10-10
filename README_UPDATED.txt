EduNexus Swing project - updated

Changes:
- Student Management: Search and View All show database records in a JTable window.
- Attendance: Search and View All show database records in a JTable window.
- Fees: Search and View All show database records in a JTable window.
- Notices: View Notices shows database records in a JTable window.
- Added com.edunexus.gui.TableViewer.java to reuse the JTable display code.

How to open:
1. Extract this ZIP.
2. In Eclipse choose File > Import > Existing Projects into Workspace.
3. Select the extracted EduNexus folder and finish.
4. Check src/com/edunexus/util/DBConnection.java and make sure the password matches your local MySQL root password.
5. Make sure the edunexus database and tables exist, then run your existing login/main class.

Note: The code compiles with the Java compiler. Database operations require MySQL to be running and the MySQL Connector/J JAR to be configured in Eclipse.
