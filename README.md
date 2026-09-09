# CCOM-4302-Projecto 1
Kevin Tosado and Jeremy Quintana

For this project, we built a 3D marble race track with different obstacles, a splitting path, and a block archway at the end for the finish line.

<img width="734" height="381" alt="Screenshot 2026-09-08 195814" src="https://github.com/user-attachments/assets/9bcf6deb-37c8-40ec-932d-3fece1e5e5e5" />

We built a straight ramp at the start and added scattered square blocks to slow down the marbles. We didn't want any dead ends that would trap the marbles, so the blocks just bump them around to make the start more unpredictable.

<img width="724" height="371" alt="Screenshot 2026-09-08 205242" src="https://github.com/user-attachments/assets/a7ef8baa-210a-47ea-9af5-62eff4bf266c" />

After the marbles fall form the obstacles they wind up in a turn where they go around in a circle before continuing down the path and we added walls so the marbles don't just fall off

<img width="730" height="377" alt="Screenshot 2026-09-08 221856" src="https://github.com/user-attachments/assets/f350693b-dae0-4da9-9600-096de6224996" />

Next, the track splits into two different paths around a middle diamond section. This lets the marbles take different routes before coming back together into a single lane to finish the race.

<img width="724" height="380" alt="Screenshot 2026-09-08 222807" src="https://github.com/user-attachments/assets/6d88be4f-ba47-4f8a-88eb-375eef8c1a15" />

At first we wanted to use only 2 marbles but that was kind of boring, so we added 2 more to make it 4 and gave them each distinct colors by using the mesh renderer to chenge them. We also utilized Rigidbody so gravity makes them roll naturally.

<img width="728" height="386" alt="Screenshot 2026-09-09 122828" src="https://github.com/user-attachments/assets/0c2d467a-86ff-4924-8e13-44d70779c501" />

At the finish line, we built an arch using individual blocks. We added Rigidbody to them as well .We connected the blocks in a way that they could support each other and not fall or explode.

<img width="597" height="372" alt="image" src="https://github.com/user-attachments/assets/ccc975ee-9676-4843-ac2a-b9972fc17071" />

This final shot shows the entire track from top to bottom. We designed the course to be fairly compact so everything fits nicely in one camera view and you never lose sight of the marbles.
