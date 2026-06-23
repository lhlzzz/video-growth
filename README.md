<div align="center">
<h1 align="center">Video Growth 📱</h1>

<p align="center">
  <a href="https://github.com/lhlzzz/video-growth/stargazers"><img src="https://img.shields.io/github/stars/lhlzzz/video-growth.svg?style=for-the-badge" alt="Stargazers"></a>
  <a href="https://github.com/lhlzzz/video-growth/issues"><img src="https://img.shields.io/github/issues/lhlzzz/video-growth.svg?style=for-the-badge" alt="Issues"></a>
  <a href="https://github.com/lhlzzz/video-growth/network/members"><img src="https://img.shields.io/github/forks/lhlzzz/video-growth.svg?style=for-the-badge" alt="Forks"></a>
  <a href="https://github.com/lhlzzz/video-growth/blob/main/LICENSE"><img src="https://img.shields.io/github/license/lhlzzz/video-growth.svg?style=for-the-badge" alt="License"></a>
</p>

<br>

Video account growth & monetization: content strategy, viral pattern library, and low-pressure monetization for blue V accounts.

<br>
</div>

## Features

- **Content Strategy** - AI tools / efficiency templates / small business automation
- **Viral Pattern Library** - High-retention patterns, opening 3s hooks, drop reasons
- **Platform Rules Memory** - Douyin/WeChat Video compliance rules
- **Video Production** - Remotion-based video generation with TTS
- **Low-Pressure Monetization** - Blue V accounts, faceless content, document products

## Prerequisites

| Requirement | Version | Notes |
|-------------|---------|-------|
| Python | 3.11+ | Required |
| pip | Latest | Python package manager |
| Node.js | 18+ | For Remotion video building (optional) |

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/lhlzzz/video-growth.git
cd video-growth
```

### 2. Install Python dependencies (core)

```bash
pip install -r requirements.txt
```

Or install manually:

```bash
pip install edge-tts
```

### 3. Install Node.js dependencies (for video building, optional)

```bash
npm install
```

### 4. Verify installation

```bash
python3 self_media_profit_agent.py --help
```

## Usage

### Run the profit agent

```bash
python3 self_media_profit_agent.py
```

### Build video from script

```bash
python3 scripts/build-video.py
```

### Generate TTS audio

```bash
python3 scripts/generate-tts.py
```

### Browse viral patterns

```bash
ls viral_pattern_library/
cat viral_pattern_library/INDEX.md
```

### Check platform rules

```bash
cat platform_rules_memory/INDEX.md
```

### Review high retention patterns

```bash
cat high_retention_pattern_library/INDEX.md
```

## Architecture

```
video-growth/
├── self_media_profit_agent.py          # Main profit agent
├── scripts/
│   ├── build-video.py                  # Remotion video builder
│   ├── generate-tts.py                 # Edge TTS generator
│   └── samples/                        # Script samples
├── viral_pattern_library/              # Viral content patterns
├── opening_3s_library/                 # First 3s hook library
├── platform_rules_memory/              # Platform compliance rules
├── high_retention_pattern_library/     # High retention patterns
├── drop_reason_library/                # Why viewers leave
├── content_production_validation_engine/  # Content validation
├── reports/                            # Strategy reports
├── requirements.txt                    # Python dependencies
└── package.json                        # Node.js dependencies (optional)
```

## Content Strategy

### P0 Direction

- **AI Tools** - Productivity tools, automation guides
- **Efficiency Templates** - Ready-to-use document templates
- **Small Business Automation** - Low-cost business solutions

### Monetization Paths

1. Blue V Account Operations
2. Faceless Content Production
3. Document Products (low-price)
4. Product Showcase Monetization

## Video Production

### Using Remotion (optional)

```bash
# Install dependencies
npm install

# Build video
python3 scripts/build-video.py
```

### Using Edge TTS

```bash
pip install edge-tts
python3 scripts/generate-tts.py
```

## Safety

- **No Live Actions** - No publishing without approval
- **Research Only** - All outputs for internal review
- **Compliance First** - Platform rules checked before content

## Troubleshooting

### "ModuleNotFoundError: No module named 'edge_tts'"

```bash
pip install edge-tts
```

### Node.js not found (for video building)

Install from https://nodejs.org/ or skip video building features.

### Permission denied on scripts

```bash
chmod +x scripts/*.py
```

## License

MIT License
