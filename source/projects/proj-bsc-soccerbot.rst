Holonomic Drive Robot
=======================
During my undergraduate studies I was a member robotics team preparing for National Robocup Competition.

The competition summery is that, a team of five robots are playing soccer with an opponent team with a golf ball.

robots use four omni-directional wheels where two wheel axes collide in the wheelbase. with a simple kinematic relation from joint angles to robot body one can convert the desired body velocity to join velocities (with IK). The a PID controller was used to correct for tracking errors.

Our vision system (camera located on top of the field) would track each robots color tag to know their number and precise location.

