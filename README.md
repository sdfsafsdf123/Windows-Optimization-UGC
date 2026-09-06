UGC TWEAKS
==========

Optimizator de Windows pentru gaming, facut pentru comunitatea United Gamers.
Gratuit. Fara cont, fara reclame, fara nimic de platit.


INAINTE DE ORICE: AVERTISMENTUL WINDOWS
---------------------------------------
Cand deschizi fisierul, Windows va afisa un ecran albastru care spune
"Windows a protejat computerul" si un buton "Nu executati".

Nu e o eroare si nu inseamna ca fisierul e stricat. Inseamna ca nu am
cumparat un certificat de semnare - costa cateva sute de euro pe an, iar
asta e o aplicatie gratuita pentru un server de FiveM.

Ca sa pornesti: clic pe "Informatii suplimentare", apoi "Executati oricum".

SI ACUM PARTEA IMPORTANTA. Exact acelasi avertisment il primesti si de la
un virus. El nu face diferenta intre "nesemnat si cinstit" si "nesemnat si
periculos" - de aia exista.

Deci verifica DE UNDE ai fisierul:

  * L-ai luat din canalul oficial de pe Discord-ul United Gamers?  -> e in regula
  * Ti l-a trimis cineva in privat, sau l-ai gasit pe alt site?     -> NU-L RULA

Nu ma crede pe cuvant fiindca scrie asta in fisierul pe care tocmai l-ai
descarcat. Un fisier poate spune orice despre el insusi. Sursa conteaza.


CE ITI TREBUIE
--------------
  1. Windows 10 (versiunea 1809 sau mai noua) sau Windows 11, pe 64 de biti.
     Merge pe amandoua. Patru optimizari exista doar pe Windows 11 si apar
     ca "incompatibil" pe 10, fara sa-ti strice scorul.

  2. Atat.

Nu-ti trebuie .NET si nu-ti trebuie nimic instalat inainte. Tot ce foloseste
aplicatia e chiar in fisierul pe care l-ai descarcat - de aia are 66 MB si nu
5. E un troc facut inadins: mai mult de descarcat o data, in loc de un pas
prealabil pe care sa-l rateze cineva si sa creada ca aplicatia e stricata.

Singura exceptie: Microsoft Edge WebView2, care deseneaza interfata. E parte
din Windows 11 si vine cu Edge pe Windows 10, deci practic il ai. Daca totusi
lipseste, aplicatia iti propune sa il instaleze: descarca instalatorul oficial
de la Microsoft, ii verifica semnatura, si abia apoi il porneste. Se intampla
doar daca spui tu "Da".

E un singur fisier. Nu se instaleaza, nu lasa nimic in urma daca il stergi
(in afara de folderul cu backupuri, ca sa poti reveni si dupa).


CUM SE PORNESTE
---------------
Dublu-clic. Windows va cere drepturi de administrator - fara ele nu poate
modifica nicio setare de sistem, deci nu poate face nimic.


CE FACE, PE SCURT
-----------------
Iti arata 89 de optimizari pentru Windows. Pentru fiecare scrie ce face,
DE CE ajuta, si CE PIERZI daca o aplici. Le alegi tu; nimic nu se aplica
singur.

Inainte de fiecare lot creeaza un punct de restaurare Windows si un backup
propriu. Din ele se revine complet sau doar la ce vrei tu.

Butonul rosu "Panic Restore" anuleaza TOT ce a facut aplicatia vreodata.


CE NU FACE
----------
  * Nu are cont, nu are telemetrie, nu verifica actualizari. Nu trimite
    nimic despre calculatorul tau nicaieri.

    Se conecteaza la internet in exact trei situatii, toate pornite de tine:
      - testele de ping, cand apesi butonul;
      - cati jucatori sunt pe server, cat timp esti pe pagina "Panou"
        (intreaba Cfx.re; Cfx.re iti vede IP-ul, la fel ca la intrarea in joc);
      - instalarea WebView2, daca lipseste si accepti.

    In rest, nimic.

  * Nu atinge antivirusul, Windows Defender sau anticheat-urile.

  * Nu iti inventeaza cifre. Nu vei vedea "+47% FPS" nicaieri, pentru ca
    nimeni nu poate masura asta dinainte. Scorul spune cat din ce stie
    aplicatia e aplicat la tine - nu cat de rapid e calculatorul.

  * Nu bifeaza singura nimic marcat "critic". Alea cer confirmare scrisa.


DACA CEVA MERGE PROST
---------------------
Deschide aplicatia si apasa "Panic Restore". Anuleaza tot.

Daca nu mai porneste Windows normal (se poate intampla doar daca ai aplicat
o optimizare marcata "critic"): porneste in Safe Mode - tii Shift apasat
cand dai Restart din meniul Start - si ruleaza fisierul restore.reg din

  %ProgramData%\UGCTweaks\snapshots\<cel mai recent folder>

Pentru orice altceva: Setari -> "Scrie pachet de diagnostic". Iti pune pe
Desktop un .zip cu jurnalele. Uita-te peste el, apoi trimite-l pe Discord.


UNDE CERI AJUTOR
----------------
Discord: dsc.gg/gta5ugc

Spune ce ai aplicat si ce s-a intamplat. Cu pachetul de diagnostic e mult
mai usor de raspuns.
