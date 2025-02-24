# FFrame - Fast Frame Encoder

FFrame is a modern, high-performance video encoding and remuxing application built in Rust. It provides an intuitive graphical interface for video processing tasks while maintaining professional-grade output quality.

## Features

### Core Functionality
- Advanced video encoding with multiple codec support (H.264, H.265, VP9, AV1, ProRes)
- Container format conversion (MP4, MKV, MOV, WebM)
- Hardware-accelerated encoding support
- Intelligent preset system for common use cases
- HDR tone mapping with multiple algorithms

### Video Processing
- Comprehensive video encoding options
- Frame rate conversion
- Resolution scaling
- Video filter support
- Subtitle handling and burn-in
- Chapter preservation

### Audio Processing
- Multi-track audio support
- Various audio codec options (AAC, MP3, AC3, FLAC, etc.)
- Channel mixing and mapping
- Audio normalization
- Sample rate conversion
- Audio filters (high-pass, low-pass)

### Advanced Tools
- Media information viewer
- Video download capabilities
- Frame interpolation (coming soon)
- AI-powered audio processing (coming soon)
- Deep learning-based frame synthesis (coming soon)

## System Requirements

- Operating System:
  - Windows 10/11 (64-bit)
  - macOS 10.15 or later
  - Linux (modern distributions)
- Minimum 4GB RAM
- Graphics card with DirectX 11/Metal/Vulkan support for hardware acceleration
- Internet connection for updates and online features

## Installation

1. Download the latest release for your operating system
2. Run the installer package
3. Follow the installation wizard instructions
4. Launch FFrame from your applications menu

## Building from Source (currently closed source, will be open source soon)

### Prerequisites
- Rust 1.70 or later
- Cargo package manager
- FFmpeg development libraries
- System-specific build dependencies

### Build Instructions

1. Clone the repository

```bash
git clone https://github.com/madelyn1337/FFrame
cd FFrame
```

2. Build the application

```bash
cargo build --release
```

3. The binary will be located in `target/release/fframe`

## Configuration

FFFrame stores its configuration in the following locations:

- Windows: `%APPDATA%\FFFrame\config.json`
- macOS: `~/Library/Application Support/FFFrame/config.json`
- Linux: `~/.config/fframe/config.json`

## Development

FFrame is built with:
- Rust programming language
- egui for the user interface
- FFmpeg for media processing
- Various Rust crates for additional functionality

## License

FFrame is proprietary software. All rights reserved.

## Support

For support, bug reports, or feature requests:
- Visit our website: [fframe.dev](https://fframe.dev)
- Join our Discord community: [Discord](https://discord.gg/fframe)
- Follow us on YouTube: [@fframe](https://youtube.com/@fframe)

## Acknowledgments

FFrame utilizes the following open-source projects:
- FFmpeg
- egui
- yt-dlp
- MediaInfo

## Contributing

While FFFrame is closed-source, we welcome feedback and feature suggestions through our official channels.

## Authors

- madelyn1337 - Founder & Head Developer
- nuruodo - Head of Marketing, Graphics & Co-founder
