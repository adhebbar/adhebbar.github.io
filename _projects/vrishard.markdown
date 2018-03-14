---
layout: post
title:  "VR is Hard (Ongoing)"
tags: Occulus-rift Unity Arduino Virtual-reality
sidebar: true
text: true
description: An temple-run like game  on the occulus rift, with integrated harware 
image: /assets/images/projects/vrishard.jpg
---
This project is currently funded by [roboClub](https://roboticsclub.org/) and part of the [ CMU game creation society](http://www.gamecreation.org/). I function as co-team lead for this interdiplinary projec involving a team of artists, programmers and engineers.

We want to create a game in virtual reality with a hardware aspect. In the game, the user will
take on the role of a princess riding on a hover board in a steampunk styled world. The hover
board will consist of physical counterpart, a real life metal board on springs that a user can stand
on. The hardware and software of this project are described below:

- The physical counterpart to the hover board:
This essentially consists of a movable board balanced on springs, that primarily serves to detect
the user’s tilt (i.e. they can stand and move around on the board as they would on a skateboard,
and this movement would be detected and manifested in the hover board in the game.)
Additionally, the physical board will also move by actions generated in the game (for instance, if
the user hits an obstacle in the game, the board will wobble).
This is a mostly mechanical/electrical job, and will consist of using spring and metal plates to
create a movable board. We plan to have an electrical and mechanical team work together to
make a physical board that ensure the user’s safety while creating as well as detecting motion.
We will use an IMU to detect the tilt, and strong motors to create the motion. We plan to use an
Arduino to coordinate data between the board, and the game software (unity).


- The Game (Software):
Storyline: The user plays as a runaway princess in a steampunk universe. She rides a hover board
and gathers parts of hover boards along the way in order to build hover boards with better specs.
She also avoids guards sent by the government along the way. Her past is explored whenever she
reaches a checkpoint (a house of someone she trusts where she will rest) which will lead to a cut
scene that reveals more about her past and her reason for running away.

The [project proposal](https://mail-attachment.googleusercontent.com/attachment/u/0/?ui=2&ik=ed77d60b8a&view=att&th=16130e050414619a&attid=0.1&disp=inline&realattid=f_jcvgzzsx0&safe=1&zw&saddbat=ANGjdJ8yBiI1pbdQRID5dROrBHYM3qs424qSr2vYn0U5B1O9gYjd5moADINnBZGXF014e-NE2xyE1vqqdcUw_I3PyUcZnwKkCcEsT3DrsWclLzd_TGJAGb3z5faLupltYsqnEGtz6ZeAwkqwmDl6gXh9BNfIitNGgBbjf4TRXy-5V6ZtpTLHoj4KHnQnySoKd47wJPmXWOXqn59GGPTdV5ArHvv00rV7DxoLJ5FTn7AOoSHM5hGsQV-lM97ZOd09TUbR7LCSPbdmaASD-w3_C_2nUuAN8u-5K5wZcVev2wGVa-dHikBXbOkJkCFjU40Gp1FpakuQjG-CPUe2xEUdpxa64feJup-0WpfhUL_tLcKfuL5ppozfmbR47c1aA379GQt2wicjtbZ5JQPRbRJSREwmKeRQ1LVqm3NAAjaSBc9PJBtJLo5Lh_P4IXz1SePnr4MqWED45d74TTmovhBA56xQOx-K1uIdLPz38s9YZI-Y6IECWRoK8MuxGB1cRg2AvJJ_9fXN-q4kmayr36ltMUjKBgkyHtEDUJLJ3jCTs5gkruFteMvQWP5kpqcXVMXMNj3RxcQaPUXcM6yP0Q22CXENV8ses32m7XwJyCjWWA) explains the project in greater detail.

