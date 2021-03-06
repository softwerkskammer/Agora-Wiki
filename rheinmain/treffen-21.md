[< index](/wiki/rheinmain/index)

Treffen #21 der Softwerkskammer Rhein-Main
=====================================

Heute verwenden wir das Lean-Coffee-Format.
Folgende Themen wurden abgestimmt:

Docker
----------
https://www.docker.io/
Leichtgewichtige Applikations-Container auf Linux-Basis
Benjamin zeigt am Beispiel eines Postgres-Servers, wie man Docker-Container einsetzt.
[Public Docker Images](https://github.com/dotcloud/docker/wiki/Public-docker-images)
[How is Docker.io different from a normal Virtual Machine?](http://stackoverflow.com/questions/16047306/how-is-docker-io-different-from-a-normal-virtual-machine)

IaaS or not?
---------------
Was sind die Vor- und Nachteile.

- Virtualisierung selbst zu machen ist sehr aufwändig und erfordert eigenes Know-How (Personal)
- IaaS-Provider hosten nicht immer in Deutschland
- Von vorne herein muss in man sich um die Automatisierung der Infrastruktur kümmern, was eigentlich ein Vorteil ist (Verteile Systeme, die robust sind).
- Nicht immer ist eine API vorhanden
- DevOps müssen dann auch den Betrieb auf IaaS lernen
- Provider-Wechsel ist nicht mehr so einfach möglich, wenn Features von IaaS voll eingesetzt werden 
- Preiskalkulation ist schwierig
- Hat viele Zusatzleistungen, wie z.B. globale Locations, Big-Data-Services die man selbst kaum aufsetzen könnte …

http://blippex.github.io/updates/2013/09/23/why-we-moved-away-from-aws.html

Retros für kleine Teams
--------------------------------
Problem: Kleines Team (3-4 Personen), Interaktion ist nicht immer eindeutig.

- Idee: Retrospektiven-Fragen "an die Wand schreiben", so dass keine bestimmte Person diese Frage stellt
- Hilfreicher Lesestoff: http://www.mccarthyshow.com/wp-content/uploads/2011/02/DieCoreProtokolleV3.pdf

Allgemeines zu Retrospektiven:

- http://www.plans-for-retrospectives.com/
- http://finding-marbles.com/retr-o-mat/what-is-a-retrospective/
- http://borisgloger.com/2012/09/13/moral-hat-in-der-retrospektive-nichts-verloren/
- http://jitterted.com/blog/2013/02/11/another-alternative-to-the-retrospective-prime-directive/