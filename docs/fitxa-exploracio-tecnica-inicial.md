# Fitxa d'exploracio tecnica inicial

## Microrepte

- Repte: Repte 1
- Microrepte: MP1 - Model client/servidor i eleccio guiada de stack
- Producte inicial: aplicacio web per gestionar microreptes i entregues de DWES.

## Model client/servidor aplicat al producte

El producte sera una aplicacio web. El client sera el navegador de l'usuari, on es mostraran les pantalles, formularis i resultats. El servidor rebra les peticions HTTP, aplicara les regles de negoci, accedira a les dades i retornara una resposta.

En el navegador s'executara:

- HTML i CSS per presentar la informacio.
- JavaScript basic per validar camps senzills o millorar la interaccio.
- Peticions HTTP cap al servidor quan l'usuari consulte, cree o modifique dades.

En el servidor s'executara:

- El codi backend que valida les dades importants.
- La gestio de rutes i controladors.
- L'acces a base de dades.
- La preparacio de respostes HTML o JSON.
- Les comprovacions de permisos quan el producte tinga usuaris autenticats.

## Valor del backend dinamic

Un backend dinamic aporta valor perque permet guardar entregues, consultar l'estat dels microreptes i generar respostes diferents segons l'usuari o les dades disponibles. Una pagina estatica no seria suficient si cal registrar informacio, validar permisos o mantindre un historial de treball.

## Tecnologies identificades

- Client: navegador, HTML, CSS i JavaScript.
- Servidor web: Apache o Nginx en un entorn local o contenidoritzat.
- Runtime de servidor: PHP.
- Backend: PHP amb Laravel com a opcio principal.
- Base de dades probable: MySQL o MariaDB.
- Eines d'entorn: Docker i Composer quan avance el repte.

## Comparacio acotada d'opcions

| Opcio | Avantatges | Limits per a este projecte |
| --- | --- | --- |
| PHP sense framework | Senzill per entendre el cicle peticio-resposta i començar rapid. | Pot acabar desordenat si creixen rutes, validacions i acces a dades. |
| Laravel | Dona estructura clara amb rutes, controladors, vistes, validacio i ORM. Esta alineat amb el recorregut de DWES. | Necessita aprendre convencions i preparar millor l'entorn. |
| Symfony | Framework robust i molt modular. | Pot ser massa extens per a una primera versio menuda. |
| NestJS | Arquitectura moderna sobre Node.js i TypeScript. | S'allunya del stack PHP previst per al curs. |

## Decisio tecnica orientativa

La primera opcio triada es PHP amb Laravel. La decisio es coherent amb el curs i amb un producte que pot necessitar rutes, formularis, validacions, autenticacio i persistencia de dades. Laravel tambe facilita separar responsabilitats entre rutes, controladors, models i vistes.

Per al primer prototip encara no cal implementar el servidor. La decisio nomes fixa una direccio tecnica per als microreptes seguents.

## Alternativa descartada

Es descarta NestJS com a primera opcio. Encara que es una alternativa potent, introdueix TypeScript i un ecosistema diferent. Per al context actual es preferible reforcar PHP i el model backend treballat a DWES.

## Dubtes i limits oberts

- Cal decidir si el primer backend retornara vistes HTML o una API JSON.
- Cal concretar quines entitats tindra el producte: microrepte, entrega, alumne i estat podrien ser candidates.
- Cal comprovar quin entorn Docker es demanara en MP2 abans de fixar versions definitives.

## Verificacio manual

Per revisar esta fitxa cal comprovar que:

- diferencia que s'executa al navegador i que s'executa al servidor;
- aplica el model client/servidor al producte propi;
- identifica navegador, servidor web, runtime, backend i base de dades;
- compara opcions de manera breu;
- tanca una decisio, una alternativa descartada i dubtes pendents.

## Fonts i us d'IA

S'ha usat IA com a suport per estructurar la fitxa i contrastar que els punts de la rubrica quedaven coberts. El contingut final s'ha adaptat al repositori i al context del microrepte.
