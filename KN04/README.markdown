# KN04

## A

## Objekte in S3-Bucket

<img src="./images/objektins3.png">

## Bild im Web

<img src="./images/ziegeaufbergimweb.png">

## [Cloud-Init für Web-Instanz](./cloud-init-web.yaml)

<img src="./images/imagephp.png">

## C

<img src="./images/allevolumen.png">

## D

|                          | Typ  | Persistenz |
| ------------------------ | ---- | ---------- |
| EBS Root                 | hot  | nein       |
| EBS Zusätzliches Volumen | hot  | ja         |
| S3                       | warm | ja         |


Erklärung: ESB Root ist als "hot" eingestuft, weil das Betriebssystem dort liegt und es kontinuierlich genutzt wird. Das zusätzliche EBS-Volumen wird als "warm" betrachtet, da es Daten enthält, die nicht archiviert werden, aber auch nicht ständig verwendet werden. Bei S3 kann man es als "warm" oder "cold" bezeichnen, da Daten dort archiviert, aber auch verwendet werden können.