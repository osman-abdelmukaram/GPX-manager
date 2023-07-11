# GPXManager
**GPXManager** is a tool developed to visualize sport activities exported as GPX specifications. GPX (GPS eXchange Format) is a standard format for representing GPS data and exchanging it across different software programs. Many popular sport tracking apps, such as Strava and RunKeeper, use GPX for exporting activity data.

## Key Features
- **Import and Visualize GPX Files**: GPXManager enables users to import GPX files and visualize them on a map. You can explore your activities and track your routes directly within the tool.

- **Assign Sport Activities**: Users can assign specific sport activities to the GPX files they import. Whether it's running, cycling, hiking, or any other sport, GPXManager allows you to categorize your activities accordingly.

- **Compute Metrics**: GPXManager provides basic metric calculations based on the chosen sport activity. Users can obtain information such as total distance traveled, minimum and maximum altitudes, estimated calories burned, and more. The tool adapts to different sports, allowing for extensibility by incorporating additional types of sports and supporting new metrics.

## Technical Details
GPXManager is designed to be launched locally on the end-user's machine, ensuring data privacy and security. The tool leverages a library (insert library name here) to visualize GPX files on a map. This library provides a seamless integration, enhancing the user experience and allowing for interactive exploration of activity routes.

To ensure the tool's extensibility, GPXManager follows a modular approach that separates the sports activities from the metric calculations. This design allows for easy incorporation of new sports and metrics in the future, ensuring that the system remains versatile and adaptable.
