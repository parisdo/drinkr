# cogs121-sp16-ass1

## Authors: Paris Do, Paul Kim, Jeremy Leu, Joshua Navi, Kyle Zhu

### Heuristic Implementations:

###### Visibility of system status:

User sees `Click here to login with twitter` only when not logged in. On the other hand user only sees `Logout` button when logged in. Furthermore, our index.html shows our app name, as well as only the 'logout' button to show that the user successfully logged in.

###### Match between system and the real world:
We phrased all of our buttons with user-friendly language, such as 'Add a New Drink',  'Please tell us about your drink', and very specific identifiers for the fields that the user inputs. Also, we made the drink types very simple, with relatable language.

###### User control and freedom:

Website has bright red `Cancel` button after clicking `Add a drink` or `Comment on this Drink` which allows user to undo decision to post. Since our application is a fairly straightforward idea (for viewing drinks), the user has capabilities to add new drinks, as well as to comment on them.

###### Consistency and standards:
We also specified each submit button to state what is being submitted, so that everything is more specific in general. Also, we placed buttons all on the appropriate sides, as well as keeping our overall website layout consistently aligned. We went for an Apple-style look.

###### Error prevention:

Form to post a drink has a dropdown menu for drink type which prevents users from typing in an invalid drink type which could cause errors. Also, we made the submit button on the form bigger than the cancel button, and in a different color as well to symbolize the purpose of each button to prevent potential slips in usage.


###### Recognition rather than recall:

Buttons are unambiguous such as `Add a New Drink` or `View/Add Comments` with a comment glyphicon so users know what actions they will be taking. Also, all things that are clickable are made obvious through the use of icons or intuitive arrows, as well as color coding for certain things. We changed it so that the arrows would change color if pressed, so that the user knows whether or not they voted.

###### Flexibility and efficiency of use:
Our application is simple, and has a very low learning curve. For the more expert users, they will have their login verified more quickly, without the need to press the re-verification button.

###### Aesthetic and minimalist design:
Our website is modeled off of how Apple designs their products -- sleek and simple. We provided enough functionality for users to comment and vote and add drinks, without cluttering the page. We tried to utilize white space so that the text stands out more (since there is less of it).

###### Help users recognize, diagnose, and recover from errors:

If a user tries to add a drink without entering a name for the drink, an error message telling the user that the name field is required appears. Also, we made it so that a user can not continually click the upvote or downvote button. As such, they have a maximum of +1 or -1 per post.

###### Help and documentation:
Our application is simple enough where it doesn't really need a tutorial, or help documentation. That being said, we included the help button on our /chat page, with a little pop up with instructions for the user. It goes over each of the functionalities briefly so the user understands how to use drinkr.





### Documentation of each group member's contributions:

###### Paris Do:
Implemented upvote and downvote buttons -- persistent vote count after page is refreshed, vote icons change color when clicked, users can only upvote/downvote once (vote.js).  

###### Paul Kim:
Created wireframes and design concepts for desktop and mobile. Changed some titles to use icons instead for easier identification and association. Changed the location of few buttons. Created a category button so that drinks can be displayed by category.



###### Jeremy Leu:
Implemented the frontend forms and UI for adding a drink and commenting, helped with authentication, designed the drink images used on both the login screen and /chat.html, and did some UI design to better match heuristics.

###### Joshua Navi:
Designed and implemented the MongoDB schemas (models.js) as well as added the functions for handling post requests for both comments and drinks and get requests for drinks (chat.js).

###### Kyle Zhu:
Applied heuristics by adjusting the type of wording we used, as well as emphasizing certain buttons on the page so that they look clickable. Also, wrote the help & documentation, and modified the 'Add a New Drink' form so that it speaks in user friendly language, as well as having useful descriptions for empty fields. Drew a prototype with a baseline skeleton design as well as emphasizing the submit drink and cancel button colors, along with their phrasing. Helped implement OAuth for login with Twitter, as well as dropdown menu on Drink Types.
