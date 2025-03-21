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
    <title>Registration Page</title>
</head>
<body>
    <!-- Header Section -->
    <header>
        <h1>Welcome to Our Website</h1>
    </header>
    
    <!-- Ordered List with Roman Numerals -->
    <section>
        <h2>Steps to Register</h2>
        <ol type="I">
            <li>Fill out the registration form</li>
            <li>Verify your email</li>
            <li>Login to your account</li>
            <li>Start using our services</li>
        </ol>
    </section>
    
    <!-- External Image from Pexels -->
    <section>
        <h2>Our Vision</h2>
        <img src="https://images.pexels.com/photos/3183197/pexels-photo-3183197.jpeg" alt="Teamwork Image" width="600">
    </section>
    
    <!-- Contacts Table -->
    <section>
        <h2>Contact List</h2>
        <table border="1">
            <tr>
                <th>Name</th>
                <th>Address</th>
                <th>Mobile</th>
                <th>Email</th>
            </tr>
            <tr>
                <td>Eva Akide</td>
                <td>111, Nairobi</td>
                <td>+254700307469</td>
                <td>evaayoti@gmail.com</td>
            </tr>
            <tr>
                <td>Terry Tess</td>
                <td>456, arusha</td>
                <td>+9876543210</td>
                <td>terrytess@gmail.com</td>
            </tr>
            <tr>
                <td>Mike Brown</td>
                <td>789 Boulevard, City</td>
                <td>+1122334455</td>
                <td>mike@example.com</td>
            </tr>
            <tr>
                <td>Sarah Lee</td>
                <td>101 Road, City</td>
                <td>+2233445566</td>
                <td>sarah@example.com</td>
            </tr>
            <tr>
                <td>David Wilson</td>
                <td>202, johanessburg</td>
                <td>+3344556677</td>
                <td>david@gmail.com</td>
            </tr>
        </table>
    </section>
    
    <!-- Registration Form -->
    <section>
        <h2>Register Here</h2>
        <form>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" placeholder="Enter your full name" required><br><br>
            
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" placeholder="Enter your email" required><br><br>
            
            <label for="password">Password:</label>
            <input type="password" id="password" name="password" placeholder="Enter your password" required minlength="6"><br><br>
            
            <label for="dob">Date of Birth:</label>
            <input type="date" id="dob" name="dob" required><br><br>
            
            <label for="gender">Gender:</label><br>
            <input type="radio" id="male" name="gender" value="male" required> Male<br>
            <input type="radio" id="female" name="gender" value="female"> Female<br>
            <input type="radio" id="other" name="gender" value="other"> Other<br><br>
            
            <label for="country">Country:</label>
            <select id="country" name="country" required>
                <option value="">Select your country</option>
                <option value="KENYA">KENYA</option>
                <option value="TANZANIA">TANZANIA</option>
                <option value="SOUTH AFRICA">SOUTH AFRICA</option>
                <option value="NIGERIA">NIGERIA</option>
            </select><br><br>
            
            <label>Interests:</label><br>
            <input type="checkbox" name="interests" value="sports"> Sports<br>
            <input type="checkbox" name="interests" value="music"> Music<br>
            <input type="checkbox" name="interests" value="technology"> Technology<br><br>
            
            <button type="submit">Register</button>
        </form>
    </section>
    
    <!-- Footer -->
    <footer>
        <p>Contact us at: info@gmail.com</p>
    </footer>
</body>
</html>

