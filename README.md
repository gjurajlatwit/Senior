# Senior

Developed with Unreal Engine 5

Plugins needed to be installed in UE5:
VaRest - connection to REST servers for ChatGPT api
Runtime Speech Recognizer

The two main architectural patterns used in the project are:
Model-View-Controller (MVC) - Separates application into the three different aspects, where the model broadly deals with data, the view with UI and the controller with input handling.
Entity-Component-System (ECS) - Representation of entities as small and independent components with specific functionality.


The UI for Encryption Adventures consists of a Top Down 
view.
Player Controller uses popular keybindings to allow the user to move and interact(WASD and E pattern).
Runtime Speech Recognizer uses a language model to recognize spoken words and convert them into input.
Player blueprint acts as the model in the MVC pattern of the architecture, handling action logic and useful data.
Maps use 48 bit sprite units for textures.

All Texture work attributed to LimeZu - https://limezu.itch.io/
