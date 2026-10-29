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
<img width="683" height="651" alt="image" src="https://github.com/user-attachments/assets/09da425c-7796-470f-b80c-628c8816e0fd" />
<img width="400" height="225" alt="2026-10-28 23-49-52" src="https://github.com/user-attachments/assets/395c197a-3bb7-4bc6-a67e-0463cc6a8964" />

Next we have to make it so the character can sprint by pressing shift.
For sprinting I added it to the PlayerMovement Script we made in class and put in a part for OnSprint that makes the player move twice as fast 
<img width="577" height="689" alt="image" src="https://github.com/user-attachments/assets/72e855b8-7d62-4221-b339-a75e418b4285" />
Only problem with this new part of the script was that when we hit the shift key to sprint, the character would stay sprinting and not stop. So we had to solve that.
