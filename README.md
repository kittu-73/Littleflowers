<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Share Your Opinion - Little Flowers</title>
  <style>
    body {
      background: #0f0f1a;
      color: #e0e0e0;
      font-family: 'Segoe UI', sans-serif;
      padding: 2rem;
    }
    h1 {
      color: #4ae;
      text-align: center;
    }
    form {
      max-width: 600px;
      margin: 2rem auto;
      padding: 2rem;
      background: #1a1a2e;
      border-radius: 10px;
      box-shadow: 0 0 10px #4ae;
    }
    label {
      display: block;
      margin-top: 1rem;
      margin-bottom: 0.5rem;
    }
    input, textarea {
      width: 100%;
      padding: 0.8rem;
      border: none;
      border-radius: 5px;
      background: #2c2c3e;
      color: #fff;
      font-size: 1rem;
    }
    textarea {
      height: 150px;
      resize: vertical;
    }
    button {
      margin-top: 1.5rem;
      background: #4ae;
      color: #000;
      padding: 0.8rem 1.5rem;
      border: none;
      border-radius: 5px;
      font-weight: bold;
      cursor: pointer;
    }
    footer {
      text-align: center;
      margin-top: 2rem;
      font-size: 0.9rem;
      color: #888;
    }
  </style>
</head>
<body>

  <h1>Share Your Thoughts</h1>

  <form action="https://formsubmit.co/padmavathi.littleflowers@gmail.com" method="POST">
    <!-- FormSubmit automatically sends responses to your email -->

    <!-- Optional settings -->
    <input type="hidden" name="_captcha" value="false">
    <input type="hidden" name="_template" value="box">
    <input type="hidden" name="_subject" value="New Comment from Website">

    <label for="name">Your Name (optional):</label>
    <input type="text" id="name" name="name" placeholder="Enter your name">

    <label for="opinion">Your Opinion about Little Flowers:</label>
    <textarea id="opinion" name="opinion" placeholder="Type your feedback here..." required></textarea>

    <button type="submit">Submit Opinion</button>
  </form>

  <footer>
    &copy; <time datetime="2025">2025</time> Little Flowers School, Pendurthi — We value your voice.
  </footer>

</body>
</html>
