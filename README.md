# Gameception
Playing around with Open GL. This project was a really great way for me to learn some concepts in programming. What better way to learn than to apply it to something fun like video games. This project includes some arcade classics like pacman, galaga, asteroids, frogger, tron and centipede

![GameRoom](docs/splash_2.png
     "GameRoom")

# Prerequisites
This project assumes you have OpenGL cmake and make already installed. The below instructions were written for the Mac environment, but this project will also run in windows.

# Build
Open a terminal and clone the project to your preferred directory:
```bash
$ cd Desktop
$ git clone https://github.com/cdomkam/Gameception.git
```

Now we'll be using cmake to create an out of source build:
```bash
$ mkdir build && cd build
```

Run cmake:
```bash
$ cmake ..
```

Now that cmake has created the necessary make files
navigate to the main directory and run make:

```bash
$ cd main && make
```
# Run
Start playing by either clicking the application that was generated in the main folder or running from terminal:

```bash
$ ./Gameception/Contents/MacOS/Gameception
```

Have fun thanks for checking this out!
![Games](docs/splash_1.png
     "Games")

