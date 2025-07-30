GITHUB LINK:
https://github.com/ST10469550/ICE-TASK-1-Blank-App-SLM-
https://github.com/ST10469550/ICE-TASK-1-Blank-App-SLM-/edit/main/README.md#L1C0

APP GOAL
-The goal was to create a simple React Native component that greets the user by name, using input provided through a TextInput field. The initial challenge was ensuring the dynamic input updated correctly and rendered the greeting in real time.

RESOLUTION APPROACH
-To resolve promblem: app was not displaying Hello but only the user name

CODE NOT DISPLAY IMAGE:
<img width="566" height="256" alt="image" src="https://github.com/user-attachments/assets/b2202f9a-e170-43d3-9880-9cc91daea918" />


TO RESOLVE THIS
-I used the useState hook to store and manage the user’s input.
-Bound the TextInput to userInput via value and onChangeText={setUserInput}, ensuring seamless state updates.
-Used a conditional Text element to display the message Hello, [username] only when input exists.
-Added a placeholder function handlePress() with a console.log() for potential future interaction expansion, such as triggering greetings on a button press or submission.

COULD NOT RESOLVE IT, THIS TIME THE CODE DID NOT RUN
HERE IS THE UPDATED CODE :<img width="913" height="691" alt="image" src="https://github.com/user-attachments/assets/ca94a01b-550d-43d4-8c25-0303549a4684" />
