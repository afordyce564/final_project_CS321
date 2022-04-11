# final_project

# if you want to make a new html page for new direction
  index.html is the template
  This will be the only item in the texts array 
  <text onmousedown=turnLeft1(this)>Pick a direction *Left*</text><text onmousedown=turnRight1(this)>*Right*</text>
  pay attention to where you put the text
  
# Change index number to reflect which item in the list you want to display
     //start game off with first maze picks
     question001.innerHTML = texts[0];
  
     
# Direct to next page
  Go to the next() function
  
   location.assign("fourth_page.html"); <--- Change this to whatever page you want to go to next
 
