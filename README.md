# pyACR1252U
Windows Tool to Read/Write/Manipulate GoToTags NFC ACR1252U NTAG213/NTAG216 NXP MIFARE Ultralight Tags

**[Check Release Section](https://github.com/AppliedEllipsis/pyACR1252U/releases)** for Exe/Binary release you can use without an Python Environment and includes dependencies.

**[How to setup your environment](how%20to%20setup%20your%20environment.md)** 

**It currently performs:**
* Reads and Writes 4 character pins to NFC.
* QT Gui App that sits in the Windows Tray Icon
* When it reads, it types the characters into whatever window has focus, followed by an enter.
* It's currently only compatible with Python 2, but I am in the process of making it 2/3 compatible.

# If you get an error in file .../PyQt5/uic/port_v2/load_plugin.py in line 38
# replace:
#     except Exception, e:
# with:
#     except Exception as e: