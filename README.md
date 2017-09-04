# Mntr
Mentoring

Problemy:
1. gruntfile_bez_watch.js siê wykonuje tj. pojawia siê komunikat DONE, ale SASS nie kompiluje siê do CSS-a. Dlaczego?
2. gruntfile.js - to plik po dodaniu watch - zg³asza b³¹d:
PS C:\Users\Sim1\Dysk Google\PRIV\Kodilla\Git\Mntr> grunt
Loading "Gruntfile.js" tasks...ERROR
>> SyntaxError: Unexpected identifier
Warning: Task "default" not found. Use --force to continue.

Aborted due to warnings.
3. Nie wy³¹czy³em na poczatku katalogu node_modules ze œledzenia gitem w .gitignore. 
3a: dopisa³em w taki sposób w gitignore, czy tak sie dopisuje katalogi?:
.gitignore
/node_modules/
3b. Jak /node_modules/ wycofaæ z Gita i ze zdalnego repozytorium?
