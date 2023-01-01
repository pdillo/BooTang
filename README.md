## Preview
![preview](/img/screen.png)

## About
Booting is temporary. Boot-Tang is forever.

## Install
```bash
git clone https://github.com/pdillo/wu-grub.git
cd wu-grub
sudo cp wugrub -r /usr/share/grub/themes/
sudo vim /etc/default/grub
```
Change `#GRUB_THEME=` to
`GRUB_THEME="/usr/share/grub/themes/wugrub/theme.txt"`
```bash
sudo grub-mkconfig -o /boot/grub/grub.cfg
```
If all works correctly you should get this line in the out put:
```bash
Found theme: /usr/share/grub/themes/wugrub/theme.txt
```

## Credit
- [Tartarus Grub](https://github.com/AllJavi/tartarus-grub)
- [Cute Ghost profile](https://www.flaticon.com/free-icon/ghost_1150381?term=ghost&page=1&position=52&page=1&position=52&related_id=1150381&origin=style)
- [Dracula Grub](https://draculatheme.com/grub)
- [Tokyo Night Grub](https://github.com/mino29/tokyo-night-grub)

## License
[MIT License](./LICENSE)
