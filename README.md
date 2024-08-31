# LoginUI
Login page using HTML,CSS,JS
index.html

-created a form that contains input feild ,password ,remember me checkbox and a submit button -on click the submit button exihibits login functionality --
----msg class for showing error msg for incorrect mail/password
------spinner class for loader
-----redirection class for showing login success/fail upon api call

script tag --contains the eye functionality for visibility of password on click and for hiding on click ----login function has conditions for checking email , password ----- spinner , related text msg showing errors and success of login which appear on condition. email condition -----/^[a-zA-Z0-9._%+-]+@[a-zA-Z0-9.-]+.[a-zA-Z]{2,}$/ name should start with either a upper or lower case or digit and @ mail and after '.' the characters should be 2 or more (example:abc@gmail.com) password length should be greater than or equal to 6. 
---- if both login and password is correct then api call is made using axios url use is given open api link.
      ---if api call is successful user data is posted in api and login successful msg appears and then page is redirected to home.html used setTimeout of 4sec.
      ---if api call fails login failed msg is displayed.

#st.css ---styling is applied for the form to appear in middle of body with backgroud image,and media query is applied to it for veiwing compatibility in various devices. ----global colors are defined for easier access and color coding format. ---hover effect is used and on focus different coloring is used and also when incorrect that particular feild will appear in crimson , red indicating error. -----icons are given styling ------loader spinner is given styling.

home.html
-----has text as Home Page in html paragraph tag.
script tag ---setTimeout function would redirect it to login page after 2 sec. 
----css styling-- background color and flex for text to appear in center is applied to body.
