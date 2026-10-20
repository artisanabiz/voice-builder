# Voice Builder — ghid de utilizare

Versiunea 0.1.0

Voice Builder te ajută să creezi un skill Writer reutilizabil dintr-o voce existentă. Citește mostrele autorizate, pune întrebări sub formă de quiz, încearcă un text real și transformă alegerile confirmate în instrucțiuni pentru Writer.

Poți porni de la propria scriere sau de la o voce de referință etichetată separat. Crearea unei persoane fictive de la zero nu face parte din fluxul principal al acestei versiuni.

## Condiții de utilizare

Utilizarea și modificarea privată sunt gratuite, inclusiv pentru activități comerciale și servicii plătite pentru clienți. Redistribuirea sau revânzarea Builder-ului, inclusiv a versiunilor modificate, necesită permisiune scrisă separată. Poți trimite altor persoane linkul distribuției originale.

Writer-ele personalizate și textele create cu Builder-ul sunt excluse de la această restricție, în limitele drepturilor și permisiunilor aplicabile lor. Poți livra clientului un Writer creat pentru el; permisiunea de a lucra pentru clienți nu include livrarea Builder-ului însuși.

Termenii compleți sunt în [Voice Builder Free Use License](LICENSE.txt), în limba engleză. Acesta este un rezumat în română. Este o licență proprie, nu o licență open source.

## Cum începi

1. Deschide un chat nou într-un serviciu AI care poate citi fișiere Markdown și atașamente sau dosare locale.
2. Atașează pachetul sau pune la dispoziția asistentului folderul extras `voice-builder`. Păstrează `SKILL.md` împreună cu folderul `references`. Unele medii cer extragerea ZIP-ului sau instalarea prin mecanismul lor propriu. Atașarea nu înseamnă automat instalare.
3. Trimite cererea:

   > Citește SKILL.md din Voice Builder și folosește referințele lui când sunt necesare. Vreau să creez un Writer reutilizabil dintr-o voce existentă. Ghidează-mă de la început până la export. Nu instala și nu publica nimic.

4. Asistentul va clarifica ce vrei să scrii, limba și sursa vocii, folosind răspunsurile deja oferite. Apoi îți va cere mostre potrivite.
5. Aprobi sau ajustezi propunerea de voce, verifici un draft util și confirmi instrucțiunile și destinația Writer-ului.

Dacă asistentul nu poate citi pachetul sau o referință, trebuie să spună acest lucru. Accesul la instrucțiuni este necesar pentru a aplica efectiv skill-ul.

În mediile care descoperă skill-uri instalate, urmează metoda documentată de mediul respectiv pentru un folder care conține `SKILL.md`. Builder-ul și Writer-ul creat sunt skill-uri separate. Acest pachet nu le instalează automat.

## Cum funcționează quiz-ul

Vei primi câte o întrebare utilă, cu alegeri concrete și posibilitatea de a scrie alt răspuns. Dacă mediul oferă selectoare interactive, asistentul le poate folosi. În celelalte medii, alegerile sunt numerotate. Skill-ul nu poate adăuga singur butoane unei aplicații.

Nu este impus un număr minim de mostre. Cu puțin material, propunerea va avea limite mai mari. Un text fluent poate să nu semene încă cu vocea dorită; feedbackul pe un pasaj concret ajută la ajustare.

O formulare recurentă, inclusiv o semnătură de final, va fi propusă ca alegere. Nu există o expresie sau un stil personal prestabilit în Builder.

## Ce primești

Un Writer cu instrucțiunile de voce acceptate și un exemplu de folosire. Acesta trebuie să funcționeze fără conversația cu Builder-ul. Încearcă-l într-un chat nou, pe alt subiect, înainte să te bazezi pe el.

Dacă asistentul poate crea fișiere, trebuie să livreze efectiv Writer-ul. Dacă nu poate, trebuie să ofere conținutul complet și să precizeze că nu l-a salvat sau instalat.

Pachetul Builder conține doar instrucțiuni generale, metadate de interfață și documentație. Nu conține mostre personale, un Writer deja completat, profiluri personale, transcrieri, rezultate de test, chei de acces, scripturi executabile sau cod de urmărire.

## Confidențialitate

Un fișier local citit printr-un asistent AI cloud este procesat de serviciul AI respectiv. Elimină informațiile confidențiale din mostre și verifică setările și politicile serviciului ales. Acest pachet de instrucțiuni nu controlează retenția datelor, folosirea lor pentru antrenare, accesul la cont sau copiile de siguranță ale platformei.

Fluxul cere folosirea materialelor autorizate, evitarea salvării automate a corpusului brut și aprobarea înainte de stocarea sau exportarea fragmentelor exacte. Un profil de voce sau o formulare distinctivă poate identifica o persoană. Verifică Writer-ul înainte să-l distribui, chiar dacă mostrele originale nu sunt incluse.

Folosește materiale pe care ai dreptul să le furnizezi. Aprobarea analizei nu înseamnă automat aprobare pentru publicare ori transmitere către alt serviciu. Condițiile de distribuire a Builder-ului nu acordă drepturi asupra mostrelor tale sau Writer-ului creat; acestea rămân supuse propriilor drepturi și condițiilor aplicabile ale furnizorului AI.

## Limite

Voice Builder este un pachet de instrucțiuni conversaționale. Nu este un model local, un sistem de antrenare sau un serviciu de publicare automată. Navigarea web, crearea fișierelor, selectoarele și instalarea depind de mediul AI ales.

Nu este validat pentru toate limbile, formatele sau modelele. Evaluează separat fluența, asemănarea vocii, exactitatea informațiilor și respectarea unghiului cerut. Validarea tehnică nu dovedește calitatea scrierii. Nu este promisă reproducerea perfectă a unui autor ori evitarea detectării textului AI.

Nu sunt necesare Python, un compiler, acces la inbox sau conectarea conturilor sociale. Documentarea factuală este opțională și necesită instrumente potrivite. Publicarea, instalarea și transmiterea materialelor private sunt acțiuni distincte, care cer autorizare.
