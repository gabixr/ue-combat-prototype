# ue-combat-prototype
A third-person top-down Unreal Engine game demonstrating modular gameplay mechanics and responsive combat systems. 

🎮 Gameplay 

A combat-focused top-down game showcasing modular gameplay systems.

Player and enemy combat mechanics include light & heavy attacks, dodge, perfect dodge, block, parry, and abilities.

Charge-based abilities: abilities can be charged up to three levels, triggering a different effect depending on the charge stage.

Dynamic UI system: includes a health bar, ability charge bar, and action bar, all updating in real time based on gameplay events.

All mechanics and UI are implemented through modular, reusable systems in Blueprints.


🛠️ Tools & Tech


Unreal Engine 5

Blueprints (main) for rapid prototyping and modular design

C++ GAS integration layer — a Blueprint Function Library and Attribute Component built to introduce the Gameplay Ability System into an existing Blueprint project without rewriting existing logic. [See technical breakdown          →](Source/Prototype_04/README.md)

UI widgets, state machines, and event-driven systems


🚀 Future Plans


Add more enemy types and smarter AI

Polish combat animations, visual effects, and feedback

Expand abilities and cooldown systems


🤝 Collaboration


Worked with an asset creator for art and assets. All gameplay systems, mechanics, and UI were implemented by me.


🧩 Technical Notes

The project is primarily built in Blueprints for fast iteration and modular gameplay design. A C++ GAS layer has been integrated to manage attributes, gameplay effects, and tag-driven logic — designed to slot into the existing Blueprint architecture without disrupting it. See the [GAS   implementation breakdown](Source/Prototype_04/README.md) for details. Future updates may expand C++ use for performance-critical systems and multiplayer functionality.

## 🎮 Gameplay Video


[![Gameplay Demo](https://img.youtube.com/vi/8Ehj1fyuOy8/0.jpg)](https://youtu.be/8Ehj1fyuOy8)
