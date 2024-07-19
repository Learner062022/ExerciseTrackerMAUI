# ExerciseTrackerMAUI

## Overview
This is a .NET MAUI app designed to track exercise minutes, providing various metrics and customizable settings for a personalized experience. This project strictly adheres implements the MVVM architecture for better code maintainability and scalability.

## Features
- **Yearly Daily Average**:
    - Calculates and displays daily average minutes.
    - Highlights average in red if below 30 minutes, otherwise in green.
- **Total Hours**:
    - Shows total hours excercised and hours needed to meet goals.
- **Daily Goal Adjustment**: 
    - Displays minutes needed daily to achieve a 30-minute average.
- **Yearly Reset**:
    - Automatically resets data on January 1st.
- **Settings Screen**: 
    - Customize background and text colors.
    - Adjust daily exercise (5 minutes to 1 hour).
    - Manually reset data.
- **Data Persistence**:
    - Saves user data across sessions.


## Why The Project is Useful
Showcases the implementation of the MVVM architecture in .NET MAUI, demonstarting how to build a modern, maintainable and scalable application. 

## Getting Started

### Prerequisites
Ensure you have .NET MAUI installed. Follow the installation guide [here](https://docs.microsoft.com/en-us/dotnet/maui/get-started/installation) if not.

### Installation
1. Clone the repository:
```sh
git clone https://github.com/Learner062022/ExerciseTrackerMAUI.git
```
2. Navigate into the project directory:
```sh
cd ExerciseTrackerMAUI
```
3. Restore dependencies:
```sh
dotnet restore
```
4. Build the project:
```sh
dotnet build
```
5. Run the project:
```sh
dotnet run
```

## Where to Get Help
- **Documentation**: Refer to the official [.NET MAUI Documentation](https://docs.microsoft.com/en-us/dotnet/maui/) for more details on framework usage.
- **Community Support**: Join the [.NET MAUI Community](https://github.com/dotnet/maui) on GitHub for discussions and support.
- **Issues**: Report issues or bugs [here](https://github.com/YourUsername/ExerciseTrackerMAUI/issues) for project-specific help.
- **Stack Overflow**: Search for common issues or ask questions using the `dotnet-maui` tag on [Stack Overflow](https://stackoverflow.com/questions/tagged/dotnet-maui).