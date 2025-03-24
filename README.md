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
    <meta name="description" content="A sample HTML5 page demonstrating images, lists, tables, forms, and multimedia elements.">
    <title>Sample HTML5 Page</title>
</head>
<body>
    <!-- Header Section -->
    <header>
        <h1>Welcome to My Sample HTML5 Page</h1>
    </header>

    <!-- Ordered List with Roman Numerals -->
    <section>
        <h2>Ordered List with Roman Numerals</h2>
        <ol type="I">
            <li>First Item</li>
            <li>Second Item</li>
            <li>Third Item</li>
            <li>Fourth Item</li>
        </ol>
    </section>

    <!-- External Image from Pexels -->
    <section>
        <h2>External Image</h2>
        <img src="https://images.pexels.com/photos/1234567/pexels-photo-1234567.jpeg" alt="Sample Image from Pexels" width="500">
        <p>Image sourced from <a href="https://pexels.com" target="_blank">Pexels</a>.</p>
    </section>

    <!-- Table of Contacts -->
    <section>
        <h2>Contact Table</h2>
        <table border="1">
            <thead>
                <tr>
                    <th>Name</th>
                    <th>Address</th>
                    <th>Mobile</th>
                    <th>Email</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>John Doe</td>
                    <td>123 Main St, City</td>
                    <td>123-456-7890</td>
                    <td>john.doe@example.com</td>
                </tr>
                <tr>
                    <td>Jane Smith</td>
                    <td>456 Elm St, Town</td>
                    <td>234-567-8901</td>
                    <td>jane.smith@example.com</td>
                </tr>
                <tr>
                    <td>Alice Johnson</td>
                    <td>789 Oak St, Village</td>
                    <td>345-678-9012</td>
                    <td>alice.johnson@example.com</td>
                </tr>
                <tr>
                    <td>Bob Brown</td>
                    <td>101 Pine St, Hamlet</td>
                    <td>456-789-0123</td>
                    <td>bob.brown@example.com</td>
                </tr>
                <tr>
                    <td>Charlie Davis</td>
                    <td>202 Birch St, County</td>
                    <td>567-890-1234</td>
                    <td>charlie.davis@example.com</td>
                </tr>
            </tbody>
        </table>
    </section>

    <!-- Registration Form -->
    <section>
        <h2>Registration Form</h2>
        <form action="#" method="post">
            <!-- Name Field -->
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" placeholder="Enter your name" required>
            <br><br>

            <!-- Email Field -->
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" placeholder="Enter your email" required>
            <br><br>

            <!-- Password Field -->
            <label for="password">Password:</label>
            <input type="password" id="password" name="password" placeholder="Enter your password" required minlength="8">
            <br><br>

            <!-- Date Field -->
            <label for="dob">Date of Birth:</label>
            <input type="date" id="dob" name="dob" required>
            <br><br>

            <!-- Dropdown Menu -->
            <label for="gender">Gender:</label>
            <select id="gender" name="gender" required>
                <option value="" disabled selected>Select your gender</option>
                <option value="male">Male</option>
                <option value="female">Female</option>
                <option value="other">Other</option>
            </select>
            <br><br>

            <!-- Radio Buttons -->
            <label>Subscription Plan:</label>
            <input type="radio" id="plan1" name="plan" value="basic" required>
            <label for="plan1">Basic</label>
            <input type="radio" id="plan2" name="plan" value="premium">
            <label for="plan2">Premium</label>
            <br><br>

            <!-- Checkboxes -->
            <label>Interests:</label>
            <input type="checkbox" id="interest1" name="interest" value="sports">
            <label for="interest1">Sports</label>
            <input type="checkbox" id="interest2" name="interest" value="music">
            <label for="interest2">Music</label>
            <input type="checkbox" id="interest3" name="interest" value="reading">
            <label for="interest3">Reading</label>
            <br><br>

            <!-- Submit Button -->
            <input type="submit" value="Register">
        </form>
    </section>

    <!-- Multimedia Elements -->
    <section>
        <h2>Multimedia Elements</h2>
        <!-- Audio -->
        <h3>Audio Example</h3>
        <audio controls>
            <source src="sample-audio.mp3" type="audio/mpeg">
            Your browser does not support the audio element.
        </audio>
        <br><br>

        <!-- Video -->
        <h3>Video Example</h3>
        <video controls width="500">
            <source src="sample-video.mp4" type="video/mp4">
            Your browser does not support the video element.
        </video>
    </section>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2023 Sample HTML5 Page. All rights reserved.</p>
    </footer>
</body>
</html>
