# INDOOR PLANTS WITH BENEFITS
### an interactive web page for plant lovers to learn indoor plant lighting requirements!

Made using HTML, CSS and jQuery only. 
My project is based around indoor plants - i've been a lover and collector of indoor plants for over 7 years.
Every variety of plants has its own needs and even though the labels often have how to look after them, 
some of the terminology can be confusing to people entering into plant ownership for the first time. 

My goal is to inform the user of the different type of lighting and watering requirements that some common indoor plants will have.

I had a few ideas on how I wanted to make this webpage interactive, due to time constraints and my skill level I settled on focusing on the light requirements - what does bright indirect lighting even mean? 
The idea is I would have a carousel of plant 'stickers' where the user can drag the image of the plant into a room that has different lighting zones. The user would be able to click on the plant to have a description pop up and tell them what would normally be on a plant care label, from there they would have to interpret the information and place it in the room accordingly. 

There are so many more features I would love to add in future, like whether the spot the user has placed it in is "correct" or sustainable to the plant. I would love to add a water requirements feature to it as well. 


## The Planning Phase: 

### Below you can see my inital ideas of what I could do for this webpage. 

#idea 1
Interactive website where the user will drag each 'sticker' of a plant into a room that visually shows different lighting.

The plant, when clicked on, would have the 'tag' information that you would see when purchasing a plant from a garden center and then they would (maybe through trial and error) find where it would be suitably placed.
There would also be a watering can with a meter and you can choose how much to water the plant.

    Issues : 
    - difficult of having each plant be a 'sticker', will have to use jquery mouseClick functions and cursor following?

#idea 2
Instead of having the users drag the plant into the correct spot in the 'room', have the plants already placed in the room and make them clickable to have the right information. Hoping to still incorporate the same logic for the watering can as in idea 1. 

    Issues : 
    - not sure how to have the different areas clickable without being separate objects
        maybe still have the plants as separate objects but just have them placed by absolute positioning.

#idea 3
This can be attached to any of the above - but hoping to have a background image that is wide enough that the user is capable of panning the room a little bit.
