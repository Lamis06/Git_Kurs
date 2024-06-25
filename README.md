# Git_Kurs
my first training at Git
## detailliertere Übersicht der verschiedenen Git-Areas
### Git Areas
1. Working Directory: Hier wird die Dateien bearbeiten. Änderungen in diesem Bereich sind noch nicht in Git aufgenommen.
2. Staging Area (Index): die Änderungen vorbereitet, bevor sie festgeschrieben (commit).
3. Local Repository: hier Commits gespeichert, aber sie sind noch nicht auf das Remote Repository übertragen.
4. Remote Repository: Commits gespeichert und mit anderen geteilt.
### Git-Befehle für das Management dieser Areas
1. Von Working Directory zur Staging Area: "git add <datei>" oder "git add ."
2. Von Staging Area zum Local Repository: "git commit -m "Beschreibung der Änderungen""
3. Vom Local Repository zum Remote Repository: "git push origin main"
4. Vom Remote Repository zum Local Repository: "git fetch origin" oder "git pull origin main"
5. Von Local Repository zum Working Directory: "git checkout <branch>" oder "git merge <branch>"
   
## Basic writing and formatting syntax
[diese Seite erklärt alle Befehle und Formatierung Abkurzung die man braucht ](https://docs.github.com/de/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
## Command Git-Linux
- "cd" (change directory),"cd .." (wechseln in das übergeordente Datei),"cd /d + D:\....."( Wechseln zwischen Laufwerken), "mkdir": Erstellt Verzeichnisse (Ordner), "touch": Erstellt neue leere Dateien,"git clone +link von Github Projekt", "dir",  [Youtube 3](https://www.youtube.com/watch?v=NZ4U9OZdtxk&list=PLDoPjvoNmBAw4eOj58MZPakHjaO3frVMF&index=3)
- "git status", "git add" (to staging) ,"git add *" oder "git add ." (all filse to staging) ,  "git reset" (to unstaging) , git commit -m "Beschreibung der Änderungen", man kann mehrere "git commit" hintereinander schreiben. [Youtube 4](https://www.youtube.com/watch?v=_ahnJcHuBW4&list=PLDoPjvoNmBAw4eOj58MZPakHjaO3frVMF&index=4).
- git branch (main for local, origin for remot also im Git), git push remotename branchname, git remote -v. [Youtube 5](https://www.youtube.com/watch?v=G_NcIuspY4E&list=PLDoPjvoNmBAw4eOj58MZPakHjaO3frVMF&index=5)
- git pull origin, clear ( to clear all im Fenster). [Youtube 6](https://www.youtube.com/watch?v=VP3c8ExvOP0&list=PLDoPjvoNmBAw4eOj58MZPakHjaO3frVMF&index=6)
- not wichtig ! git config --l,  git help config, git config  --global user.email, git config  --global --edit. [Youtube 7](https://www.youtube.com/watch?v=NWnWIpoFVyU&list=PLDoPjvoNmBAw4eOj58MZPakHjaO3frVMF&index=7)
- fork( also  eine Kopie eines Repositorys auf unserem eigenem Konto)
-beim "Commit changes" unterscheidet sich 1- "Commit directly to the main branch":die Änderungen werden sofort in den Haupt-Branch (main) übernommen.
2- "Create a new branch for this commit and start a pull request":erstellt einen neuen Branch mit deinen Änderungen und startet einen Pull Request.Empfohlen bei größen Projekten.
[Youtube 10 Learn Pull Request With Real Examples](https://www.youtube.com/watch?v=n43bagVuJPU&list=PLDoPjvoNmBAw4eOj58MZPakHjaO3frVMF&index=10)

## Linux Befehle 
[Seite zu Linux Befehle](https://www.linuxbefehle.de)
 hier ist eine Probe für die Änderung