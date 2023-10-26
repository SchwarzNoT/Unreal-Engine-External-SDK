# Unreal-Engine-External-SDK
Designed to help others understand reversing/modding of the Unreal Engine, this project serves as a tool to guide UE4 modding/hacking.

Usage is fairly simple, the UnrealClasses files provide an accurate demonstration for how Unreal classes should be initialized. For example, calling the AActor Constructor with an address passed in will fully initialize a class consisting of all requested variables (FName, Base Address, World to Screen Information, etc.). Feel free to expand on these files and add your own game specific classes.

While this specific implementation is based on Fortnite Battle Royale, the classes are easily transferable to any other Unreal Engine 4+ game. The SDK is extremely well optimized for good performance (Even on my laptop which often struggles has no issue).

Additionally, there are several tools built in to aid in development, such as ImGui, used to easily draw visuals.

I hope those who use the SDK are able to learn as much about Unreal Engine as I did while writing this.
