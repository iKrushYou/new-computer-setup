# New Computer Setup

## System Setup

### zshrc
```shell
cp zshrc "~/.zshrc"
```

### Display
`Settings > Displays > Built-in Display > More Space`

## Applications

### Homebrew
```shell
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

### MacDown
```shell
brew install --cask macdown
```

**note:** must open via `Option + Right Click > Open`

### iTerm2
```shell
brew install --cask iterm2
```

### iStats Menu
```shell
brew install --cask istat-menus
```

`iStats Menu > Registration > `

```
GAWQE-FCYUJ-46FSU-LQP9G-NBNPT-MTEG4-QLHZP-SWP9C-CUAKF-7RGQY-8AH5G-D4JFU-9KJAH-Y8HNX-4GT5V-Q
```

`File > Import Settings... > ./new-computer-setup/iStat Menus Settings.ismp`

### Zed
```shell
brew install --cask zed
```
Zed > Install CLI

### Bartender
```shell
brew install --cask bartender
```
- Start at login (on)
- Click on empty menu bar space (off)

### Fusion 360 Insider
[Download](https://urldefense.proofpoint.com/v2/url?u=https-3A__feedback.autodesk.com_project_article_default.html-3Fcap-3D326ccb1f9653409c8884c57523f9e054-26arttypeid-3Da2f073b62b8e493c804fa67ca5d0bfee&d=DwMFaQ&c=slrrB7dE8n7gBJbeO0g-IQ&r=xyEx6ZMW7Cvhn1Z4JVamjw&m=6yjjaEr7gjeT7n3qq-27dA7yEB4y_Zvfp3G0EORhKUlZtS0fEWNifiKmnxagVNIa&s=zK1CxKgwuWFWEl-ISVSHMGL8n4axdSvhTqqSvjFLWZU&e=)

### Cura
```shell
brew install --cask ultimaker-cura
```

Settings

```shell
cp cura "/Users/alexkrush/Library/Application Support/"
```

### Google Chrome
```shell
brew install --cask google-chrome
```

## UI Development

### Node Version Manager (NVM)
```shell
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash
nvm alias default node
nvm install node
```

### Bun
```shell
brew tap oven-sh/bun
brew install bun
```



