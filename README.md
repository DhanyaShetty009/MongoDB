### **MongoDB Student Management Script**

This script performs CRUD operations on a MongoDB database using the `pymongo` library.

## **Features:**

1. **Insert One Record**: Add a single student's details (name, age, email, state) to the database.
2. **Insert Multiple Records**: Add multiple students' details up to a specified limit.
3. **Find All Records**: Retrieve and display all student records.
4. **Find One Record**: Search for a student by their name.
5. **Update One Record**: Modify a specific field (name, age, email, state) of a student's record.
6. **Delete One Record**: Remove a student's record by their name.
7. **Drop Collection**: Delete the entire `students` collection.

## **Usage:**

1. **Install Dependencies**:
   - Install MongoDB and ensure it is running.
   - Install `pymongo`:
     ```bash
     pip install pymongo
     ```

2. **Run the Script**:
   - Save the script as `mongo_ex.py`.
   - Execute it in the terminal:
     ```bash
     python mongo_ex.py
     ```

3. **Input Format**:
   - For student details: `name, age, email, state`.

## Example

### Insert One Record:
Enter student details (format: name, age, email, state): John, 20, john@example.com, California
Insert Multiple Records:

Enter student details: Alice, 22, alice@example.com, New York
Enter student details: Bob, 23, bob@example.com, Texas
Update One Record:

Enter the name of the user to update: John
Enter the field to update: age
Enter the new value for age: 21

Drop Collection:
Type 'drop' to delete the entire 'students' collection: drop



### **Dependencies:**

-Python 3.x

-MongoDB

-pymongo
