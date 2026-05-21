# troyshannon94.github.io
<h1>
Static test web page. The button below will send an event to GA4
</h1>

<h2>
  
  <button id="my-button" onclick="trackButtonClick()">Click Me</button>

  <!-- Google tag (gtag.js) -->
  <script async src="https://www.googletagmanager.com/gtag/js?id=G-LYWL8RBVFW"></script>
  <script>
    window.dataLayer = window.dataLayer || [];
    function gtag(){dataLayer.push(arguments);}
    gtag('js', new Date());

    gtag('config', 'G-LYWL8RBVFW');
  </script>

  <script>
  function trackButtonClick() {
    gtag('event', 'button_clicked', {
      'button_name': 'Sign Up Button',
      'location': 'Homepage'
    });
  }
  </script>

</h2>
