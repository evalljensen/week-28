!SLIDE countdown bullets

## Consuming the Github API

* Understand the Gist API
* Consume the API in Ruby
* Design and develop a client

<div id="countdown_dashboard2" style="margin-left: 372px; width: 350px; height:150px;">
  
<div class="dash minutes_dash">
<span class="dash_title">minutes</span>
<div class="digit">0</div>
<div class="digit">0</div>
</div>

<div class="dash seconds_dash">
<span class="dash_title">seconds</span>
<div class="digit">0</div>
<div class="digit">0</div>
</div>

</div>

<div style="margin: 0px auto; width: 92px;">
<button class="button" onclick="secondTimer.start();">
  START!
</button>
</div>

<script>
$(document).ready(function () {
window.secondTimer = new ExerciseTimer("#countdown_dashboard2");
});
</script>