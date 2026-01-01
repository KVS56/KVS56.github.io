<script>
    var now = new Date();

    var learning = new Date(2025, 5, 8,);
    
    var elapsedT = now - learning;

    var seconds = elapsedT / 1000;
    
    var second = seconds * 1.78

    var counter = setInterval(timer, 1000); //1000 will  run it every 1 second
    
    function timer()
{
  second=second+1.78;
  if (second <= 0)
  {
     clearInterval(counter);
     return;
  }

 document.getElementById("timer").innerHTML=second + " lives have been lost."; // watch for spelling
}
  </script>



  <p>Since the day I made this, <span id="timer"></span> Lost to mortality, to war, to famine, to pestilence and to the march of time. That is 1.78 lives lost every single second. 107 lives lost every minute, 6,390 lost every hour, 153,000 every day, and 56 million every year.</p>
