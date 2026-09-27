<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=22&pause=1000&color=FF0055&background=05050A&center=true&vCenter=true&width=620&height=100&lines=%5B%21%5D+MASHRUKH+%2F%2F+RED+TEAM+OPS;root%40astra%3A~%23+bypass_auth+--force;%5BSTATUS%5D+AUTHENTICATED" alt="Red Cyber Box" />
</div>



# AstraLoradTeam
Ethical hacker and cybersecurity researcher from Bangladesh securing systems and building open-source tools.  > **Disclaimer:** For educational and authorized testing only. Unauthorized access is illegal.
# fast boot adb tool
#!/data/data/com.termux/files/usr/bin/bash

directory="$(pwd)"
echo
echo -e "\e[93mThis script will install Astra Tools in Termux."
echo

# ... [preceding installation commands] ...

files="$(ls $downpath)"
cd $PREFIX/bin
chmod +x $files
echo -e "\e[32m[*] \e[34mCreating workspace directory..."
cd $HOME
if [ ! -d "astrafiles" ]; then
  mkdir astrafiles
fi
echo -e "\e[32m[*] \e[34mCleaning up..."
cd $directory
rm -rf $downpath
rm -rf InstallTools.sh
echo
# DarkFly-Tool
by mashrukh

The current main version is **DarkFly v5** – a modern Python 3 CLI that runs on current Linux/Termux systems. The previous **DarkFly v4.0** (Python 2, Termux-focused) installer is still included below as a legacy option.

In its original (v4) form, DarkFly-Tool is an installation tool for installing tools. this tool makes it easy for you. so you don't need to type git clone or look for the github repository. You only have to choose the number. which tool you want to install. there are 530 tools ready for intall. and for those of you who like to have fun. there are 7 SMS spam tools that are ready to use, you just need to choose spam to use the target number. there is a tocopedia DLL.

## Version comparison

| Feature                                      | DarkFly v5 (current) | DarkFly v4.0 (legacy) |
| -------------------------------------------- | -------------------- | ---------------------- |
| Python 3 support                             | ✓                    | ✗                      |
| Python 2 support                             | ✗                    | ✓                      |
| Target: Linux                                | ✓                    | ✗ (not reliable)       |
| Target: Termux                               | ✓                    | ✓                      |
| Actively maintained                          | ✓                    | ✗ (frozen legacy)      |
| Configurable tools via `darkfly_tools.json`  | ✓                    | ✗                      |
| Obfuscated/installer-based tool management   | ✗                    | ✓                      |

### Detailed comparison

| Aspect              | DarkFly v5 (current)                                           | DarkFly v4.0 (legacy)                                                |
| ------------------- | -------------------------------------------------------------- | -------------------------------------------------------------------- |
| Implementation      | Python 3 CLI in `darkfly/`                                     | Python 2 installer `install.py` plus `.module` and `lib` scripts     |
| Target environments | Linux and Termux with Python 3.10+ and pip                     | Primarily Termux (Android); regular Linux may not work reliably      |
| Status              | Active / modern path                                           | Frozen legacy path, kept for historical compatibility                |
| Install / usage     | `python -m pip install -e .[dev]` then `DarkFly5 ...`          | `python2 install.py` then `DarkFly`                                  |
| Tool list           | Config-driven via `darkfly_tools.json` (easy to extend/modify) | Hard-coded/obfuscated inside legacy Python 2 and `.module` artifacts |

---

## DarkFly v5 – modern Python 3 CLI (Linux / Termux)

DarkFly v5 is a new, configurable CLI that does **not** depend on the old Python 2 installer. It is implemented as a normal Python package in the `darkfly/` directory.

### Install (editable) for development

From a Python 3.10+ environment on Linux (or Termux with Python 3):

```bash
python -m pip install --upgrade pip
python -m pip install -e .[dev]
```

##### installs the `DarkFly5` command and development dependencies (like pytest).

### Usage

List available tools (from `darkfly_tools.json` or the built-in examples):

```bash
DarkFly5 list
```

Show details and suggested install commands for a specific tool:

```bash
DarkFly5 info nmap
```

Open a simple interactive menu:

```bash
DarkFly5 menu
```

You can add or change tools and categories by editing `darkfly_tools.json` in the repository root. The JSON structure is simple and designed to be extended over time.

### Running tests (modern CLI)

After installing with the `dev` extras:

```bash
pytest
```

This runs the tests under `tests/` for the modern Python 3 CLI.

---

## DarkFly v4 – legacy Python 2 installer (Termux)

> **Warning:** DarkFly v4 depends on Python 2 and is kept for historical compatibility. Modern systems may not ship Python 2 by default.
>
> If you specifically want this legacy version, download it from the v4 release:
> <https://github.com/reblox01/DarkFly-Tool/releases/tag/darkfly-v4.0.0>

### Information

DarkFly now is: <a href="https://github.com/Ranginang67/DarkFly-2019.1.git">DarkFly-2019.1</a> (generation of DarkFly-tool) Try it.

DarkFly-Tool is an installation tool for installing tools. this tool makes it easy for you. so you don't need to type git clone or look for the github repository. You only have to choose the number. which tool you want to install. there are 530 tools ready for intall. and for those of you who like to have fun. there are 7 SMS spam tools that are ready to use, you just need to choose spam to use the target number. there is a tocopedia DLL.

### Install (Termux)

**Termux:**

* `pkg install python2`
* `pkg install git`
* `git clone https://github.com/reblox01/DarkFly-Tool`
* `cd DarkFly-Tool`
* `python2 install.py`

```bash
1.if installed is complite, use command
$cd
2.then run it
$DarkFly
```

**NOTE:**

```bash
if python2 install.py is not allowed or fail, Use this
$chmod +x install.py
$python2 install.py
```

### How to update v4

For update this tool, just do the reinstallation, the first way is to install the Darkfly tools, by reinstalling, the old file will be deleted and replaced with the new one installed.

### Note

The original DarkFly v4 installer was mainly tested on Termux. On regular Linux distributions it may not work correctly.



  █████╗  ███████╗ ████████╗ ██████╗   █████╗ 
 ██╔══██╗ ██╔════╝ ╚══██╔══╝ ██╔══██╗ ██╔══██╗
 ███████║ ███████╗    ██║    ██████╔╝ ███████║
 ██╔══██║ ╚════██║    ██║    ██╔══██╗ ██╔══██║
 ██║  ██║ ███████║    ██║    ██║  ██║ ██║  ██║
 ╚═╝  ╚═╝ ╚══════╝    ╚═╝    ╚═╝  ╚═╝ ╚═╝  ╚═╝


# be carefull using it its not my reposibility if any illgeal thing you 
# offical Astra


