
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple HTML5 Page</title>
</head>
<body>

    <!-- Ordered List -->
    <h2>Topics</h2>
    <ol type="I">
        <li>HTML</li>
        <li>CSS</li>
        <li>JavaScript</li>
    </ol>

    <!-- External Image -->
    <h2>Image</h2>
    <img src="https://images.pexels.com/photos/1108099/pexels-photo-1108099.jpeg" alt="Nature Image" width="300">

    <!-- Contacts Table -->
    <h2>Contacts</h2>
    <table border="1">
        <tr>
            <th>Name</th>
            <th>Location</th>
            <th>Mobile</th>
            <th>Email</th>
        </tr>
        <tr>
            <td>Chinedu Okafor</td>
            <td>Lagos</td>
            <td>+234 803 123 4567</td>
            <td>chinedu.okafor@gmail.com</td>
        </tr>
        <tr>
            <td>Aisha Bello</td>
            <td>Abuja</td>
            <td>+234 806 987 6543</td>
            <td>aisha.bello@gmail.com</td>
        </tr>
    </table>

    <!-- Registration Form -->
    <h2>Register</h2>
    <form>
        <label>Name: <input type="text" required></label><br><br>
        <label>Email: <input type="email" required></label><br><br>
        <label>Password: <input type="password" required></label><br><br>
        <label>Birthdate: <input type="date" required></label><br><br>

        <!-- Gender -->
        <label>Gender:</label>
        <input type="radio" name="gender" value="male" required> Male
        <input type="radio" name="gender" value="female" required> Female<br><br>

        <!-- Country -->
        <label>Country:</label>
        <select required>
            <option value="">Select</option>
            <option value="ng">Nigeria</option>
            <option value="gh">Ghana</option>
        </select><br><br>

        <!-- Interests -->
        <label>Interests:</label>
        <input type="checkbox" value="coding"> Coding
        <input type="checkbox" value="music"> Music<br><br>

        <button type="submit">Register</button>
    </form>

</body>
</html># index2.html
