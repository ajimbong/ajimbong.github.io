# Ajim's Property

Spying on me bruh?
<br>
<br>
This is your IP: <b id="ip"></b>
<br>
I know who you are 👀👊

<script>
 const ipHolder = document.getElementById('ip');
   fetch('https://api.ipify.org?format=json')
   .then(response => response.json())
   .then(data => {
    ipHolder.innerHTML = data.ip;
})
</script>
