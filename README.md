# HCI hand gesture games - super mario, chrome dino, battle city

Play classics such as super mario bros, the chrome no-internet dino game and battle city only using hand gestures! No need keyboard or mouse inputs. A fun and futuristic way to revisit the old games.

Made in **Python 3.6**. Not a standalone exe. Requires Python 3.6 and necessary packages, Python IDE like PyCharm.

Chrome dino currently only works with [chrome 86](https://www.neowin.net/news/google-chrome-860424075-offline-installer/) and included chrome driver software.

Play the following games:
* Super Mario Bros by running the script mario.py
* Battle City by running the script battle_city.py
* Dinosaur Game by running the script dinosaur.py

## Super Mario Bros:
The screen is split into 3 equal parts horizontally. Actions detected:
* Open hand within the left part -> Left jump
* Closed hand within the left part -> Left run
* Open hand within the middle part -> Jump
* Closed hand within the middle part -> Do nothing
* Open hand within the right part -> Right jump
* Closed hand within the right part -> Right run

## Battle City:
The screen is split into 5 parts, including 4 triangles and a circle. Actions detected:
* Open hand -> Fire
* Closed hand within the circle -> Do nothing
* Closed hand within the left triangle -> Go left
* Closed hand within the right triangle -> Go right
* Closed hand within the up triangle -> Go up
* Closed hand within the left triangle -> Go down

## Chrome dino game:
The screen is split into 2 equal parts vertically. Actions detected:
* Closed hand -> Run
* Open hand within the upper part -> Jump
* Open hand within the lower part -> Duck

## Python packages:
* cv2
* tensorflow
* numpy
* gym
* gym_super_mario_bros
* gym_chrome_dino
* pygame
* opencv

[Demo](https://drive.google.com/file/d/1LMtnWvqIe02X3QryX5maWkhySHyxMyiH/view?usp=sharing)

Contact [boss Sagar](mailto:sagarsethu25@gmail.com?subject=Regarding github repo- hci handgesture game) for help and more details.
