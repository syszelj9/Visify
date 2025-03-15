# Visify - Real-Time Audio Oscilloscope

Visify is a real-time audio oscilloscope written in C that visualizes live audio input as a waveform.

## Features

- Captures audio input in real-time using **PortAudio**.
- Displays a waveform using **SDL2**.
- Supports **Fedora**, **Ubuntu**, and **Arch Linux** (Windows version coming soon!).

## Compatibility

| Operating System | Status         |
| ---------------- | -------------- |
| Fedora           | ✅ Supported    |
| Ubuntu           | ✅ Supported    |
| Arch Linux       | ✅ Supported    |
| Windows          | 🚧 Coming soon |

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/syszelj9/visify.git
   cd visify
   ```

2. Install the dependencies:
Fedora
    ```
    sudo dnf update -y
    ```
    ```
    sudo dnf install -y portaudio-devel SDL2-devel gcc make
    ```
  Arch
  ```
  sudo pacamn -Syu
  ```
  ```
  sudo pacman -Sy --noconfirm portaudio sdl2 gcc make
  ```
  Ubuntu/Debian
  ```
  sudo apt update -y
  ```
  ```
  sudo apt install -y libportaudio2 libportaudiocpp0 portaudio19-dev libsdl2-dev gcc make
  ```
## Usage

After installation, run the program with:

```bash
./visify
```

## Contributing

Contributions are welcome! Feel free to submit issues and pull requests.

## License

This project is licensed under the GNU GPL 3.0 License.

