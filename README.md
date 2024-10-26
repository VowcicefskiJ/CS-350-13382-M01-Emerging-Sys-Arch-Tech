This repository includes selected artifacts from my coursework that highlight my skills in systems architecture, embedded programming, and hardware interface control. The projects demonstrate my ability to write software for hardware interaction, analyze system architecture impacts, and apply emerging technology solutions to meet business requirements.

In this submission, you’ll find:

    Project Artifacts - Two project files showcasing my work in UART and GPIO driver integration, as well as state management for hardware control.
    Reflection - Answers to key reflection questions that document my learning process, highlight specific skills, and provide context for future reference.


Reflection Questions and Answers

1. Summarize the project and what problem it was solving.

The goal of this project was to control an LED on the TI CC3220S LaunchPad using UART and GPIO drivers. By entering simple commands ('O' for on and 'F' for off) through UART, the LED could be turned on or off. This setup allows interactive control over the LED, highlighting the use of basic hardware interfaces and UART communication.

2. What did you do particularly well?

I think I did well in making sure the input commands were handled accurately so the LED responded as expected every time. I also added feedback messages that let the user know if the LED was on or off, which made the program more user-friendly and easier to follow.

3. Where could you improve?

One area I could improve is optimizing the infinite loop in the code to use fewer resources, like processing power. I could also add more input validation to make sure the program ignores any commands that might not make sense or could cause issues.

4. What tools and/or resources are you adding to your support network?

For this project, I leaned on the Texas Instruments documentation for the TI CC3220S, UART, and GPIO drivers. I’m adding more resources to my toolkit, like TI’s online developer communities and forums for embedded systems, to help with similar projects in the future.

5. What skills from this project will be particularly transferable to other projects and/or coursework?

This project helped me understand how to use UART and GPIO drivers, which are really useful for hardware control in embedded systems. Also, creating the state machine diagram for the LED control gave me practice in organizing program states, a skill I can use for other projects that involve managing hardware behavior or controlling devices.

6. How did you make this project maintainable, readable, and adaptable?

To make the project more maintainable and readable, I added comments throughout the code, especially in the parts that handle UART input and control the LED. I set up the code in a way that makes it easy to change individual parts if needed. The state machine diagram also helps show how the code flows, making it easier to follow or modify later on.
