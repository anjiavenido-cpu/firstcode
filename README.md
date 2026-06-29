<html>
  <head>
    <title>appreciation for my baby</title>
    <style>
      img {
        width: 30px;
        float: left;
        border-radius: 15px;
        border-color: black;
        margin-right: 15px;
        margin-bottom: 20px;
      }
      p.username {
        font-weight: bolder;
        margin-top: 10px;
      }
      p.message {
        font-style: italic;
        background-color: rgb(91, 198, 237);
        margin: 10px;
        padding: 10px;
        border-radius: 30px;
        height: 30px;
      }
    </style>
  </head>
  <body>
    <img src="612168283_1603048007501034_569544262036436990_n.jpg" />
    <p class="username">@elinelovesdav</p>
    <p class="message">
      Hi dave, or let's say "baby". Thank you for everything that you have done
      for me ever since we've met. I know how fast everything happened, despite
      the arguments and problems we had you're still staying and enjoying every
      moment of our life but this time with me. You don't know how grateful i am
      to have you. Thank you! Will you be my forever baby?
    </p>
    <div class="buttons">
      <button id="yesButton">Yes</button>
      <button id="noButton">No</button>
    </div>
    <div id="answer"></div>
    <script>
      const answerEl = document.getElementById("answer");
      document.getElementById("yesButton").addEventListener("click", () => {
        answerEl.textContent = "You clicked Yes. Thank you! May Bj ka maya";
      });
      document.getElementById("noButton").addEventListener("click", () => {
        answerEl.textContent = "You clicked No. At baket?";
      });
    </script>
  </body>
</html>
