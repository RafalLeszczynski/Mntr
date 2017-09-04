# Mntr
Mentoring

Problemy:
1. gruntfile_bez_watch.js się wykonuje tj. pojawia się komunikat DONE, ale SASS nie kompiluje się do CSS-a. Dlaczego?
2. gruntfile.js - to plik po dodaniu watch - zgłasza błąd:
PS C:\Users\Sim1\Dysk Google\PRIV\Kodilla\Git\Mntr> grunt
Loading "Gruntfile.js" tasks...ERROR
>> SyntaxError: Unexpected identifier
Warning: Task "default" not found. Use --force to continue.

Aborted due to warnings.

3. Nie wyłączyłem na poczatku katalogu node_modules ze śledzenia gitem w .gitignore. 

3a: dopisałem w taki sposób w gitignore, czy tak sie dopisuje katalogi?:
.gitignore
/node_modules/

3b. Jak /node_modules/ wycofać z Gita i ze zdalnego repozytorium?
