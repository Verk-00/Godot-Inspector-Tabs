# Godot Inspector Tabs
Godot add-on for spliting the inspector property classes into its own tabs. So that its shorter and require less scrolling.

Vertical layout:

![image](https://github.com/user-attachments/assets/fc5455d2-c48d-4e1f-b51f-4c09e2d4eb83)

Horizontal layout:

![Untitled](https://github.com/user-attachments/assets/e2849982-a57f-46d6-bcfa-c38676032b9d)


# Features
- An option for horizontal/vertical tab layout. (Can be change in the editor_settings/interface/inspector/tab_layout)
- An option to add/remove text and icon on the tabs. (Can be change in the editor_settings/interface/inspector/tab_style)
- Settings is synced to all projects.
- Support custom script classes.
- Favorite property will be shown in all tabs.

# Known problems
- Custom node from GDExtension will not be shown in the inspector.
- Resizing the inspector dock is kind of glitchy especially if the dock is made floating.
