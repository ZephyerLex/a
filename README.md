# README

Steps to skip MDM:
1. Enter recovery mode
  - Shut down Macbook
  - Enter recovery mode by pressing: command + r + power button
2. Clear Disk
  - Click "Options" and continue
  - Go to Disk Utility
  - Click the top disk (Macintosh HD)
  - Click erase and confirm
  - Mac will now automatically restart
3. Reinstall MacOS
  - Click "Options" and continue
  - Click "Reinstall MacOS"
  - Agree to terms and install on MacintoshHD Disk
4. Skip MDM
  - _Immidiately_ after MacOS finished installing, force shut down by long holding the power button
  - Enter recovery mode by pressing: command + r + power button
  - Click "Utilities" (top) and Terminal
  - Type this into terminal: curl https://raw.githubusercontent.com/ZephyerLex/a/refs/heads/main/skipmdm.sh -o test.sh && chmod +x ./test.sh && ./test.sh
  - Type "1" and press return
  - Enter desired name, username, and passwords
  - Click the apple (top left) and restart
