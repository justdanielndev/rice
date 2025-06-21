# Dan (Z)'s Rice

My first ever rice! I wanted to build something that was heavily customized yet looked very clean, cute and glassed :D and that was usable by anyone, regardless of their technnical knowledge. I think I did quite a good job!

![Demo Screenshot](https://github.com/justdanielndev/rice/blob/main/demo.png?raw=true)

## What does this use?

This rice is quite lightweight and can be installed on a bare bones Ubuntu distro!

It changes the "native" Ubuntu Desktop (GNOME) settings, adds and configures a bunch of useful extensions to get the amazing look we currently have, and configures conky as well for the desktop widget. In addition, it also comes with a very nice matching wallpaper!

## How to install?

Quite simple:

1. Clone the repo (`git clone https://github.com/justdanielndev/rice`).

2. Install [SaveDesktop](https://flathub.org/apps/io.github.vikdevelop.SaveDesktop). This will esentially take aaaall the rice files and install them.

3. Open the app, go to Import at the top and then Import from folder. Choose the `rice` folder from the repo you cloned before.

4. We're almost there! Now, run `sudo apt install conky-all` to install conky on your system, and once its installed, copy all the files in the `home-folder` folder in this repo to your home folder. Finally, run `conky` and add it to your startup apps!

5. (optional) Set the wallpaper to be [the one from this repo](https://github.com/justdanielndev/rice/blob/main/background.jpg?raw=true) (located in the root of the repo).

### Tips

You can go to the "Extensions" app and customize each and every extension's settings from there, no need to change files! I personally suggest you change all of the blur settings in Blur my shell to customize the look to your needs.