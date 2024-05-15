# [SDF04] CSS Magic Buttons

In this challenge, I sought out to generate buttons that I felt would challenge me, and help develop some of my skills.

## Project Overview

### Button One

After googling for inspiration to get some inspiration, very quickly, I had a grand idea for the first button. 
This was to have meteors fly across it when hovered upon, as well as triggering the background to change to a starry night photo. 
I achieved this goal in the end, but it did take a lot longer than expected, and stackoverflow was my best friend. 

This involved created 5 divs, inside a parent div, asiging respective classes as the 5 children div were to be the "meteors", and then I needed to do the rest with CSS.
I had been burnt in the last project where I spent ages trying to apply flexbox to divs only for them to not budge an inch before I realised I had been trying to apply
display:flex to the children I was trying to affect, and therefore nothing was going to happen. I did not make this mistake this time around.

All in all, the first button was about 250+ lines of CSS, which shocked me. Having said that, the satisfaction I felt when everything finally came together as I wanted it to
was extraordinary.

### Button Two

Tired after the first button, I decided I wanted a more manageable challenge for the second.
As such, I decided I wanted to experiment with box shadow animations for the second.
I decided I wanted to have neon blue/green colours alternating smoothly while a box shadow surrounds the button and gives it a smooth almost misty look.
This took a bit of figuring out how to properly manipulate the box shadows, I also learnt the key to the smoothness is making sure whatever happens
at 0% of the keyframe must happen at 100%. Once I cracked that, I was really happy with the results.

### Button Three

For the third button, I decided to go with something more sleek and minimalist compared to my first two design choices. 
For this button I settled on animating it such that upon hovering it will begin slowly shifting up and down upon its Y axis to indicated its been hovered upon. 
I also added a smooth green border I liked, and I adjusted the letter spacing and the font. The border pulses in and out in time with the shifting on the Y axis, which I liked.
While this was the easiest button to do out of the lot, I felt there were still lessons I absorbed from it.

## Final Thoughts

This was the hardest challenge yet, but of course I feel this is defined by where you set your own goalposts. I decided to really push myself with my first button. For quite a while, I felt I didn't have what it took to achieve the result I wanted, but I am happy to say I perservered and I achieved the results I wanted.

What I enjoyed about this challenge was how I got indepth hands on experience with so many different aspects of CSS. It was a challenge relating to animating buttons and yet I feel even more comfortable manipulating divs, using flexbox, using the hover and focus pseudo-classes, using keyframes of course, and I even used a somewhat new CSS selector, the :has() selector. This selector allows you to reference parent elements and without it, I would not have overcome the biggest hurdle of my version of this project. 

I'm coming out of this feeling like I have a much more solid grasp of CSS and I'm looking forward to the oncoming projects and challenges with a new strength and confidence.
