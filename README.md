# ec2_get_iplayer

An das BBC Archiv von ausserhalb UK herankommen über Amazon EC2.
Ein Konto bei der Amazon Cloud EC2 anlegen. Neubenutzer haben ein freies Kontingent
Den Standort Europe-London auswählen
Einen SSH-Key erzeugen oder importieren. Public Key hochladen, Private Key in den lokalen SSH Client (z.B. Putty)
Eine Security-Group erzeugen, welches nur Port 22 (SSH) durchlässt
Nun eine virtuelle Maschine erzeugen. Größe nano reicht. Das Standard Amazon Image nehmen.
Mittels ssh auf den User ec2-user einloggen.
wget blabla
chmod +x blabla
./blabla

Aus und wieder einloggen.
Nun mit get_iplayer [URL von BBC Film] 
den gewünschten Film herunterladen
Über WinSCP oder was auch immer den Kram auf den lokalen Rechner schieben.
Nach getaner Arbeit direkt die Amazon EC2 Maschine direkt terminieren (zerstören). Frisst sonst unnötig Geld.
