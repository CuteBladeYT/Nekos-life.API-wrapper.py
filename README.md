# Better Nekos.py
## AKA Better Nekos.life API wrapper for Python

### Table of contents
| Section | Description |
| --- | --- |
| [License](#license) | Project's license |
| [Requirements](#requirements) | List of anything you need to run the wrapper |
| [Usage](#usage) | How to use the wrapper |
| [Installation](#installation) |  How to install the wrapper|

### License
This project is licensed under [GPL-3.0](https://github.com/CuteBladeYT/Nekos-life.API-wrapper.py/blob/main/LICENSE), as the original API wrapper is licensed under this license.

<br>

### Requirements

| Requirement | Version | Source |
| --- | --- | --- |
| Python | >= 3.8.10 | [python.org](https://python.org/) |

| Module | Version | Install with ... | Source |
| --- | --- | --- | --- |
| requests | 2.27.1 | `pip install requests` | [pypi.org](https://pypi.org/project/requests/) |

<br>

### Usage
You have to include this module in your Python file first. Refer to [installation guide](#installation).<br>
After you do so, you can use `get_neko()` function. It requires two arguments, neko type and optional query text.<br>
<br>
**Example usage:**
```py
from nekos import get_neko

print(get_neko("neko"))
# Output: https://cdn.nekos.life/neko/neko_425.png
```
Here you have list of all available options:
- tickle
- slap
- poke
- pat
- neko
- meow
- lizard
- kiss
- hug
- fox_girl
- feed
- cuddle
- why
- cat
- owoify
- fact
- ngif
- smug
- baka
- woof
- spoiler
- wallpaper
- goose
- gecg
- avatar
- waifu
- 8ball

<br>

### Installation

| Requirement | Version | Source |
| --- | --- | --- |
| git | >= 2.25.1 | [git-scm.com](https://git-scm.com/) |

To install run in CMD / Terminal
```
git clone https://github.com/CuteBladeYT/Nekos-life.API-wrapper.py
cd Nekos-life.API-wrapper.py
```
Then in file explorer copy `nekos.py` file and paste it in your project's directory, optionally project's modules directory.<br>
Then in your python file you have to include `sys` and `os` modules, if you do so use this
```py
modules_path = "" # PATH TO MODULE'S DIRECTORY
sys.path.append(os.path.relpath(modules_path))
import nekos
```
Then you're ready to go.
