# HumidityStatistics_Luxoft
Technical task for hiring process

This task consists of creating an application to track the humidity sensors which are divided in to groups.
Each group leader provides a statistical data comprising of the sensor and the value of humidity

The application uses Akka Actor system to receive the sensor data and it continously changes its state according to the messages. This helps in memory efficiency and faster performance.

In this project I have used a sample data created randomly to feed the inputs to the application. The inputs can be fetched from a CSV file as well where we have to change trhe data structure to the case class defined in the application so that the actor can handle it.

