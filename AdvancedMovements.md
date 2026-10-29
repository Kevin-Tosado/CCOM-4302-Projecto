# CCOM-4302-Projecto 3
Jeremy Quintana And Kevin Tosado

For this project we need to give our already created characters, actions.
During class, we already gave it Horizontal movement, Vertical movement and Shoot, as seen in the images. 

<img width="674" height="628" alt="image" src="https://github.com/user-attachments/assets/cb4acddf-3c7e-40d8-bfa7-54986c899e2e" />

and heres the one for shooting 

<img width="606" height="333" alt="image" src="https://github.com/user-attachments/assets/c8d1087c-3a8e-42ed-aa06-e92ef026af95" />

We utilize the property known as PlayerInput or InputSystem to do all of this .

Now we need to add the Jump mechanic.
At first we tried doing it with a simple code but the character would straight up just fall through the floor. So then we added the same Rigidbody rb mechanic we've used previously to the code that that made it work. We gave the player character 5 jump height and made it be able to double jump.
<img width="599" height="565" alt="image" src="https://github.com/user-attachments/assets/04f00007-196b-4209-9e10-7fc4bf584a44" />

<img width="400" height="225" alt="2026-10-28 23-49-52" src="https://github.com/user-attachments/assets/395c197a-3bb7-4bc6-a67e-0463cc6a8964" />

Next we have to make it so the character can sprint by pressing shift.
For sprinting I added it to the PlayerMovement Script we made in class and put in a part for OnSprint that makes the player move twice as fast 

<img width="730" height="679" alt="image" src="https://github.com/user-attachments/assets/3fe53158-1744-41e7-a754-0316915694f3" />

Only problem with this new part of the script was that when we hit the shift key to sprint, the character would stay sprinting and not stop. So we had to solve that.
We switched the public void for OnSprint to take an InputAction Callback To toggle and go between true and false when the button is pressed.

<img width="352" height="146" alt="image" src="https://github.com/user-attachments/assets/1125c64a-99c5-4e88-bac4-4864ce70d731" />

This also didn't work. So as a last case we decided to just add the old part back and change it direcctly in the InputSystem to add an interaction, it now checks if the shift key was pressed or not and changed the speed depending on if its toggled or not.

<img width="250" height="380" alt="image" src="https://github.com/user-attachments/assets/a0d99595-a99b-4155-854a-ec4b0ee270a8" />

This actually worked, as demonstrated here, where it moves faster.

<img width="400" height="225" alt="2026-10-29 00-30-24" src="https://github.com/user-attachments/assets/dbe7654b-251d-4e7b-8567-16d05524a2f2" />

Lastly we need to add the dodge. We made a new Script called PlayerDodge to do so, here's the code

<img width="544" height="635" alt="image" src="https://github.com/user-attachments/assets/a8478c89-1f01-4a6d-b3cf-c6d036881ec4" />

When we made it, it was only dodging in the direction it was facing as commented. To fix that we added this

<img width="562" height="87" alt="image" src="https://github.com/user-attachments/assets/c501a8b0-a4ec-49fa-8590-b19d910db7ff" />

Now it will dodge left or right based on the last direction pressed. And now heres the full code with the video Demonstration

<img width="554" height="640" alt="image" src="https://github.com/user-attachments/assets/49d32ef8-638a-4bf5-9ccc-9ee7b0c771e0" />

<img width="400" height="225" alt="2026-10-29 01-05-21" src="https://github.com/user-attachments/assets/97dfd375-7a03-4b9a-8448-f550a808d731" />

Now that we made our character Move, Shoot, Jump, Double Jump Sprint and Dodge. We are Done!!!!


