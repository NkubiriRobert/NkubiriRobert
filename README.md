- 👋 Hi, I’m @NkubiriRobert
- 👀 I’m interested in coding ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on my project ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
NkubiriRobert/NkubiriRobert is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Classic Fashion Website - Registration</title>
<style>
  body { font-family: Arial, sans-serif; }
  .container { max-width: 500px; margin: auto; padding: 20px; }
  input[type=text], input[type=password], input[type=email] {
    width: 100%; padding: 15px; margin: 5px 0 20px 0; display: inline-block;
    border: 1px solid #ccc; box-sizing: border-box;
  }
  button { background-color: #4CAF50; color: white; padding: 14px 20px; margin: 8px 0;
    border: none; cursor: pointer; width: 100%; }
  button:hover { opacity: 0.8; }
  @media screen and (max-width: 600px) {
    .container { width: 100%; }
  }
</style>
</head>
<body>

<h2>Client Registration Form</h2>

<div class="container">
  <form action="/submit_registration" method="post">
    <label for="uname"><b>Username</b></label>
    <input type="text" placeholder="Enter Username" name="uname" required>

    <label for="email"><b>Email</b></label>
    <input type="email" placeholder="Enter Email" name="email" required>

    <label for="psw"><b>Password</b></label>
    <input type="password" placeholder="Enter Password" name="psw" required>

    <button type="submit">Register</button>
  </form>
</div>

</body>
</html>
