# CS 361 Golf Scatter Plot

A. Clear instructions for how to REQUEST data from the microservice you implemented. Include an example call.

User will interact with the Golf Scatter Plot Microservice by sending a request for data in [(degrees, yards)] format to show their golf shot scores in a visual format. This will be achieved by sending input as a JSON file with an array of data points to be plotted. (see example)

[["[deg]", "[yds]"], ["8.438499450683594", "4.634101976308557"], ["-0.3516591489315033", "24.63838534384833"], ...]

B. Clear instructions for how to RECEIVE data from the microservice you implemented.

Once the data from the JSON file is processed, it will be saved as a variable called data, and the degree values will be converted to radians.
These data points will now be plotted on a scatter plot, which will be shown to the user, and the figure will be saved to the user's computer by the microservice program.

C. UML sequence diagram showing how requesting and receiving data work. Make it detailed enough that your partner (and your grader) will understand.

<img width="691" alt="CS 361 UML Diagram" src="https://user-images.githubusercontent.com/96963166/218279113-6007f34c-5575-465a-97c0-2bed44e33512.png">
