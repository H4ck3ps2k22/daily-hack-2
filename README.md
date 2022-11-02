<h2 align = center> <img align="center" src="icons/hacking.png" height="200px" width="200px"/> </h2>
<h1 align="center">
   🚨 &nbsp Instruccions per al 2n DailyHack &nbsp 🚨
</h1>

# ALERTA ⚠️

Us informem que s’ha retrassat la publicació del 2n DailyHack degut a un atac als servidors de l’associació.

Hem estat hackejats a través d’una vulnerabilitat en un dels nostres fitxers, a través de la qual s'ha pogut escalar privilegis i accedir a dades crítiques.

Degut a la importància de localitzar el punt feble, hem decidit que el guanyador del DailyHack serà el primer que aconsegueixi trobar la càrrega útil (shellcode) que s’ha utilitzat per explotar la vulnerabilitat.

# Informació útil 🐒
Alguna informació que hem pogut recolectar desde l'associació és:
  - La màquina hackejada tenia CentOS6 de 32 bits.
  - Hem perdut el codi font del binari que conté la vulnerabilitat, estem intentant fer reverse-engineering per saber com era, però no assegurem res.
  - Algú va deshabilitar les proteccions de la pila que venen per defecte a linux.

# Instruccions per instal·lar la VM desde el sofà de casa teva 🐧

  1) Descarrega la màquina virtual (arxiu .ova) de l'apartat releases del repositori.
  2) Importa l'arxiu .ova a virtualbox
  3) A partir d'aquí, entra com a usuari 'user' i contasenya '123456'
  4) Ara, has de començar a fer reverse-engineering del codi, intentant explotar-lo.
  5) Finalment, quan siguis root, busca a '/' l'arxiu que et dirà les instruccions per tal de donar per finalitzat el repte.

# Links adicionals 🥸
[ShellCode](https://en.m.wikipedia.org/wiki/Shellcode)

[Aleph One](https://en.m.wikipedia.org/wiki/Elias_Levy)

[Buffer Overflow](https://en.m.wikipedia.org/wiki/Buffer_overflow)

[How to create your own shell code](https://www.youtube.com/watch?v=VrJfWWbO0HI?t=1m24s)

[Asciinema](https://asciinema.org)

[Manual of strings](https://man7.org/linux/man-pages/man1/strings.1.html)

[How to solve all your problems of your life](https://youtu.be/oHNKTlz1lps)

# A la uni no m'ensenyen a fer shellcodes 😭
Si teniu qualsevol problema o porteu diversos dies estancats en el mateix error, podeu obrir una issue plorant i analitzarem la vostra petició.
