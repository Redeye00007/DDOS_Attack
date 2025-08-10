# DDOS Attack Tool

---

## Termux Installation & Running

### Step 1: Update & install packages

```bash
pkg update && pkg upgrade
pkg install python git
```

### Step 2: Clone the repository (if available on GitHub)

```bash
git clone https://github.com/Redeye00007/DDOS_Attack
cd DDOS_Attack
```

### Step 3: Run the script

```bash
python Ddos.py
```

### Important Notes for Termux Users

- Grant Termux necessary network permissions on first run.  
- If storage permission is needed, run:  
  ```bash
  termux-setup-storage
  ```  


## Features

- Menu-driven interface  
- Manual IP input for attack  
- Find IP from website URL and attack  
- Simple logo and user-friendly design  
- Stop attack anytime with keyboard interrupt (Ctrl+C)  

---

## Requirements

### 1. Python 3.x  
- Must be installed  
- Check version with:  
  ```bash
  python3 --version
  ```

### 2. Python Standard Modules  
- Uses `socket`, `random`, `sys`, `os`, `time`, `webbrowser`  
- Included by default, no need to install separately

### 3. Linux (Optional)  
- For opening links, `xdg-utils` package should be installed:  
  ```bash
  sudo apt install xdg-utils
  ```

---

## Installation & Running on Linux / macOS / Windows

```bash
# Install Python if not installed
sudo apt update && sudo apt install python3   # Linux

# Run the script
python3 ddos_tool.py
```

---

## Usage

1. Run the program, you will see a menu.  
2. Choose your preferred option:  
   - 1: Start DDOS attack with manual IP input  
   - 2: Find website IP and start DDOS attack  
   - 3: Exit the program  
3. Press **Ctrl + C** during attack to stop.

---

## Warning / Disclaimer

- Use this tool **only for educational purposes**.  
- Unauthorized attacks are illegal and punishable by law.  
- The author is not responsible for any misuse of this tool.  

---

## Author

- Name: Himel Majumder Pronob  
- Facebook: [https://www.facebook.com/share/1BAnvMnchr/](https://www.facebook.com/share/1BAnvMnchr/)  
- GitHub: [https://github.com/redeye00007](https://github.com/redeye00007)  
- Telegram: [https://t.me/redeye7](https://t.me/redeye7)  

---

## License

Free to use for educational purposes only.

