# Mntr
Mentoring

Problemy:
1. gruntfile_bez_watch.js si� wykonuje tj. pojawia si� komunikat DONE, ale SASS nie kompiluje si� do CSS-a. Dlaczego?
2. gruntfile.js - to plik po dodaniu watch - zg�asza b��d:
PS C:\Users\Sim1\Dysk Google\PRIV\Kodilla\Git\Mntr> grunt
Loading "Gruntfile.js" tasks...ERROR
>> SyntaxError: Unexpected identifier
Warning: Task "default" not found. Use --force to continue.

Aborted due to warnings.
3. Nie wy��czy�em na poczatku katalogu node_modules ze �ledzenia gitem w .gitignore. 
3a: dopisa�em w taki spos�b w gitignore, czy tak sie dopisuje katalogi?:
.gitignore
/node_modules/
3b. Jak /node_modules/ wycofa� z Gita i ze zdalnego repozytorium?
