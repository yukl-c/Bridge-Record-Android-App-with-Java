# Bridge-Record-Android-App-with-Java
Bridge Record Android App with Java

Functionality of my app:
- Uses a linked list as the database for easy implementation, insertion, and deletion.
- Defines data types for bridge name, inspection date, status index, and location.
- Uses a string array for status with options: null, good, moderate, and poor.
- Packs input data into a bridge class and adds it to the linked list.

Overall layout and design:
- App logo is a yellow bridge on a black background.
- Homepage includes a picture, list of buttons, and a "?" button for guidance.
- Pages have a back button to return to the homepage.

Main page:
- Displays the app logo.
  
Adding bridge records:
- Accessible through the "Add Record" row on the homepage and the "+" button in the toolbar.
- Input fields for bridge name, inspection date, status, and location.
- Validates input and adds it to the linked list.

Viewing the summary list of reports:
- Shows the count of bridge repair reports using the length of the linked list.
- Displays records using the linked list and a ListView.
  
Viewing/editing a bridge record:
- Clicking on a record in the list displays its details for editing.

Deleting bridge record:
- Long pressing a record displays an alert dialog to confirm deletion.
- Clicking the trash button on the toolbar deletes all records.
