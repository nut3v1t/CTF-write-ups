Problem:
-------
Who is the owner of the phone number +20 117 999 3432?(Case Insensitive)
Flag Format: TFC{Jackson}

Solve:
-----
As it is a problem related to contact, I simply searched for "contact" in explorer and found "contact2.db" file. I opened the .db file using online database viewer. There, I extracted the raw_contact_id from 'phone_lookup' table using the contact number, and used the raw_contact_id in 'data' table to find the name.
Flag : TFC{Eyad}
