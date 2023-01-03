# CS231 Final Project

# if you want to make a new html page for new direction
  index.html is the template

# Direct to next page
  Go to the next() function
  
   location.assign("fourth_page.html"); <--- Change this to whatever page you want to go to next
   
 # location.assign()
  - the functions to advance to the next page are at the bottom of the script tag
  - type in the url you want to go to 
   
  # Progress Bar
  
  copy paste these things
  
  - <div id="myProgress">
        <div id="myBar"></div>
  
  - //progress bar test
        var i = move_count;
        function move() {
          if (i == 0) {
            i = move_count;
            var elem = document.getElementById("myBar");
            var width = 10;
            var id = setInterval(frame, 10);
            function frame() {
              if (width >= 100) {
                clearInterval(id);
                i = move_count;
              } else {
                width++;
                elem.style.width = width + "%";
                elem.innerHTML = width  + "%";
              }
            }
          }
        }
  
  - next001.innerHTML = "<button onclick=next(); move();>Continue</button>";
  
 
