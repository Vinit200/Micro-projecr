# Micro-projecr
# Title of the Project:Micro project on student enrollment 
# Description:

The above project is a student enrollment form that allows users to enter and store student data in a database using JSONPowerDB. It is implemented using HTML, JavaScript, and the Bootstrap framework.
The form consists of several input fields such as Student ID, Full Name, Class, Birth Date, Address, and Enrollment Date. The primary key for the database table is the Student ID.
The form provides three control buttons at the bottom: [Save], [Update], and [Reset].
Here's how the form works:
On page load or when the form is reset, the form is initialized with empty fields and the cursor is focused on the Student ID field. All other fields and buttons are disabled at this time.
If the user enters a Student ID that does not exist in the database, the [Save] and [Reset] buttons are enabled, and the cursor moves to the next field, allowing the user to enter data in the form.
The form performs basic validation to ensure that no fields are left empty before saving or updating data.
If the user clicks the [Save] button, the data entered in the form is saved to the JSONPowerDB database. The form is then reset to its initial state.
If the user enters a Student ID that exists in the database, the form retrieves the corresponding data and populates the form fields. The [Update] and [Reset] buttons are enabled, and the cursor moves to the next field, allowing the user to make changes.
If the user clicks the [Update] button, the data in the form is updated in the JSONPowerDB database. The form is then reset to its initial state.
The [Reset] button allows the user to reset the form to its initial state, discarding any entered or modified data.
The project makes use of the JSONPowerDB JavaScript library to interact with the JSONPowerDB database. The library provides methods for inserting and updating data in the database
# Benefits of using JsonPowerDB:
JsonPowerDB offers several benefits as a database solution:
#High Performance: JsonPowerDB is a high-performance database that offers extremely fast data retrieval and manipulation operations. It leverages the power of indexing and a built-in server-side query language to provide excellent query performance.
Schema-free: JsonPowerDB is schema-free, which means you don't need to define a fixed structure or schema for your data. You can store and retrieve JSON documents as they are, without the need for pre-defined tables or columns. This flexibility allows for easy data modeling and adaptability to changing requirements.
ACID Compliant: JsonPowerDB provides ACID (Atomicity, Consistency, Isolation, Durability) compliance for data integrity and reliability. It ensures that data transactions are processed reliably and consistently, even in the presence of concurrent operations or system failures.
Real-time Capabilities: JsonPowerDB supports real-time data synchronization and replication across multiple nodes and devices. It enables real-time data updates, making it suitable for applications that require live data streaming, collaboration, or real-time analytics.
# Release History (release of your JsonPowerDB related code on Github):
