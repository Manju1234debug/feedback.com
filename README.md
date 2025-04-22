# feedback.com
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Feedback Receiver</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <div class="feedback-container">
    <h2>Send Us Your Feedback</h2>
    <form id="feedback-form">
      <input type="text" id="name" placeholder="Your Name" required />
      <input type="email" id="email" placeholder="Your Email" required />
      <textarea id="message" placeholder="Your Feedback" rows="5" required></textarea>
      <button type="submit">Submit Feedback</button>
    </form>
    <div id="confirmation" class="hidden">Thanks for your feedback!</div>
  </div>
  <script src="script.js"></script>
</body>
</html>
