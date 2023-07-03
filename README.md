[Instructions on how to compile and run the software]

1. Open the RecipeApplication solution in your preferred Integrated Development Environment (IDE), such as Visual Studio.
2. Make sure that the solution builds successfully by checking for any build errors.
3. Set the RecipeApplication project as the startup project in your IDE. This ensures that it is the project that runs when you execute the application.
4. Configure the target platform for the application. For a WPF application, ensure that the target platform is set to ".NET Framework" or ".NET Core" based on your setup.
5. Build the solution to compile the code. This will generate the necessary executable files and dependencies.
6. Once the build is successful, you can run the Recipe Application by selecting the "Start" or "Run" button in your IDE, or by pressing the "F5" key.
7. The RecipeApplication will launch, and the main menu will be displayed.
8. From the main menu, you can interact with the various options to enter new recipes, display recipes, select and view recipe details, scale recipes, reset recipe quantities, and clear all data.
9. Follow the on-screen instructions and user manual for each option to use the Recipe Application effectively.
10. To exit the application, click the "Close" button at the top-right corner of the main menu screen.

[My Link]



[Brief Description on what i Changed]

In the transition from a console application to a WPF (Windows Presentation Foundation) application, several changes were made to enhance the user experience and provide a graphical user interface (GUI) for the Recipe Application.

Project Type: The project type was changed from a console application to a WPF application. This change allowed us to leverage the capabilities of WPF, which provides a rich set of controls and features for building desktop applications.

User Interface Design: In a WPF application, the user interface is defined using XAML (eXtensible Application Markup Language). XAML allows for a declarative approach to designing the user interface, separating it from the application logic. The XAML file contains the layout and appearance of the application's windows and controls.

Window: In a WPF application, the main entry point is typically a window. We created a new WPF window that serves as the main menu of the Recipe Application. The window provides a container for hosting controls and defining the overall structure of the application's user interface.

Controls: The console-based text input/output was replaced with various WPF controls that provide a more interactive and visually appealing experience. Examples of controls used in the Recipe Application include buttons, text boxes, labels, list boxes, and menus. These controls allow users to input data, display information, and navigate through the application's functionalities.

Event Handling: WPF utilizes an event-driven programming model, where actions or events (such as button clicks) trigger corresponding event handlers in the code-behind file. In the WPF application, we added event handlers to handle user interactions with the controls, such as button clicks or menu selections.

Data Binding: WPF supports data binding, which allows for a seamless connection between the application's data and the user interface controls. We utilized data binding to bind the recipe data to the appropriate controls, ensuring that any changes in the data are automatically reflected in the user interface.

Styling and Theming: WPF provides powerful styling and theming capabilities. We added styles and applied them to the controls to customize their appearance and create a consistent visual theme throughout the application.

Overall, transitioning from a console application to a WPF application involved reimagining the user interface and redesigning the application flow using XAML and WPF controls. These changes resulted in a more interactive and visually appealing Recipe Application that offers a seamless user experience.
