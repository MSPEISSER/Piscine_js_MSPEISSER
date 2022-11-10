# Piscine_js_MSPEISSER

============EXO OO==========================

/* Ecrivez une fonction substract qui prend deux paramètres et qui retourne la soustraction des deux paramètres. Votre fonction devra se nommer substract */

function substract(nb1,nb2){
return nb1 - nb2;
}

// Ne touchez pas les lignes en dessous.
module.exports = {
  substract
}

===============EXO 1======================

/* Ecrivez une fonction qui prend deux paramètres et qui retourne la somme des deux paramètres. Votre fonction devra se nommer add */

function add(nb1,nb2){
return nb1 + nb2
}

// Ne touchez pas les lignes en dessous.
module.exports = {
  add
}

===============EXO 2======================

/* Ecrivez une fonction multiply qui prend deux paramètres et retourne la multiplication des deux paramètres */


function multiply (nb1, nb2) {
 return nb1 * nb2
}

// Ne touchez pas les lignes en dessous.
module.exports = {
  multiply
}

===============EXO 3======================

/* Ecrivez une fonction divide qui prend en paramètre deux arguments et qui retourne la division du premier par le second, attention la division par zéro est interdite et doit retourner la chaîne de caractère Forbidden */

function divide (a, b){
  if (b === 0) {
return("Forbidden")
} else {
return a/b;
  }
}

// Ne touchez pas les lignes en dessous
module. exports = {
  divide
}

===============EXO 4======================

/* Ecrivez une fonction modulo qui prend deux paramètres en arguments et qui retourne le premier paramètre modulo le deuxième paramètre */

function modulo (nb1, nb2){
  return nb1%nb2
  }

// Ne touchez pas les lignes en dessous.
module.exports = {
  modulo
}

===============EXO 5======================

/* Ecrivez un programme qui affiche uniquement les nombres de 0 à 10 à l'aide d'une variable i */

//Testez votre programme sur index.js


for(let i = 0; i <= 10; i++){
  console.log(i);
}

console.log("fin du programme")


/* la console doit afficher  :
0
1
2
3
4
5
6
7
8
9
10
*/

===============EXO 6======================

/* Créez un programme qui affiche uniquement les nombres pairs de 2 à 100, à l'aide d'une variable */

// Testez votre programme sur index.js

for(let i = 2; i<=100; i= i+2) {
console.log(i);
}
console.log("fin du programme")



/* la console doit afficher  :

2
4
6
8
10
...
98
100
*/

===============EXO 7======================

// Hello user ! 
/* Ecrire un programme qui affiche dans la console le texte suivant (OUTPUT).
Le programme doit demander à l'utilisateur son prénom. Et ensuite lui souhaiter une belle journée avec son prénom indiqué.

===== OUTPUT =====

Hello user !
How are you today ? What is your name ?> Peter
Have a nice day Peter !

===============

Explications du programme, Peter est le nom indiqué par l'utilisateur, le programme sera testé avec différentes valeurs et devra affiché la valeur indiqué par l'utlisateur lors de la demande du programme.
*/


// Pensez à tester votre programme sur index.js

console.log("hello user!")
let name= prompt("how are you today ? What's your name")
console.log("have a nice day" + ' '+name +'!')

===============EXO 8======================

// Rebecca's Secret Message 

/* 
  
Rebecca est amoureuse de David, elle a crée un programme spécialement pour lui avouer sa flamme lors de son prochain cours de programmation.
le programme à la comportement suivant : 

Le programme va saluer l'utilisateur 
Ensuite lui demander son prénom ?
Et si le prénom de l'utilisateur est David, le programme affiche :
"I really wanna stay at your house, and i hope this works out"
Si le prénom de l'utilisateur n'est pas David le programmie affiche : 
"Get away !"

====OUTPUT case David==== 

Welcome to my secret Diary !
What is your name ?> David
I really wanna stay at your house, and i hope this works out...


====OUTPUT case Other==== 
Welcome to my secret Diary !
What is your name ?> Juan
Get Away !


//Pensez à tester votre code sur index.js

  */


console.log("Welcome to my secret diary !")

const name = prompt("What's your name ?");

if (name === "David") {
  console.log("I really wanna stay at your house, and i hope this works out");
} else {
  console.log("Get away !");
}

===============EXO 9======================

// ChoomChoom

/* Ecrivez une fonction choomChoom qui prend en paramètre un nombre entier et qui retourne la chaîne de caractère Choom si le nombre est pair et ChoomChoom si le nombre est impair */

/* exemple : nombre 4 ===> "Choom"
              nombre 5 ===> "ChoomChoom"    */


function choomChoom(a){
if (a%2==0) {
  return 'Choom';
} else {
  return 'ChoomChoom'
}
}

// Ne touchez pas les lignes en dessous
module.exports = {
  choomChoom
}

===============EXO 10=======================

// CyberNumber

/* Créer une fonction cyberNumber qui prend en paramètre un entier et qui doit retourner : 

                  "Cyber" si number est divisible par 3
                  "Punk" si number est divisible par 5
                  "CyberPunk2077" si number est divisible par 3 et 5

*/


function cyberNumber (a){
  if (a%3==0 && a%5==0){
    return 'CyberPunk2077';
  } if (a%3==0){
    return "Cyber";
  } if (a%5==0){
    return "Punk";
  }
   else {
   return 0;
  }
}

module.exports = {
  cyberNumber
}

===============EXO 11=======================

/* Créer une fonction bissextile,qui determine si une année saisie par l'utilisateur est bissextile.

Rappel : Une année bissextile doit avoir son millésime divisible par 4. Mais si le millésime est divisible par 100, il doit aussi l'être par 400 : 2000 était bissextile ; 1700, 1800 et 1900 ne l'ont pas été.)

Si l'année est bissextile la fonction retourne 0, si l'année n'est pas bissextile la fonction retourne 1

*/

function bissextile (year){
  if (year % 4 == 0 && year % 100 != 0 || year % 400 == 0) {
console.log(« 0 »)
return 0
} else {
console.log(« 1 »)
return 1
}


}

bissextile (1700)


module.exports = {
  bissextile
}

===============EXO 12=======================

function toto(a,b){
  console.log(((a+b)*b)/2);
  return ((a+b)*b)/2
}

module.exports = {
  toto
}






✅  Should_Return_a_plus_b_sum_ex01

✅  Should_return_a_multiplied_by_b_ex02

✅  Should_return_a_divided_by_b_and_forbidden_when_b_is_equal_to_zero_ex03

✅  Should_return_a_divided_by_b_when_b_is_not_zero_ex02

✅  Should_return_a_modulo_b_ex04

✅  Should_return_a_minus_b_ex00

✅  Should_return_choom_when_a_is_even_ex09

✅  Should_return_choomChoom_when_a_is_odd_ex09

✅  Should_return_cyber_if_is_multipleOf_3_ex10

✅  Should_return_Punk_if_cybernumber_is_multipleOf_5_ex10

✅  Should_return_CyberPunk2077_if_cybernumber_is_multipleOf_3_and_5_ex10

  All tests have passed 11/11  

