# BitCrab a Windows Ransomware

This is Original Repository of the BitCrabRansomware.

BitCrab is a windows ransomware that encrypts all the user files with a basic encryption scheme.

This project is OpenSource, feel free to use, study and/or send pull request.

# Prerequisites
1: Python 3 should me installed in your system.
2: Run the below command to install libraries needed for the Ransomware to run. Make sure while running the command the requirements.txt is present in the same directory where you are running the command from.

<pre>
pip install -r requirements.txt
</pre>

# Before Running

Make sure that all other files are removed excluding( run.txt , file.txt, icon.ico, Ransomware.cpython-310.pyc )

# Not Working No Problem

If the Ransomware is not opening or working make sure that ( key.txt, run.txt, icon.ico ) files are present including the main Ransomware in the same directory

# Disclaimer
This Ransomware mustn't be used to harm/threat/hurt other person's computer.

Its purpose is only to share knowledge and awareness about Malware/Cryptography/Operating Systems/Programming.

BitCrab is a ransomware which is made for learning and awareness about security/cryptography.

Be aware Read all instructions inside the application or else, it may harm your computer.

# What's a Ransomware?

A ransomware is a type of malware that prevents legitimate users from accessing their device or data and asks for a payment in exchange for the stolen functionality. They have been used for mass extortion in various forms, but the most successful one seems to be encrypting ransomware: most of the user data are encrypted and the key can be obtained paying the attacker. To be widely successful a ransomware must fulfill three properties:

Property 1: The hostile binary code must not contain any secret (e.g. deciphering keys). At least not in an easily retrievable form, indeed white box cryptography can be applied to ransomware.

Property 2: Only the author of the attack should be able to decrypt the infected device.

Property 3: Decrypting one device can not provide any useful information for other infected devices, in particular the key must not be shared among them.

# Features
✓ encrypts all user files.

✓ Works even without internet connection.

