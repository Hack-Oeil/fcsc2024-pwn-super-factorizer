# FCSC 2024 Super Factorizer

Je trouve qu’ils font un peu trop les malins les gens qui font de la crypto. Moi aussi je peux factoriser des nombres !

**Note :** la commande pour lancer le binaire côté serveur est : *timeout -k 121 120 stdbuf -o0 /app/super-factorizer.*



Fichiers :
- [factor.sh](factor.sh)
- [ld-2.36.so](ld-2.36.so)
- [libc-2.36.so](libc-2.36.so)
- [super-factorizer](super-factorizer)
- [super-factorizer.c](super-factorizer.c)



Auteur : XeR

Origine : [Super Factorizer](https://hackropole.fr/fr/challenges/pwn/fcsc2024-pwn-super-factorizer/)


-----------

## Connectez vous en WEBSSH
> http://localhost

#### tentez 
> nc fifty-shades-of-white.cyrhades.fr 4000

-----------

## Ou directement avec netcat
> nc localhost 4000

-----------


## Installation manuel
Vous n'utilisez pas l'application **les CTFs de Cyrhades** ? C'est dommage !
Mais voici comment installer ce CTF manuellement :

> git clone https://github.com/Hack-Oeil/fcsc2024-pwn-super-factorizer.git

> cd fcsc2024-pwn-super-factorizer


-----------

## Sur le site officiel hackropole.fr
> https://hackropole.fr/fr/challenges/pwn/fcsc2024-pwn-super-factorizer/