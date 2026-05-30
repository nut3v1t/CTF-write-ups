Problem:
-------
He was recently seen near a museum. What was the name of the museum?(Case Insensitive)
Flag Format: TFC{The National Museum}

Solve:
-----
This was an interesting problem. I thought that since it was a tourist place, I have to find something associated with map. So I used recursive grep command:

$ grep -ri museum temp_dir/
grep: temp_dir/data/data/com.google.android.apps.maps/databases/gmm_storage.db: binary file matches

It caught my attention and I used strings and grep command on that db file:

$ strings gmm_storage.db | grep -i -A 5 -B 5 museum 
The room was very clean, and was even cleaned and the waters were replenished the day of our departure (which is not done in the US). Very spacious and comfortable seating and bed.p
$HOTELS_TIPS_TOPICS_NEARBY_ACTIVITIES
Nearby activities*$Say more about the nearby actz
ivities2
Nearby activitiesB,0ahUKEwinp6np5beBAxXGT6QEHXo-AAYQ3IcHCNsBKAoZU
SThe Egyptian Museum is just a minute away from the hotel if you exit from the back.p
.... (more data)

There I got the name Egyptian Museum.

Flag: TFC{The Egyptian Museum}



