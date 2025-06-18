# Beamu's Volume Meter
A real-time desktop decibel meter with a fun twist — if you get too loud, you'll be visually and audibly punished! 😈  
Built with CustomTkinter, PyAudio, and Pygame.

# 📁 Folder Setup
Make sure the following folders exist in the same directory as your script:
```
volume-meter/
├── Images/     # Put punishment images here (.jpg, .png)
├── Sounds/     # Put punishment sounds here (.mp3)
├── Beamu's VolumeMeter.exe
```
✅ Image Rules:
- Place any .jpg, .png, or .jpeg image files inside the ``Images/`` folder.
- The app will choose one randomly when the threshold is exceeded.

✅ Sound Rules:
- Place any .mp3 sound files inside the Sounds/ folder.
- The app plays one randomly during penalty.

# 🚀 Features
Live dB meter with color-coded visual feedback

Set your own volume threshold

When exceeded:

A random image pops up

A random sound effect plays

Hotkey: ``Ctrl + Shift + Q`` to force-close

# 🎁 Download

Head to the [Release](https://github.com/PreBeamu/Volume-Meter/releases/latest) tab and download the latest ``.zip`` file.  
It includes everything you need:  
✅ Executable  
✅ ``Images/`` folder for penalty popups!  
✅ ``Sounds/`` folder for punishment sound effects!  

Just extract and run!

# ⚠️ Antivirus False Positives

Some antivirus software may falsely flag the `.exe` as malicious. This is a common issue with new programs built using tools like PyInstaller, especially when packaged as a single file.

**Rest assured, there is no malware in this app.**  
You can verify this by uploading the EXE to [VirusTotal](https://www.virustotal.com/)
