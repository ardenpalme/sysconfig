# Arch Linux System Configuration

- R libraries at /home/linux/R/x86_64-pc-linux-gnu-library/4.5

TODO:
- battery is at 89% capacity `sudo tlp-stat -b`
- Cron job for full system update every 2 weeks
- battery below threshold 10% dunst notification script (perhaps also cron job)
- Connect to external display: `xrandr --output HDMI-1 --auto --left-of eDP-1`
- play CD: `sudo mount -o ro /dev/sr0 /mnt/apple_cd`
Brave - Winedrive Google ext for movies

PyTorch GPU install:
``uv pip install torch==2.7.1+xpu torchvision==0.22.1+xpu torchaudio==2.7.1+xpu intel-cmplr-lib-rt intel-cmplr-lib-ur intel-cmplr-lic-rt intel-sycl-rt pytorch-triton-xpu tcmlib umf intel-pti --index-url https://download.pytorch.org/whl/xpu``
