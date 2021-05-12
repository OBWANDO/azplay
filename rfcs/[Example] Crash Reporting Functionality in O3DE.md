# Description

Game crashes may occur when the game application attempts to perform an operation that the operating system does not allow. Troubleshooting game crashes can be challenging, especially when a game targets multiple runtimes and operating systems. Crashes are frustrating for players, and can originate in many different parts of a code base, which makes it difficult for game developers to get and act upon meaningful feedback about why their application has crashed in a particular context.

A crash reporting pipeline/workflow for applications built using the O3DE engine will enable developers to implement a solution that enables their teams to get automated reports sent back from end users when application crashes occur. This reporting should include information that is helpful for debugging and reproducing crashes, including (but not limited to): 

* Active scene
* Level loaded
* Log files
* Video replays
* Event stack / history (breadcrumbs)

The crash reports should be generated in such a way that they can be utilized with different crash reporting solutions. Companies that offer solutions for tracing and reporting application crashes can then build Gems / integrations that plug into the engine so that developers can select services.

# Open Questions
What is the full list of default and configurable attributes that should be included?
