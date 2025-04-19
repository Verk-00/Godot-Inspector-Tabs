# Godot Inspector Tabs
Godot add-on for spliting the inspector property classes into its own tabs. So that its shorter and require less scrolling.

Vertical layout           |  Horizontal layout
:-------------------------:|:-------------------------:
![](https://github.com/user-attachments/assets/fc5455d2-c48d-4e1f-b51f-4c09e2d4eb83)  |  ![](https://github.com/user-attachments/assets/e2849982-a57f-46d6-bcfa-c38676032b9d)

# Features
- An option for horizontal/vertical tab layout. (Can be change in the `editor_settings/interface/inspector/tab_layout`)
- An option to add/remove text and icon on the tabs. (Can be change in the `editor_settings/interface/inspector/tab_style`)
- The built-in property filter will search for properties on all tabs.
- Settings is synced to all projects.
- Support custom script classes.
- Favorite property will be shown in all tabs.

# Known issues
- Custom node from GDExtension will not be shown in the inspector.
- Resizing the inspector dock is kind of glitchy especially if the dock is made floating.

# Installing
Soon you will be able to get it from the godot [asset lib](https://godotengine.org/asset-library/asset). but for now you have to install it manually:

- Download the files.
- Place the addon folder into your the root of your project.
- In the project, go to `project_settings/plugins` and enable the plugin.
