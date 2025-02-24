# SYS1000-GRUPPE12

Her skal vi jobbe med vår prosjekt på SYS1000 (evt andre prosjekter)

🛠 Regler for arbeid i repository

For at vi skal jobbe ryddig og unngå feil, la oss følge disse reglene:

1️⃣ Jobb i egne branches
	•	Ikke gjør endringer direkte i main
	•	Før du starter, lag en egen branch, for eksempel:
        
        git checkout -b feature-nav-menu

(hvor feature-nav-menu er navnet på branchen, beskrivende for hva du legger til)

  •	Etter endringer, push til din branch:

        git add .
        git commit -m "La til navigasjonsmeny"
        git push origin feature-nav-menu

2️⃣ Bruk Pull Requests (PR)
	•	Når du er ferdig med en oppgave, ikke merge direkte til main, men opprett en Pull Request (PR)
	•	Jeg eller andre teammedlemmer vil gjennomgå endringene
	•	Etter godkjenning merges PR-en til main

3️⃣ Oppdater koden før du starter arbeid

Før du begynner på noe nytt, sørg for at du har **siste versjon** av prosjektet:

        git checkout main  
        git pull origin main  
        git checkout feature-nav-menu  
        git merge main
 
  Dette hjelper deg med å unngå konflikter.
  
4️⃣ Hold koden ren og forståelig
	•	Legg til kommentarer der det trengs
	•	Gi meningsfulle commit-meldinger, for eksempel:
✅ La til styling for knapper
❌ Update

5️⃣ Hvis noe går galt – ingen panikk
	•	Du kan alltid tilbakestille endringer:

        git reset --hard
        git clean -df

•	Hvis du er usikker på noe, spør i chatten, så hjelper jeg!

Mvh, Nikita
