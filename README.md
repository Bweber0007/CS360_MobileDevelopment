# CS360_MobileDevelopment
Created a simple inventory application that utilizes an SQlite database for user data


Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?

This app was designed to implement a simple inventory tracking system that allows users to log in to access their previous account data. Users would be able to register through the application and sign up for SMS notifications when an item had low inventory. The application was required to display inventory items on a screen that allowed their counts to be increased or decreased, add new items, or delete old ones.


What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?

This application utilized three seperate screens. The first for logging in or signing up. The second was an SMS permissions page that allowed users to select whether or not they wanted to allow the application to access phone data and send SMS notifications. The third was the main application page that allowed users to interact with each inventory item. The UI design was intended to create a simple interface with a basic color scheme that would allow users to intuitively interact with the different icons on each page. The buttons and text fields that were included were designed to be large enough and spaced appropriately in order to provide an easy-to-use application that didn't crowd the screen.


How did you approach the process of coding your app? What techniques or strategies did you use? How could those techniques or strategies be applied in the future?

My approach for developing the app relied on Object-oriented programming principles that provided a modular and maintainable end product. This allowed me to easily understand what each part of the program was intended to accomplish and how it should interact with the other pieces. While designing and developing, I focused on implementing the view section of the MVC design pattern which allowed me to lay a good foundation for the view and controller. Since a mobile application has a decent amount of pieces working in tandem, having a solid foundation and design plan allowed me to put more effort into the functionality rather than worrying about how it will all fit together.


How did you test to ensure your code was functional? Why is this process important, and what did it reveal?

Android Studio provides a lot of tools for testing and debugging code. Throughout the development I utilized the built in logcat to follow an errors that I was receiving from the program and the emulator provided me an on-demand tool for deploying and testing the functionality of the actual application. This process is important because it allowed me to work out kinks as I went along instead of trying to build the entire application and then weed out the issues from a few hundred lines of code amongst mulitple classes.


Consider the full app design and development process from initial planning to finalization. Where did you have to innovate to overcome a challenge?

I think that the biggest issues that I had to overcome was transitioning from design to development and implementing the concepts that I had previously thought of. I felt like I had a good idea of how I wanted the pieces of the application to interact. But, Android Studio had such a steep learning curve for me that I found myself deep in the docs multiple times trying to figure out different aspects of functions and methods. 


In what specific component of your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?

A particular area of the program that I felt really good about was implementing the main inventory screen and how the individual card layout integrated into a greater Recyclerview layout. I thought that my design for the cards and how they interacted with the database items was really clean and that screen feels really intuitive to use. I was less confident about implementing the SMS notifications and wading through the different types of permissions that were needed and how they interacted with the program.
