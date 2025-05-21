# Bug List

> Make a list of the things that don't work as expected. Keep a list of things that you have fixed and try to document how you solved them.


1. Problem: *Wanted infobox hidden before you press "start quiz" at start of the game* 
- *Solution*
  - *I added the "ibox" id tag in parent infobox div*
  - *Created css styling under ".info_box" that hides infobox with "opacity 0;" and "pointer-events: none;"*
  - *Created  infoBox and startbtn variables in js*
  - *Created  infoBox and startbtn functions in js*



2. Problem: *Wanted startbtn to be centered on screen* 
- *Solution*
  - *Added "start_btn" class to the button container div*
  - *Created css styling with "position: absolute", "top: 50%", "left: 50%" and "transform: translate(-50%, -50%)"*
  - *This combination pushes button to exact center of screen*



3. Problem: *Wanted continuebtn and exitbtn to be inside infobox and centered at the footer* 
- *Solution*
  - *Placed both buttons inside a div with class "buttons" within infobox*
  - *Added css styling with "display: flex", "align-items: center", and "justify-content: center"*
  - *Used "gap: 15px" to space buttons evenly*
  - *Added margin-top: auto to push buttons to bottom*



4. Problem: *When i press continue, i wanted to see first page with first question to show up* 
- *Solution*
  - *Created continueBtn variable in js to target the button*
  - *Added onclick function that removes "activeInfo" class from infobox*
  - *Added "activeQuiz" class to quizBox to make it visible*
  - *Called showQuestion(0) to display first question*
  


5. Problem: *When i press exit, i wanted to hide infobox again and only show start quiz btn* 
- *Solution*
  - *Created exitBtn variable in js to target the button*
  - *Added onclick function that simply removes "activeInfo" class*
  - *This makes infobox disappear while start button remains visible*
  - *No other changes needed as start button stays in place*



  
6. Problem: *Timer not working properlr* 
- *Solution*
  - *Created  timerDisplay variable in js to target the timer*
  - *styled with css to put it under time text*
  - *Tmade the timerid variable to "id" the timer and clearinterval(timerid) to stop timer when button is clicked*


7. Problem: *Wordscramble input box too big* 
- *Solution*
  - *Fixed the sizing with css .wword_scramble_container *

 



 


