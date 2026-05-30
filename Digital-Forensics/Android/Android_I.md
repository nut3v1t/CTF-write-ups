Problem:
-------
The FBI recently confiscated a mobile device and extracted its files. You are a member of the Digital Forensics team. Your task is to efficiently extract information from the files because you have limited time. [Go to readme for file link]
What is the ICCID of the SIM card used in the device?(No space)
Flag Format: TFC{digits}

Solve:
------
I tried to assume names to search in explorer, which are relevant with "SIM" OF "Cellular Network". The file named 'telephony.db' stored the iccid info. But I couldn't assume it intially because it was "telephony", not "telephone". Anyway, I opened the .db file using online db viewer and found the iccid number. 

For command line approach, sqlite3 command can be used, however, the search is text based, no UI.

Flag : TFC{89014103211118510720}

Purpose of ICCID : The ICCID (Integrated Circuit Card Identifier) is a unique 19 to 22-digit serial number assigned to every SIM card at the time of manufacture. It serves as the SIM's primary serial number and is used by mobile network operators to authenticate SIM cards, link them to subscriber accounts, and manage connectivity across networks. The ICCID is essential for various applications, including IoT deployments and device provisioning, as it remains constant throughout the SIM's lifecycle, unlike a phone number, which can change when switching carriers.
