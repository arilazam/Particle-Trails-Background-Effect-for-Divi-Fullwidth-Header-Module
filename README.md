# Particle-Trails-Background-Effect-for-Divi-Fullwidth-Header-Module
If you use the Fullwidth Header module with fullscreen feature enabled and would like to apply a nice animated effect to its background then this tutorial might be what you are looking for. I am suggesting a particle trails background effect for Divi Fullwidth Header Module and will show you how to implement it quickly and easily. Click the demo button below to see the end result.

To implement this effect we’ll have to assign an id to the Fullwidth Header and apply neccessary settings, then insert the canvas with the animated effect using Javascript. We will also need a small CSS snippet to adjust the canvas position appropriately. Let’s do all this step by step.

Step 1:
After you enable the Page Builder for your post go to Divi Post Settings and set the page layout to “Full Width” and post title to “Hide”, then add the Fullwidth Header module in a fullwidth section with padding set to 0.

Step 2:
Apply following Fullwidth Header Module settings.

Fullwidth Header Module settings -> General Settings
Make Fullscreen to Yes *this is important
Background Color *background should be dark because the particle trails are light

Step 3:
Add the *particle_bg_effect* id to Fullwidth Header Module Settings -> Custom CSS -> CSS ID field. If you already have an id assigned to the Fullwidth Header module then you shouldn’t add another one since an element is supposed to have only one id, in this case you will have to find the particle_bg_effect id in the Javascript and CSS code snippets below and replace every instance of it with your id.

Step 4:
This is the JS code snippet for the particle trails background effect. You can set the number of particles, particle speed, particle color and size of circle (see highlighted rows in the code below).

*Particle Trails Background Effect for Divi Fullwidth Header Module.js*

Copy the JS code snippet above and paste it into the Divi -> Theme Options -> Integration -> Add code to the < body > field.

Step 5:
The canvas positioning needs to be adjusted so that it doesn’t push the Fullwidth Header contents down and doesn’t create horizontal scrollbar, for this we’ll use the following CSS code:

*Particle Trails Background Effect for Divi Fullwidth Header Module.css*

Copy the CSS code snippet above and add it into the Divi -> Theme Options -> General -> Custom CSS field.

That’s all, save everything and enjoy the effect.
