<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width">
    <title>Pravah 2025 Coordinator Application</title>
</head>
<body>

    <h1>Pravah 2025 Coordinator Application</h1>

    <form action="/submit_application" method="POST">
        <label for="name">Full Name:</label><br>
        <input type="text" id="name" name="name" required><br><br>

        <label for="email">Email Address:</label><br>
        <input type="email" id="email" name="email" required><br><br>

        <label for="phone">Phone Number:</label><br>
        <input type="text" id="phone" name="phone" required><br><br>

        <label for="year">Year of Study:</label><br>
        <select id="year" name="year" required>
            <option value="1">First Year</option>
            <option value="2">Second Year</option>
            <option value="3">Third Year</option>
            <option value="4">Final Year</option>
        </select><br><br>
        
        <label for="branch">BRANCH:</label><br>
        <select id="year" name="year" required>
            <option value="1">CS </option>
            <option value="2">CS[AI]</option>
            <option value="3">CS[DS]</option>
            <option value="4">IT</option>
            option value="5">ELECTRICAL</option>
            <option value="6">ECE</option>
            <option value="7">MECHANICAL</option>
            <option value="8">CIVIL</option>
        </select><br><br>
        <label for="reason">Why do you want to be a coordinator for Pravah 2025?</label><br>
        <textarea id="reason" name="reason" rows="4" required></textarea><br><br>

        <input type="submit" value="Submit Application">
    </form>

</body>
</html>
