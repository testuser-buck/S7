Schrittketten
 N: Non-stored die Aktion ist solange aktiv wie der Schritt

 R: Reset (Stored) 
 die Aktion wird deaktiviert

 S: Set (Stored) 
 die Aktion wird aktiviert und bleibt bis zu einem Reset aktiv

 L: time Limited 
 die Aktion wird für eine bestimmte Zeit aktiviert, maximal solange der Schritt aktiv ist

 D: time Delayed 
 die Aktion wird nach einer bestimmten Zeit aktiv, sofern der Schritt noch aktiv ist und dann solange der Schritt aktiv ist

 P: Pulse 
 die Aktion wird genau einmal ausgeführt, wenn der Schritt aktiv wird

 SD: Stored and time Delayed 
 die Aktion wird nach einer bestimmten Zeit aktiviert und bleibt bis zu einem Reset aktiv

 DS: Delayed and Stored
 die Aktion wird nach einer bestimmten Zeit aktiviert, sofern der Schritt noch aktiv ist und bleibt bis zu einem Reset aktiv 

 SL: Stored and time Limited
 die Aktion ist für eine bestimmte Zeit aktiviert

 Die Bestimmungszeichen L, D, SD, DS und SL benötigen eine Zeitangabe im TIME-Konstantenformat, z.B. L T#5s.


Eingänge Steuern
 Zielsystem/Variable beobachten und steuern