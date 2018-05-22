# Unreal Multiplayer Course - Section 1 - Puzzle Platforms

In follow up to our hugely successful [Complete Unreal Engine Developer](http://gdev.tv/urcgithub) course we bring you [Unreal Multiplayer Mastery](http://gdev.tv/uemgithub) - as on featured on [Epic's UE4 blog](https://www.unrealengine.com/en-US/blog/getting-started-with-unreal-multiplayer-in-cpp).

In this section we teach the basic client server model and get multiple instances connected through a collaborative puzzle game.

You're welcome to download, fork or do whatever else legal with all the files! The real value is in our huge, high-quality online tutorials that accompany this repo. You can check out the course here: [Unreal Multiplayer Mastery](http://gdev.tv/uemgithub)

### 0 Course Promo ###

+ Why you should take the course.
+ We overview the journey.
+ What are the prerequisites?

### 0b Introduction to Puzzle Platforms ###

+ Overview of the course structure.
+ What will we cover this section.
+ Let's get stuck in!

### 1 Connecting Two Players ###

+ Notes on Unreal versions.
+ Creating the base project.
+ Testing with multiple players.
+ What's under the hood.
+ Finding an Unreal .gitignore.

### 2 How to Be an Active Student ###

+ Source control and where to get code.
+ Our community site.
+ Reading the slides.
+ Our rich community.

### 3 Surveying the Multiplayer Space ###

+ Overview of multiplayer game types.
+ Outlining the journey.
+ Sharing our ambitions.

### 4 Meet the Client-Server Model ###

+ Client-Server vs Peer-to-Peer
+ Launching a game from the command-line.
+ Launching a dedicated server.
+ Join with clients.

### 5 Detecting Where Code is Running ###

+ Create a `AStaticMeshActor` subclass.
+ Adding mobility in C++.
+ Running code only on the server.

### 6 Authority and Replication ###

+ Understand Actor "Authority".
+ Enable replication of movement.
+ What happens with disagreement.

### 7 Widgets For FVector Properties ###

+ Adding 3D gizmos to a UPROPERTY.
+ Vector for A to B travel.
+ Moving our platform.

### 8 Sending The Platform Back ###

+ What we want to achieve.
+ Continuing past the target.
+ Swapping the start and target.

### 9 Set Up A Simple Puzzle ###

+ Better jump controls.
+ Layout a puzzle.

### 9b Playing Over The Internet ###

+ Local vs global internet.
+ Simulating LAN with Hamachi.
+ Connecting Unreal over Hamachi.
+ Getting connected with others.

### 10 Set Up A Platform Trigger ###

+ Create the C++ class.
+ Add a box component.
+ Tweak the Blueprint.
+ Place it in the world.

### 11 Handling Overlap Events In C++ ###

+ Implement the handler function.
+ Register the event callback.
+ Reloading the map to call constructors.
+ Repeat for `EndOverlap`.

### 12 Activating Platforms From Triggers ###

+ The desired behaviour.
+ Creating the platform interface.
+ TArray for hooking up platforms.
+ Implementing the logic.

### 13 When To Use A GameInstance ###

+ What is a `GameInstance`?
+ Set a custom `GameInstance` for you project.
+ Init vs Constructor.

### 14 Console Commands With Exec ###

+ What is the console.
+ What classes support Exec functions.
+ Creating out own.
+ How to log to the screen from C++.
+ Dealing with arguments.

### 15 Hosting Servers With ServerTravel ###

+ Creating a Lobby.
+ What is travelling?
+ Hosting a server with travel.
+ Testing with and without `?listen`.

### 16 Joining Servers With ClientTravel ###

+ `ClientTravel` vs `ServerTravel`.
+ Getting the `PlayerController`.
+ Implementing `ClientTravel`.

### 17 Sharing Your Game On Itch.io ###

+ Building your game.
+ Introduction to Itch.io.
+ A note on security.
+ Sharing our game.

### 99 Puzzle Platforms Wrap-up ###

+ Well done!
+ Get inspired to extend your project.
+ Make sure you're ready for the next section.
