<div id="countdown"></div>

<script>
const date = new Date("January 30, 2020 06:00:00")
const countdown = new Date(Date.getTime() - date.getTime())
document.getElementById("countdown").innerHTML = countdown.getHours() + ":" + "countdown.getMinutes() + ":" + countdown.getSeconds()
</script>
