
# "It's about the race, not the finish line"

We’re RoboRacers, a robotics team from Dublin, CA. Our team, RoboRacers 16481, is taking part in the annual FIRST Tech Challenge (FTC). We are talented kids from the ages 13-17 years. Our team was founded in 2019.

Our mission is to provide kids with a free, fun, and accessible way to get into learning about robotics and technology.

Our members learn valuable skills in mechanical and software engineering, artificial intelligence, problem solving, and leadership through hands-on experience with robotics. We work to inspire youth in our community to join a FIRST robotics program.

## Current Open Source Projects:

### GaelDrive: Monte Carlo Localization for FTC

GaelDrive is a localization library written in Java & C++ that uses Monte Carlo Localization (MCL). Localization is the process of finding where something is, and this library allows robots to find their location on the field. We accomplish this by recursively estimating our state (The posistion of the robot) using a particle filter. A particle filter uses particles to estimate the distribution of the probability of the robot.

This allows the robot to use any type and number of sensors (distance sensors, deadwheel encoders, inertial measurement units) to find it's absolute position of the field, something traditional localization methods cannot do. 

Here is a link to the [Project Page on GitHub](https://github.com/RoboRacers/GaelDrive) (GaelDrive for FTC)
