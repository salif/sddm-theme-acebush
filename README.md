# sddm-theme-acebush

Acebush is a theme for the SDDM login manager named in honor of Aaron Bushnell.

![](./media/screenshot.png)

## Install

```bash
# Clone this repo
git clone https://codeberg.org/salif/sddm-theme-acebush.git
cd sddm-theme-acebush
# Create theme.conf.user and edit it for customizing
cp theme.conf theme.conf.user
cp -r ./ /usr/share/sddm/themes/acebush
```

Add this to `/etc/sddm.conf`:

```toml
[Theme]
Current=acebush
```

## Uninstall

```bash
# You can backup `theme.conf.user` if you want
# Then delete the directory:
sudo rm -r /usr/share/sddm/themes/acebush
```
