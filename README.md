# Quiz en C 🎯

Un petit jeu de quiz en ligne de commande écrit en C.

## Fonctionnalités
- 25 questions en banque
- 10 questions tirées aléatoirement à chaque partie
- 4 propositions par question
- Score final et appréciation
- Possibilité de rejouer

## Compilation

```bash
gcc quiz_question.c -o quiz_question
./quiz_question

```bash
gcc -Wall -Wextra -O2 -o quiz_question quiz_question.c

./quiz_question       # Linux / macOS
quiz_question.exe     # Windows
