# ajimbong.github.io

<h2>This is your IP</h2>
<p id="ip"></p>

<script>
 let UserIp
 const ipHolder = document.getElementById('ip');
   fetch('https://api.ipify.org?format=json')
   .then(response => response.json())
   .then(data => {
    console.log(data)
    ipHolder.innerHTML = data.ip;
    //console.log(data.ip)
})
</script>
