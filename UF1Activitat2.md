# Activitat 2 - Pràctica amb llenguatges

### Grup: Javier Mouriño y Byron Cobos



#### Per al llenguatge compilat:

- Utilitzant la línia de comandes, sense utilitzar un IDE de desenvolupament escriureu el programa en un fitxer de text que sigui el codi font, el codi font l’adjunteu dins el document. 

```

#include <iostream>
#include <cstdlib>
#include "time.h"

int Droll()
{
    int outcome;
    int l_limit = 1;  // floor or lower limit of a die
    int h_limit = 6; //ceiling or higher limit of a die

    outcome = rand() % (h_limit - l_limit + 1) + l_limit;

    return outcome;
}

int main()
{
    srand(time(0));
    for(int i=0;i<1;i++)
    {
        std::cout << Droll() << std::endl;
    }
}

```
![image](https://user-images.githubusercontent.com/113586156/195358732-f27ef4e6-0062-45dc-aeab-ae851906e2b6.png)

- Identifiqueu el compilador real que utilitzeu (nom de l’executable) i la comanda per utilitzar-lo per passar de codi font a codi objecte. 

Instalará el compilador GCC altres eines de desenvolupament.
“La GNU Compiler Collection és un conjunt de recopiladors de llenguatges de programació creat pel Projecte GNU. Així doncs, és programari lliure distribuït per la Free Software Foundation sota la llicència GNU General Public License”


- Descriviu com passar de codi font a codi objecte. 
- 
- Mostreu les extensions dels fitxers de codi font i codi objecte. 

- Descriviu com passar de codi objecte a executable. 

- Expliqueu els avantatges d’utilitzar un llenguatge compilat i els punts febles. 

-Busqueu 3 IDEs de desenvolupament pel llenguatge.

#### Per al llenguatge interpretat:

- Utilitzant la línia de comandes, sense utilitzar un IDE de desenvolupament escriureu el programa en un fitxer de text que sigui el codi font, el codi font l’adjunteu dins el document.

- Identifiqueu l'intèrpret del llenguatge (l’executable). 

- Descriviu com funciona l’intèrpret. 

- Mostreu les extensions dels fitxers de codi font. 

- Expliqueu els avantatges d’utilitzar un llenguatge interpretat i els punts febles. 

- Busqueu 3 IDEs de desenvolupament pel llenguatge. 




#### Per al llenguatge de MV: 
- Utilitzant la línia de comandes, sense utilitzar un IDE de desenvolupament escriureu el programa en un fitxer de text que sigui el codi font, el codi font l’adjunteu dins el document. 

- Identifiqueu el compilador real (nom d’executable) que utilitzeu i la comanda per utilitzar-lo per passar de codi font a ByteCode. 

- Descriviu com passar de codi font a ByteCode. 

- Mostreu les extensions dels fitxers de codi font i ByteCode. 

- Descriviu com executar el programa. 

- Expliqueu els avantatges d’utilitzar un llenguatge de MV i els punts febles. 

- Busqueu 3 IDEs de desenvolupament pel llenguatge. 

