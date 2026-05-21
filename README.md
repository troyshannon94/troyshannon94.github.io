# troyshannon94.github.io
Static test web page. The button below will send 
<h1>

  <button id="my-button" onclick="trackButtonClick()">Click Me</button>

<script>
function trackButtonClick() {
  gtag('event', 'button_clicked', {
    'button_name': 'Sign Up Button',
    'location': 'Homepage'
  });
}
</script>

</h1>
