# Hi there 👋

### About me:

- 🔭 I’m currently working on alot of things but i'll mention the portfolio for a friend only right now.
- 🌱 I’m currently learning Django Rest Framework, MobX, NextJS.
- 👯 I’m looking to collaborate on projects based on web technologies.
- 📫 How to reach me: LinkedIn, Mail or Discord. (Contact: https://gabrieldahlberg.com/about)
- ⚡ Fun fact: I like monkey gifs alot.
- 🏎️ Trackmania: BroderGaBoo

# Mac Setup

This is my take on the following article and how i prefer my setup https://betterprogramming.pub/how-to-set-up-your-macbook-for-web-development-in-2021-a7a1f53f6462.

## macOS Settings ⚙️

Let’s start with a few changes you can make to macOS and the built-in apps.

### System preferences

#### Keyboard ⌨️

``` Keyboard > T️️ouch Bar Shows: F1, F2, etc. Keys ```

``` Keyboard> Press Fn key to: Show Control Strip ```

These two settings are about the touch bar. As a developer, I find myself using the F keys more often (a lot of shortcuts rely on them) than the other options — so I prefer to have them be the default.

#### Dock ⚓

️️``` ☑️ Automatically hide and show the Dock ```

More often than not, I use Spotlight (⌘ Space) or the terminal to launch applications instead of the dock — it’s hard to justify dedicating such display real estate to it. Besides, you can easily access it by moving your mouse to the bottom of the screen or by pressing ⌃ F3.

#### Trackpad 🐭

``` Point & Click > ️️☑️ Tap to click ```

Once you get used to it, it’s way faster to tap instead of click.

#### Accessibility 🎩

``` Pointer Control > Mouse & Trackpad > Trackpad Options… > ️️☑️ Enable dragging ```

By enabling trackpad dragging, you’ll be able to drag files, select text, etc., by double tapping (and holding the second tap).

### Finder 🔍

#### Preferences

``` Preferences > Advanced > ☑️ Show all filename extensions ```

#### View options

``` View > Show Path Bar ```
``` View > Show Status Bar ```

#### Show hidden files

Type ``` defaults write com.apple.Finder AppleShowAllFiles true ``` in terminal,
or press ⇧⌘ .



## Command-line Tools 👨‍💻

Now the fun part! These are the command line–related tools I recommend for any web developer.

### Homebrew 🍺
This is the package manager. It allows you to install, uninstall, and update command-line tools and Mac applications.
To install it, open the terminal, and run this command:
``` /bin/bash -c “$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"```

During the installation, you might be asked to install the Xcode Command Line Tools if you haven’t already — just follow the instructions on the screen.
To make sure your system is ready to brew, run ``` brew doctor ```.

You can now search for packages with brew search and install them with brew install. You can also list installed packages with brew list.
To update the packages’ local registry you can run ```brew update```, and to upgrade the installed packages to their latest versions, type ``` brew upgrade ```.
I recommend running ``` brew doctor ``` every now and then to make sure things are good and brew cleanup to remove unused files.

### iTerm2 🖥️

This is an optional replacement for the terminal app. It offers a lot of really useful features. I’ll list my favorite ones below.
To install it, open the terminal (this is the last time you’ll need it), and run the following:

``` brew install --cask iterm2 ```

Now, feel free to replace terminal from the Dock (if you have it) with iTerm2. Or just open Spotlight (⌘ Space) and type iTerm2.

### Git 👽

The most popular version-control system. You can install it with Homebrew:

``` brew install git ```

### Zsh 🐲

As macOS’s default shell since Catalina, Zsh is built on top of Bash and provides many cool features.
The first thing I recommend is having Homebrew manage its installation — open iTerm2, and run:

``` brew install zsh ```

### Oh My Zsh 🐉

Oh My Zsh is a community-driven framework for managing your Zsh configuration. It provides hundreds of plugins and themes and makes configuring Zsh a breeze.
To install Oh My Zsh, run:

``` sh -c “$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)" ```

### Theme 😏
Powerlevel10k is my theme of choice — it’s fast, it’s really well integrated with Git, it supports icons, and a lot more.

It has a really nice wizard that walks you through configuring it the first time that you run it:

![This is an image](https://miro.medium.com/max/700/1*9pUV32lfdQqBOFUn7vaAzQ.gif)

To install it with Homebrew, run:

``` brew install romkatv/powerlevel10k/powerlevel10k ```

And add the following line to your .zshrc:

``` source /usr/local/opt/powerlevel10k/powerlevel10k.zsh-theme ```

It’ll override any value you have set to$ZSH_THEME.
Restart iTerm2, and you should see the configuration wizard. In the future, you can run it again with p10k configure.

For additional customization with my preferred plugins added to the theme i recommend watching this video:
https://www.youtube.com/watch?v=D2PSsnqgBiw&list=LL

### Node.js 📦

The JavaScript runtime built on Chrome’s V8 JavaScript engine. This is the most popular framework for running and building web applications.
To install it, run:

``` brew install node ```

If you need to manage multiple applications that need different versions of Node, I recommend nodenv.

### Docker 🐋

Docker allows you to develop and deliver software in packages called containers. Containers are isolated from one another and bundle their own software, libraries and configuration files.

To install it, run:

``` brew install --cask docker ```

You should also check out lazydocker, a great CLI tool for docker and docker-compose.

### Visual Studio Code 📝

The best IDE/editor for web development at the moment (in my opinion, of course). It’s fast with tons of extensions, and it’s open-source.
To install it, run:

``` brew install --cask visual-studio-code ```

You can find lots of great extensions for the most popular languages and frameworks in the Visual Studio Marketplace.

Extensions:
- Atom One Dark 
- vscode-icons

# Windows Setup(In progress)🚧

https://pureinfotech.com/install-windows-subsystem-linux-2-windows-10/
