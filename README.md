# final_project

# if you want to make a new html page for new direction
  first add a new string to the texts array
  copy and paste this "<text onmousedown=turnLeft1(this)>Pick a direction *Left*</text><text onmousedown=turnRight1(this)>*Right*</text>"
  pay attention to where you put the text
  
# Change index number to reflect which item in the list you want to display
     //start game off with first maze picks
     question001.innerHTML = texts[0]; <--- change to match item at a certain position
     
# Change function numbers
  adjust the numbers in the turnLeft and turnRight for the new string
  
    <text onmousedown=turnLeft1(this)>Pick a direction *Left*</text><text onmousedown=turnRight1(this)>*Right*</text>
    Notice how it has turnLeft1 and turnRight1 because they were the first functions written and they match the item at texts[0]
  
     
# Direct to next page
  function next() {location.assign("fourth_page.html");}<--- Change this to whatever page you want to go to next
 
