GPXManager
GPXManager is a tool developed to visualize sport activities exported as GPX specifications. GPX (GPS eXchange Format) is a standard format for representing GPS data and exchanging it across different software programs. Many popular sport tracking apps, such as Strava and RunKeeper, use GPX for exporting activity data.

The main goal of GPXManager is to provide a local tool that allows users to import and visualize GPX files, perform basic calculations on the data, and assign sport activities to the files. The tool can be accessed either through a basic user interface or a command-line interface, depending on the user's preference.

Key Features
Import and visualize GPX files: GPXManager enables users to import GPX files and visualize them on a map. You can explore your activities and track your routes directly within the tool.

Assign sport activities: Users can assign specific sport activities to the GPX files they import. Whether it's running, cycling, hiking, or any other sport, GPXManager allows you to categorize your activities accordingly.

Compute metrics: GPXManager provides basic metric calculations based on the chosen sport activity. Users can obtain information such as total distance traveled, minimum and maximum altitudes, estimated calories burned, and more. The tool adapts to different sports, allowing for extensibility by incorporating additional types of sports and supporting new metrics.

Technical Details
GPXManager is designed to be launched locally on the end-user's machine, ensuring data privacy and security. The tool leverages a library (insert library name here) to visualize GPX files on a map. This library provides a seamless integration, enhancing the user experience and allowing for interactive exploration of activity routes.

To ensure the tool's extensibility, GPXManager follows a modular approach that separates the sports activities from the metric calculations. This design allows for easy incorporation of new sports and metrics in the future, ensuring that the system remains versatile and adaptable.
