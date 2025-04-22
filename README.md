# feedback.com
document.getElementById('feedback-form').addEventListener('submit', function (e) {
  e.preventDefault();

  const name = document.getElementById('name').value.trim();
  const email = document.getElementById('email').value.trim();
  const message = document.getElementById('message').value.trim();

  // Log feedback to console (simulate storing or sending to backend)
  console.log('Feedback Received:', { name, email, message });

  // Show confirmation
  document.getElementById('confirmation').classList.remove('hidden');

  // Clear form
  this.reset();
});
