<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Newsletter Subscription Form</title>
</head>
<body>

<h2>Subscribe to Our Newsletter</h2>

<form id="subscriptionForm">
    <label for="email">Email:</label>
    <input type="email" id="email" name="email" required>
    <input type="button" value="Subscribe" onclick="submitForm()">
</form>

<script>
    function submitForm() {
        var email = document.getElementById("email").value;
        window.location.href = "mailto:adebanjodaniel13@gamail.com?subject=New%20Subscription&body=Email:%20" + email;
    }
</script>
