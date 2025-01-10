Ubuntu Riced Setup

Welcome to my first riced setup for Ubuntu! This README provides an overview of the customization I've done to transform my Linux desktop into a more visually appealing and functional workspace.

Features

Terminal Customization

Transparency: The terminal has been made semi-transparent to add a modern and sleek look.

Font: Updated the terminal font to a stylish and readable option for a better coding experience.

Theme: idk something black

Widgets

Added functional and aesthetic widgets to the desktop for quick access to important information like:

System monitoring (CPU, memory, and disk usage).


Screenshots
![Screenshot from 2025-01-10 22-25-53](https://github.com/user-attachments/assets/7db99dac-d95f-4b0a-ab00-c806c5ee0a93)


![Screenshot from 2025-01-10 22-28-40](https://github.com/user-attachments/assets/573913d9-8bd2-4e0c-b483-2f7710c3e78b)





Installation Instructions

Terminal

Open your terminal settings.

Navigate to the Appearance tab.

Adjust the Transparency slider as per your preference.

Change the font by selecting your desired font from the Font settings.


Widgets

Install Conky (or any widget tool you prefer):

sudo apt install conky

Download the widget configuration files:

Provide a link to your configuration files.

Copy the configuration files to the .config/conky directory:

mkdir -p ~/.config/conky
cp /path/to/config/files/* ~/.config/conky/

Start Conky:

conky

Additional Customizations

Wallpapers: Updated the desktop wallpaper to align with the theme.

Dock: Customized the dock is moved down
