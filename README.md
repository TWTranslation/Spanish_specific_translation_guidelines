# Spanish_specific_translation_guidelines

<img src='https://github.com/alan-turing-institute/the-turing-way/blob/main/book/website/figures/logo/logo.png?raw=true' align="right" height="239" /> 

[Alejandro Coca-Castro](https://github.com/acocac), [Camila Rangel Smith](https://github.com/crangelsmith), Pamela Villar González, Reina Camacho Toro
, [María Nanton](https://github.com/mcnanton)


Some inspiration for these guidelines comes from the collaborative translations of [R4DS](https://github.com/cienciadedatos/documentacion-traduccion-r4ds) by [@cienciadedatos](https://github.com/cienciadedatos), [Teaching Tech Together](https://github.com/gvwilson/teachtogether.tech/blob/master/es/README.md) to Spanish, the [R Contributors translations working group](https://contributor.r-project.org/translations/) and the [R OpenSci translation project](https://translationguide.ropensci.org/).

*switch to Spanish but feel free to enter in contact in English :)* 

## Código de conducta

Este espacio está ligado a [*The Turing Way*](https://the-turing-way.netlify.app/welcome.html) y su [código de conducta](https://the-turing-way.netlify.app/community-handbook/coc.html) 

## Orientaciones para la traducción

### Contexto

A la hora de realizar traducciones se suelen producir algunos errores recurrentes habitualmente por parte de aquellas personas que no están acostumbradas a realizar esa tarea. 
Esta sección incluye una serie de guías de recomendaciones con los errores más frecuentes en la traducción de textos técnicos así como un glosario para lograr mayor uniformidad en las traducciones. 
Se recomienda su uso por todos los traductores que forman parte del esfuerzo de internacionalización al español.
En general, se debe evitar la traducción directa del inglés. 
El traductor debe primero leer y entender lo que va a traducir antes de hacerlo y, en muchos casos, es mejor traducir con las palabras que uno utilizaría, y no necesariamente con las mismas que utilizó el que lo escribió en inglés. 
En programas y aplicaciones se recomienda utilizarlos antes para determinar el uso de los textos en el contexto del programa. 
Por ejemplo, la cadena «save» en un programa podría traducirse por «salvar» si se trata de un juego y es una operación para salvar a un compañero de un peligro o «guardar» (más común) si se trata de guardar los resultados del programa a un archivo. 
Una traducción de calidad es aquella que ofrece al lector el mismo significado que el término original aunque no necesariamente con las mismas palabras o frases.

### Normas

A continuación se listan una serie de normas a tener en cuenta a la hora de realizar las traducciones:

#### Tratamiento al lector

Queremos que The Turing Way se sienta como un documento informal y amigable, por lo que excepto casos contados, ha de tratarse al lector siempre de tú. 
Por ello se traducirá «you» por «tú», no por «usted». 
Esta fórmula se utiliza para dar un trato informal al lector.

#### Género gramatical

Se usará un en lo posible un lenguaje inclusivo. 
Por ejemplo: the users debe traducirse por “los usuarios y las usuarias” o aún  mejor “las personas usuarias”.

#### Mayúsculas y minúsculas

* En español se escribe con mayúsculas sólo la primera letra de los títulos, Our Priorities are Our Users and Free Software debe traducirse por "Nuestras prioridades son nuestros usuarios y el software libre".
* Las mayúsculas deben ir acentuadas (la falsa idea de que no es necesario o es opcional viene del mundo de las máquinas de escribir)
* Los meses y los días de la semana en español se escriben en minúsculas.
* Tampoco se ponen con mayúsculas los nombres de idiomas.
* Ante la duda, se puede consultar en [Fundeu](https://www.fundeu.es/dudas/tipo-de-duda/mayusculas-y-minusculas/) si la palabra va con mayúscula o minúscula.

#### Verbos

* Pasivas: En inglés es muy típico el uso de pasivas. 
En español apenas se usan y deberían sustituirse por un estilo directo o por formas reflexivas o pronominales. 
Se debe evitar su traducción directa.
Por ejemplo, "Many users are being affected" debería traducirse como "Se está afectando a muchos usuarios" y no como "Muchos usuarios están viéndose afectados".
* Muchas palabras terminadas en ing no son gerundios, aunque lo parezcan. "Installing from NFS" es "Instalación desde NFS", no "Instalando desde NFS". 
Lo mismo con Installing from Hard Disk, Installing Base from Floppies o Installing from a DOS partition. 
El gerundio en inglés es un sustantivo (por eso Saving private Ryan es Salvar al soldado Ryan).

#### Otras normas
* Los **pronombres posesivos** en inglés no se tienen necesariamente que traducir por el correspondiente pronombre posesivo en español. 
Se entiende, pero un hispanoparlante no hablaría así, por ejemplo, en lugar de tu sistema para traducir your system debería utilizarse el sistema. 
Sólo se debería poner tu si el propietario del sistema es relevante en este caso. La película de Amenábar Abre los ojos se traduciría al inglés a Open your eyes pero en español no se diría Abre tus ojos.
* Cuidado con palabras que se escriben parecido pero que no significan lo mismo (**falsos amigos**), que no tienen el mismo género, o que habitualmente se traducen a anglicismos que no existen, algunos ejemplos:
  - command: orden, comando no es correcto.
  - actual: real o verdadero, actual no es correcto.
  - free: libre (generalmente, en Debian), y no gratis.
  - font: tipo de letra, fuente no es correcto.
  - library: biblioteca, no librería.
  - normally: habitualmente (generalmente mejor que 'normalmente')
  - to encrypt: cifrar (no encriptar, que es meter en una cripta)
  - to parse: analizar o tratar (no parsear, que no existe)
  - prevent: impedir, no prevenir.
  - the interface: la interfaz (ojo, femenino).
  - by default: por omisión, de forma predeterminada ('defecto' es un 'falso amigo', que aunque ha sido admitido por la RAE, es preferible evitar).
* Comillas tipográficas: En inglés se usa comúnmente "" o '' para entrecomillar citas o cualquier otro tipo de texto. 
En español han de sustituirse por las comillas tipográficas latinas «». 
Si se requieren comillas adicionales dentro de un contexto previamente entrecomillado con comillas latinas, se utilizarán "", y después ''. 
  - Ej: «El cocinero dijo: "¿Cuándo terminaré de freír las 'croquetas'?"». 
  - Ej: If you select "Choose from the list", then ... debería traducirse como: Si usted selecciona «Escoger de la lista», entonces.... Más información en [aquí](https://www.rae.es/dpd/comillas) (RAE)
* Palabras compuestas: 
En inglés se usa comúnmente el guión (-) para componer palabras a partir de otras más simples. 
En español el guión separa más que junta. Palabras como sub-architecture o best-effort han de traducirse de forma que o bien se junten las palabras (subarquitectura), según las normas de estilo del español, o bien se realice una traducción más libre de la palabra, con por ejemplo una expresión (lo mejor posible). 
También es posible separar los términos con un espacio: ex presidente. 
Si se piensa que se puede perder significado al traducir la palabra, puede colocarse después entrecomillada aunque sólo se hará esto si la palabra técnica no queda clara o si el término se utiliza en otros contextos (por ejemplo, programas o etiquetas de control) sin traducir. 
  - Ej: This is done at best-effort podría traducirse por Ello se hace lo mejor posible, The minor-release field podría traducirse por El campo de distribución menor («minor-release», N. del T.).
* Números: se utilizará el punto como separador de miles y la coma como el separador de decimales (al revés que en inglés) que es el formato mayoritario utilizado por los usuarios hispanoparlantes.

#### Términos que no deben traducirse

Los términos que sean intraducibles y deban dejarse en inglés se marcaran como tales. 
Esto significa, habitualmente, que se coloca el término  traducido en español y la traducción entre paréntesis y en cursiva. 
Posteriormente el término se seguirá usando con doble comillas en el texto. Esta se hará por ejemplo: pipeline (tubería), deployment (despliegue). 
No se deberá, sin embargo, abusar de esto y poner(put) cada palabra(word) con un sinónimo(synonymous) entre paréntesis, ya que es francamente(frankly) ridículo(ridiculous).

## Referencias externas

Estos son los recursos que cualquier colaborador con las traducciones de The Turing Way debe conocer. Se recomienda leer primero los más específicos a The Turing Way y luego los más generales, para ir profundizando en los conocimientos y las herramientas.
* [Diccionario de la Real Academia de la Lengua Española](https://dle.rae.es/)
* [Manual de Ortografía de la Real Academia de la Lengua Española (PDF)](https://www.rae.es/sites/default/files/1ortografia_espanola_2010.pdf)

**Glosarios complementarios**

* Como glosario de términos informáticos se deberá utilizar [ORCA](http://es.tldp.org/htmls/orca.html)
* [Glosario del proyecto KDE](http://es.l10n.kde.org/glosario.php) 
* [R Contributors (ver glosarios en Weblate)](https://contributor.r-project.org/translations/)
* [ROpenSci](https://github.com/ropensci-review-tools/glossary)

El proyecto no ha desarrollado su propia guía de estilo, sólo se han enumerado algunas de las normas básicas. Se pueden consultar y utilizar las siguientes guías de estilo:
* Guía de estilo de Insflug.
* Guía de estilo de localización de Programas (traducción al español de la realizada por SoftCatalá), Marzo 2004. [ Nota: No disponible por cambios en los servidores de Hispalinux, esperemos que este arreglado pronto ]
* [Normas de traducción](https://es.l10n.kde.org/normas_generales.php) del grupo de internacionalización de KDE al español.
