<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Quien es Eddie Miranda | Home</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <div class="container">
      <h1>Eddie Miranda</h1>
      <nav>
        <ul>
          <li><a href="index.html">Home</a></li>
          <li><a href="inclusion.html">Inclusion</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <section class="intro">
    <div class="container">
      <h2>Welcome to My Website</h2>
      <p>Hello, I'm known by name names, but Eddie seems to have been the one that stuck . ' you  begin to live life when you live for others' was something that Bruce Lee said and deeply resonates. My passion lies in being able to truly help those around me. ].</p>
      <img src="your-photo.jpg" alt="A photo of me" class="profile-photo">
    </div>
  </section>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Your Name | Inclusion</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <div class="container">
      <h1>Your Name</h1>
      <nav>
        <ul>
          <li><a href="index.html">Home</a></li>
          <li><a href="inclusion.html">Inclusion</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <section class="inclusion">
    <div class="container">
      <h2>What Inclusion Means to Me</h2>
      <p>Inclusion is the practice of creating environments where everyone, regardless of their background or abilities, feels valued, respected, and empowered. It's about breaking down barriers and ensuring everyone has a voice.</p>
      <img https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.prdaily.com%2Fresearch-backed-ways-to-foster-inclusion-in-your-workplace%2F&psig=AOvVaw3ge1jZmTpbhnXB90idA3zo&ust=1744742385638000&source=images&cd=vfe&opi=89978449&ved=0CBQQjRxqFwoTCMDe7oeW2IwDFQAAAAAdAAAAABAE">
    </div>
  </section>
</body>
</html>
/* Reset some default styles */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Arial, sans-serif;
  line-height: 1.6;
  background-color: #f9f9f9;
}

header {
  background-color: #333;
  color: white;
  padding: 10px 0;
}

header .container {
  width: 80%;
  margin: 0 auto;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

header nav ul {
  list-style-type: none;
  display: flex;
}

header nav ul li {
  margin-left: 20px;
}

header nav ul li a {
  color: white;
  text-decoration: none;
}

.container {
  width: 80%;
  margin: 0 auto;
}

h1 {
  font-size: 2.5rem;
}

h2 {
  font-size: 2rem;
  margin-top: 20px;
}

.intro, .inclusion {
  padding: 20px 0;
  text-align: center;
}

.profile-photo, .inclusion-photo {
  max-width: 100%;
  height: auto;
  margin-top: 20px;
}

