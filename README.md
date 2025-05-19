# Wake-on-Bluetooth

Enable your PC to wake from sleep or suspend when a paired Bluetooth device (controller, keyboard, mouse, etc.) reconnects or sends input.

## Installation

Simply run:

```bash
curl -s -o /tmp/install https://raw.githubusercontent.com/EnriqueWood/wake-on-bluetooth/refs/heads/main/install && \
chmod +x /tmp/install && \
/tmp/install && \
rm /tmp/install
```

After installation, the script will automatically reload udev rules and enable the service (if applicable).

## Usage

- Put your machine to sleep with `systemctl suspend` or from GUI.  
- Send input from your paired Bluetooth device—the PC will wake automatically.
