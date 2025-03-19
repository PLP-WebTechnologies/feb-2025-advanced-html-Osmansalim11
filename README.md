# Advanced HTML5 Elements and Forms

## Objectives
Implement HTML5 images, lists, tables, forms and input types.
Use form validation attributes.
Apply multimedia elements such as audio and video.

## Instructions

- Create an index.html file.
- Add an ordered list with roman numerals
- Add an external image from pexels.com
- Add a table of 5 contacts with; name, address, mobile and emails
- Add a registration form

>[!NOTE]
>  The registration form should have:
>- Name, email, password, and date fields.
>- A dropdown, radio buttons, and checkboxes.
>- Proper labels and placeholders.
>- Required fields and validation attributes.
>- Ensure proper indentation and commenting.
 
# Tasks
- Create a well-structured HTML5 document.
- Ensure semantic correctness.

Happy Coding! 💻✨




<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Index Page</title>
    <style>
        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
        }
        th, td {
            border: 1px solid black;
            padding: 10px;
            text-align: left;
        }
        th {
            background-color: #f2f2f2;
        }
    </style>
</head>
<body>
    <h1>Welcome to My Page</h1>
    
    <h2>Ordered List (Roman Numerals)</h2>
    <ol type="I">
        <li>First Item</li>
        <li>Second Item</li>
        <li>Third Item</li>
        <li>Fourth Item</li>
        <li>Fifth Item</li>
    </ol>
    
    <h2>External Image from Pexels</h2>
    <img src="https://images.pexels.com/photos/1234567/pexels-photo-1234567.jpeg" alt="Pexels Image" width="600">
    
    <h2>Contacts Table</h2>
    <table>
        <tr>
            <th>Name</th>
            <th>Address</th>
            <th>Mobile</th>
            <th>Email</th>
        </tr>
        <tr>
            <td>John Doe</td>
            <td>123 Main St</td>
            <td>+123456789</td>
            <td>john@example.com</td>
        </tr>
        <tr>
            <td>Jane Smith</td>
            <td>456 Elm St</td>
            <td>+987654321</td>
            <td>jane@example.com</td>
        </tr>
        <tr>
            <td>Michael Brown</td>
            <td>789 Oak St</td>
            <td>+456789123</td>
            <td>michael@example.com</td>
        </tr>
        <tr>
            <td>Sarah Johnson</td>
            <td>159 Pine St</td>
            <td>+321654987</td>
            <td>sarah@example.com</td>
        </tr>
        <tr>
            <td>David Wilson</td>
            <td>753 Maple St</td>
            <td>+741852963</td>
            <td>david@example.com</td>
        </tr>
    </table>
    
    <h2>Registration Form</h2>
    <form action="#" method="POST">
        <label for="name">Full Name:</label>
        <input type="text" id="name" name="name" required><br><br>
        
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required><br><br>
        
        <label for="phone">Phone:</label>
        <input type="tel" id="phone" name="phone" required><br><br>
        
        <label for="password">Password:</label>
        <input type="password" id="password" name="password" required><br><br>
        
        <label for="confirm_password">Confirm Password:</label>
        <input type="password" id="confirm_password" name="confirm_password" required><br><br>
        
        <input type="submit" value="Register">
    </form>
</body>
</html>

