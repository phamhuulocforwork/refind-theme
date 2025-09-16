# rEFInd rich black theme

![screenshot](screenshot.png)

## Installation

1. Clone the git repository

   ```bash
   git clone https://github.com/phamhuulocforwork/refind-theme.git
   ```

2. Copy the theme to the rEFInd directory. This is usually `/boot/EFI/refind/`.

   ```bash
   sudo cp -r refind-theme /boot/EFI/refind/
   ```

3. To adjust icon size and font size edit `theme.conf`.

   ```bash
   sudo nano /boot/EFI/refind/refind-theme/theme.conf
   ```

4. To enable the theme add `include refind-theme/theme.conf` at the end of `refind.conf`.

   ```bash
   sudo nano /boot/EFI/refind/refind.conf
   ```

[rEFInd](http://www.rodsbooks.com/refind/) The official rEFInd website
