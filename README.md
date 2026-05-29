# Microrepte DWES

Repositori individual de treball de l'alumne per als microreptes de DWES.

## Objectiu del treball

Este repositori resol de manera inicial el `MP1` del Repte 1: model client/servidor i elecció guiada de stack.

El resultat principal és una fitxa breu d'exploració tècnica inicial on s'explica:

- què fa el client i què fa el servidor en el producte proposat;
- què s'executa al navegador i què s'executa al servidor;
- quin valor aporta un backend dinàmic;
- quines tecnologies de client i servidor s'identifiquen;
- quina primera decisió tècnica es pren i quina alternativa es descarta.

## Com executar-lo

Este microrepte encara no demana una aplicació executable. És una entrega documental.

La fitxa principal està en:

- `docs/fitxa-exploracio-tecnica-inicial.md`

## Com verificar-lo

La verificació és manual. Cal revisar que la fitxa cobreix els punts mínims del microrepte:

- diferenciació entre client i servidor;
- execució al navegador i al servidor;
- identificació de navegador, servidor web, runtime, backend i base de dades;
- comparació acotada de PHP, Laravel, Symfony i NestJS;
- decisió tècnica orientativa, alternativa descartada i dubtes oberts.

## Decisions tècniques

Registra les decisions importants preses durant el microrepte.

- Decisió: usar PHP amb Laravel com a stack orientatiu per als microreptes següents.
- Motiu: és coherent amb DWES i dona estructura per a rutes, controladors, validació, vistes i persistència.
- Alternatives descartades: NestJS com a primera opció, perquè introdueix un ecosistema diferent i s'allunya del recorregut PHP del curs.
- Dubtes pendents: decidir si el primer backend retornarà vistes HTML o API JSON, i concretar l'entorn Docker de MP2.

## Evidències

- `docs/`: documentació del treball i registre d'ús d'IA si correspon.
- `evidence/`: captures textuals, logs, comprovacions o altres evidències.
- `tests/`: proves automàtiques o fitxers relacionats amb la verificació.
- `src/` o `app/`: codi font quan el microrepte ho demane.

## Estat actual

MP1 resolt de manera mínima amb documentació revisable.
