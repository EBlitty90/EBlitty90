<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Your Name | Home</title>
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

  <section class="intro">
    <div class="container">
      <h2>Welcome to My Website</h2>
      <p>Hello, I'm [Your Name]. I'm passionate about [what you’re passionate about].</p>
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
      <img src="inclusion-photo.jpg" alt="Inclusion-related photo" class="inclusion-photo">
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

