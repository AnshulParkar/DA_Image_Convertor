Overview:
This Python GUI application serves as a simple image converter, allowing users to change the format of images, such as converting from JPEG to PNG or vice versa. It offers several features, including adding filters to images, adjusting image colors, and performing file compression to reduce file size.

Description of Python Packages Used:

Tkinter: Tkinter is a standard GUI (Graphical User Interface) toolkit for Python. It provides various widgets, such as buttons, labels, and frames, to create user-friendly interfaces.

Pillow (Python Imaging Library - Fork): Pillow is a powerful library for image processing tasks in Python. It provides support for opening, manipulating, and saving many different image file formats.

Description of Different Functions and Classes Used from External Packages:

Image: This class from the Pillow library represents an image. It is used to open image files, apply various transformations, and save the modified images.

ImageChops: The functions in this module provide simple image arithmetic and logical operations. It's used for operations like inverting colors or combining images.

ImageFilter: This module contains a collection of filters that can be applied to images. It's used for operations like blurring, sharpening, or edge detection.

filedialog: This module from Tkinter provides dialogs to open and save files. It's used to prompt users for file selection when adding or saving images.

messagebox: This module from Tkinter provides a simple way to create message boxes for displaying alerts or prompts. It's used to show error messages or confirmation dialogs.

ttk (Themed Tkinter): This module provides access to the Tk themed widget set. It's used to create styled buttons and comboboxes, improving the appearance of the GUI.

By combining Tkinter for the user interface and Pillow for image processing, this application offers a user-friendly way to convert image formats and perform basic image manipulations. It's suitable for both Windows and Linux systems, with potential for further enhancements and platform compatibility testing.
