# Profile Avatar Menu

Replaces the application menu (hamburger) button icon with your Mozilla account profile avatar when signed in.

## How It Works

Firefox/Zen Browser exposes two key pieces of information when you're signed in:
- `fxastatus="signedin"` attribute on the root element
- `--avatar-image-url` CSS variable containing your profile picture URL

This mod uses these to replace the hamburger menu icon with your avatar.

## Features

- Automatically shows your profile avatar on the hamburger menu when signed in
- Falls back to default avatar icon if no custom avatar is set
- Optional border styling around the avatar
- Option to hide the separate FxA toolbar button

## Requirements

- Zen Browser or Firefox with userChrome.css support
- Signed in to Mozilla/Firefox Account
- Custom profile picture uploaded (for personalized avatar)

## Options

| Option | Description | Default |
|--------|-------------|---------|
| Show border | Display accent color border around avatar | Off |
| Hide FxA button | Hide the Firefox Account toolbar button | Off |

## Installation

### Via Zen Mods Registry
1. Open Zen Browser
2. Go to Mods settings
3. Search for "Profile Avatar Menu"
4. Click Install

### Manual Installation
1. Copy `chrome.css` to your profile's chrome folder
2. Restart browser

## License

MIT
