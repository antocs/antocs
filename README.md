<div id="countdown"></div>

<script>
const event = new Date("January 30, 2020 06:00:00");
let countdown = new Date(Date.now() - event.now());
setInterval(() => {
document.getElementById("countdown").innerHTML = date.getHours() + ":" + "countdown.getMinutes() + ":" + countdown.getSeconds()})
</script>
