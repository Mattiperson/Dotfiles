<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
  * [Built With](#built-with)
* [Getting Started](#getting-started)
  * [Dependencies](#dependencies)
  * [Nice things](#nice-things)
  * [Installation](#installation)
* [Contributing](#contributing)
* [License](#license)



### About the Project
A very intensly patched DWM config made mostly at 1 am.



### Built With

* Autostart
* Cycle layouts
* Fake Fullscreem 
* Full gaps
* Grid mode
* Restartsig
* Rotate stack
* Underline tag indicator



<!-- GETTING STARTED -->
## Getting Started

Just do the stuff and you should be good.



### Dependencies
* TerminessTTF Nerd Font
* Redshift
* Flameshot
```sh
yay -S nerd-fonts-terminess
sudo pacman -S redshift
sudo pacman -S flameshot
```



### Nice things

You can use my config without these things but they'll make it much better.
* slstatus config
* st config
* dmenu config
```sh
cd .config
```
```sh
git clone https://github.com/Mattiperson/slstatus
git clone https://github.com/Mattiperson/st
git clone https://github.com/Mattiperson/dmenu
```
```sh
cd slstatus
sudo make clean install
cd
cd st
sudo make clean install
cd
cd dmenu
sudo make clean install
```

### Installation

1. Clone the repo
```sh
git clone https://github.com/Mattiperson/.dwm
```
2. Cd in and make install
```sh
cd .dwm
chmod +x autostart.sh
```
```sh
sudo make clean install
```
3. Enjoy



<!-- CONTRIBUTING -->
## Contributing

Contribution is pretty cool.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.
