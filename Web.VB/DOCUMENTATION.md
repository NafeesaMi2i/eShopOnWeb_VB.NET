# eShopOnWeb_VB.NET Technical Documentation

## Table of Contents
- [Introduction](#introduction)
- [Application Architecture](#application-architecture)
  - [Front-end Libraries](#front-end-libraries)
- [Application Workflow](#application-workflow)
- [Developer Guidelines](#developer-guidelines)
- [Further Reading](#further-reading)

## Introduction
eShopOnWeb_VB.NET is an online shopping web application designed to provide a robust platform for e-commerce activities. It serves as a reference architecture for building scalable, cloud-native applications. The target audience includes developers seeking to understand modern web application patterns and users looking for a comprehensive e-commerce solution.

## Application Architecture
The application is built using VB.NET, a modern, object-oriented programming language, and ASP.NET Core, a high-performance, open-source framework for building web applications. The architecture is designed to be modular, testable, and scalable, adhering to the principles of clean architecture.

### Front-end Libraries
- `@aspnet/signalr`: This library enables real-time communication between the client and server, allowing for features such as live chat and instant updates without the need for page refreshes.
- `Vazor`: Vazor is utilized for dynamically generating HTML views using VB.NET syntax, which allows for a more fluid development experience within the VB.NET ecosystem.
- `bootstrap`: Bootstrap provides a collection of CSS and JavaScript tools for creating responsive and mobile-first web pages, ensuring a consistent and modern user interface across various devices.
- `jquery` and `jquery-validate`: jQuery simplifies HTML document traversal and manipulation, event handling, and animation. The `jquery-validate` plugin adds powerful validation methods to ensure user input is correct and formatted properly.
- `jquery-validation-unobtrusive`: This library integrates with ASP.NET Core's validation attributes to provide a clean, minimalistic validation approach that doesn't rely on inline scripts.
- `toastr`: Toastr is used for displaying non-blocking notifications to the user, enhancing the user experience by providing immediate feedback in a non-intrusive manner.

## Application Workflow
The application follows a request-response pattern where user actions trigger HTTP requests to the server. The front-end, built with the libraries mentioned above, communicates with the back-end through API calls. The back-end, powered by VB.NET and ASP.NET Core, processes these requests, interacts with the database, and returns the appropriate responses, which are then rendered on the front-end.

## Developer Guidelines
Developers looking to work with the codebase should first set up their development environment by installing Visual Studio with VB.NET and ASP.NET Core support. The application can be run locally by opening the solution file and starting the debugger. Contributions to the project should follow the established coding standards and include comprehensive tests to ensure quality and functionality.

## Further Reading
For more in-depth knowledge on the technologies and patterns used in this application, consider exploring the following resources:
- [ASP.NET Core Documentation](https://docs.microsoft.com/en-us/aspnet/core/)
- [Bootstrap Documentation](https://getbootstrap.com/docs/)
- [jQuery API Documentation](https://api.jquery.com/)
- [SignalR Documentation](https://docs.microsoft.com/en-us/aspnet/core/signalr/)
- [Clean Architecture](https://docs.microsoft.com/en-us/dotnet/architecture/modern-web-apps-azure/common-web-application-architectures)
