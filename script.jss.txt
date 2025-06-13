function handleSubmit(event) {
  event.preventDefault();
  const name = document.getElementById("name").value;
  const message = document.getElementById("message").value;
  alert(`Thank you, ${name}! Your message: "${message}" has been received.`);
}
