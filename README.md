# Fast-wall-destroyer

Sziasztok,

Ahogy a nevéből is látszik, a script a barbár és bónusz falvak falának a bontására született, hogy farmolás közben minimalizáljuk a veszteségeinket.

Használata:

farmkezelő
-belépsz a farmkezelőbe, és bepipálod ezt: "Beleértve azokat a jelentéseket, amelyek veszteséggel jártak."
-futtatod a scriptet
-egy lapra teszi az összes farmkezelős oldaladat
-kinyeri belőle a sárga jelentések koordinátáit, illetve a kémjelentésekből azokat a koordinátákat, ahol a falszint > 0
-amint végzett, jelzi és átnavigál a gyülekezőhelyre

gyülekezőhely
-futtatod a scriptet
-beteszi az előre beállított bárdost, kost és kémet, illetve az első koordinátát
-kiküldöd a támadást
-visszakerülsz a gyülekezőhelyre, ismét futtatod a scriptet, beteszi az egységeket, és immár a második koordinátát
-ezt addig kell folytatni, amíg el nem fogynak a koordináták, jelezni fogja, amint a végére ért

Beállítások:
-a bárdos, a kos és a kém darabszámát a következő helyen adhatod meg:

var bardos = "43",
kos = "7",
katapult = "0",
kem = "0";

-alapbeállításként ezek az értékek szerepelnek(-25 szerencse, 3-as fal --> 0-ra, 2 bárdos veszteség)
-más egységet nem lehet beállítani, azokkal farmolni szoktunk és védekezni :p

Jó szórakozást hozzá.
