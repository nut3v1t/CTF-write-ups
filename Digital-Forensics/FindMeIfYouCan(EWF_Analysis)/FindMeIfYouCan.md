Problem:
-------
A small business operated by a few individuals is located in the UK. In the company’s office, there is a computer placed in a “common” work area, accessible by multiple employees.

BillyBob, CEO
Joe T. Nameless, Employee
Jimmy Wilson, Employee
The Law enforcement authority claims that someone from the company may be involved in the illegal sale of credit cards, driver’s licenses, and green cards. As a digital forensic examiner, you are called to the scene to investigate this shared computer and collect it as evidence for further examination. While inspecting the scene, you also discover an unclaimed USB drive. None of the employees on-site take responsibility for the USB drive. The drive is collected along with the computer for further forensic analysis, as it may contain important evidence related to the case. Your task is to seize the computer in a forensically sound manner, preserving its integrity. Analyze both the computer and USB drive for any evidence related to the alleged illegal activities, including but not limited to: · Emails or messages related to the illegal sales · Files or databases that may contain stolen information · Browser history indicating access to dark web or illegal marketplaces · Financial transactions that might suggest involvement in illicit activities · Any attempts to hide or delete incriminating data Given that multiple employees had access to the computer, your investigation must also focus on user attribution, ensuring that any suspicious activity or data found can be linked to a specific individual. The USB drive, being unclaimed, presents an additional challenge, as its contents and ownership will need to be determined as part of your forensic analysis.

To verify image integrity, find out the SHA-1 hash of the image.

Flag Format: TFC{e65034fdc2bb1b4a12897634435f7dea1cea7829}


Solve:
-----
I used 'ewfinfo' command on the E01 file, nothing else.
command: ewfinfo Lab_Image.E01

Flag : TFC{e46414fdc2bb1a9012896799435f7dea1ce18143}
