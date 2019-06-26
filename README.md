# myE701 - Exam 701: DevOps Tools Engineer ![](https://www.lpice.eu/fileadmin/_processed_/csm_LPIC-DevOpsToolsEngineer_43de3c4735.jpg)  

Beispiel für einen Aufbau einer Dokumention des Lern- und Entwicklungsprozesses mit Ausgesuchten Unterkapiteln aus dem LPI E701 Exam

## Fahrplan
***

| Datum | behandelte Unterrichtsinhalte: | Gewichtung |
| -------- | ------ | -------- |
| 15.05.19 | Installation SW, Einrichten Linux VM(s)<br> [701.3 Source Code Management](https://github.com/w901-fr19-mi/E701#7013-source-code-management)  | 5 |
| 22.05.19 | [701.1 Modern Software Development](https://github.com/w901-fr19-mi/E701#7011-modern-software-development) | 6 |
| 29.05.19 | [702.2 Container Deployment and Orchestration](https://github.com/w901-fr19-mi/E701#7011-modern-software-development) | 5 | 
| 05.06.19 | [704.1 Ansible](https://github.com/w901-fr19-mi/E701#7011-modern-software-development)  | 8 | 
| 12.06.19 | [703.2 Cloud Deployment](https://github.com/w901-fr19-mi/E701#7011-modern-software-development) | 2 |
| 19.06.19 | [702.3 Container Infrastructure](https://github.com/w901-fr19-mi/E701#7011-modern-software-development) | 4 |
| 26.06.19 | LB1 Theoretische Prüfung und Abschluss LB2 | - |
| 03.07.19 | Lehrerkonevent | - |
| 10.07.19 | Sommersporttage | - |
|          | Total Punkte | 30

Kapitel aus E701 wurden in der Gruppe mit .... erarbeitet. Davon sind mindestens 14 Punkte selbständig erarbeitet worden. 

# Dokumention des Lern- und Entwicklungsprozesses

## 701.3 Source Code Management (Status: In Arbeit)

**Weight**: 5

**Beschreibung und Ziel** 
Candidates should be able to use Git to manage and share source code. This includes creating and contributing to a repository as well as the usage of tags, branches and remote repositories. Furthermore, the candidate should be able to merge files and resolve merging conflicts.

Key Knowledge Areas: 
* Understand Git concepts and repository structure
* Manage files within a Git repository
* Manage branches and tags
* Work with remote repositories and branches as well as submodules
* Merge files and branches
* Awareness of SVN and CVS, including concepts of centralized and distributed SCM solutions

The following is a partial list of the used files, terms and utilities:
* git
* .gitignore

**Beispiele und Arbeitsergebnisse** <br>
Das Resultat kann man beim Schluss dieses Moduls erkennen, da ich laufend mit git arbeiten werde. Folgende Theorie Punkte werde ich genauer anschauen:

Remote Repos

Branches <br>
Wenn man vom einer Hauptversion etwas testen will, kann man ein Branch machen. Das heisst es wird eine Kopie zusagen erstellt, bei dem man alles bearbeiten kann ohne dabei das Original zu verändern.

Tags <br>
Tags werden benutzt um wichtige Punkte zu markieren (z.B. die Version eines Files). Es wird dabei unter zwei Typen unterschieden: lightweight und unnotated.<br>
Um die von git verfügbaren tag aufzulisten, kann man folgenden Befehl eingeben:

    git tag


File Branch/Merge <br>
Wenn man ein Dokument oder Code auf Git bearbeiten möchte, aber dabei die Hauptdatei nicht überschreiben will macht man ein Branch (man nennt das Forken). Somit hat man wie eine Kopie vom Originalen und kann da soviel testen wie man will. <br>
Wenn man nun den Branch mit dem Hauptfile (master) vereinen will, heisst dies ein Merge machen.

<img src="https://nvie.com/img/main-branches@2x.png" alt="branch" width="300"/>



SVN und CVS <br>


Zentrale und verteilte SCM Lösungen <br>


**Fazit und Aussicht** <br>
Im M300 haben wir schon etwas mit git gearbeitet, doch jetzt konnte ich das ganze Thema mehr vertieft anschauen und besser verstehen.

<br>


## Kapitel: 701.1 Modern Software Development (Status: In Arbeit)

**Weight**: 6

**Beschreibung und Ziel** 
 Candidates should be able to design software solutions suitable for modern runtime environments. Candidates should understand how services handle data persistence, sessions, status information, transactions, concurrency, security, performance, availability, scaling, load balancing, messaging, monitoring and APIs. Furthermore, candidates should understand the implications of agile and DevOps on software development.

Key Knowledge Areas:
* Understand and design service based applications
* Understand common API concepts and standards <br>
   <span style="color:blue">
   ser
* Understand aspects of data storage, service status and session handling
* Design software to be run in containers
* Design software to be deployed to cloud services
* Awareness of risks in the migration and integration of monolithic legacy software
* Understand common application security risks and ways to mitigate them
* Understand the concept of agile software development
* Understand the concept of DevOps and its implications to software developers and operators

The following is a partial list of the used files, terms and utilities:
* REST, JSON
* Service Orientated Architectures (SOA)
* Microservices
* Immutable servers
* Loose coupling
* Cross site scripting, SQL injections, verbose error reports, API authentication, consistent enforcement of transport encryption
* CORS headers and CSRF tokens
* ACID properties and CAP theorem

**Unterlagen**

[![](https://img.youtube.com/vi/PH4HtZ8naWs/0.jpg)](https://www.youtube.com/watch?v=PH4HtZ8naWs)

Microservices YouTube Einführung

---


**Beispiele und Arbeitsergebnisse**


**Fazit und Aussicht**, z.B. Die Durcharbeitung von ... gab mir ein besseres Verständnis über die Funktionsweise von Containern.

<br>

## Kapitel: 702.2 Container Deployment and Orchestration (Status: In Arbeit)

**Weight**: 5

**Beschreibung und Ziel**  
* Understand the architecture and application model Kubernetes
* Define and manage a container-based application for Kubernetes, including the definition of Deployments, Services, ReplicaSets and Pods

 
**Vorgehen** 

<br>

**Beispiele und Arbeitsergebnisse**
| Linux          | Container      | Beschreibung      |
| -------------- | -------------- | ----------------- |
|    |   | 

**Fazit und Aussicht**, z.B. Die Durcharbeitung von ... gab mir ein besseres Verständnis über die Funktionsweise von Containern.

<br>

## Kapitel: 704.1 Ansible (Status: In Arbeit)

**Weight**: 8

**Beschreibung und Ziel** 
Key Knowledge Areas:
* Understand the principles of automated system configuration and software installation
* Create and maintain inventory files
* Understand how Ansible interacts with remote systems
* Manage SSH login credentials for Ansible, including using unprivileged login accounts
* Create, maintain and run Ansible playbooks, including tasks, handlers, conditionals, loops and registers
* Set and use variables
* Maintain secrets using Ansible vaults
* Write Jinja2 templates, including using common filters, loops and conditionals
* Understand and use Ansible roles and install Ansible roles from Ansible Galaxy
* Understand and use important Ansible tasks, including file, copy, template, ini_file, lineinfile, patch, replace, user, group, command, shell, service, systemd, cron, apt, debconf, yum, git, and debug
* Awareness of dynamic inventory
* Awareness of Ansibles features for non-Linux systems
* Awareness of Ansible containers

The following is a partial list of the used files, terms and utilities:
* ansible.cfg
* ansible-playbook
* ansible-vault
* ansible-galaxy
* ansible-doc
  

**Vorgehen** 

<br>

**Beispiele und Arbeitsergebnisse**
| Linux          | Container      | Beschreibung      |
| -------------- | -------------- | ----------------- |
|    |   | 

**Fazit und Aussicht**, z.B. Die Durcharbeitung von ... gab mir ein besseres Verständnis über die Funktionsweise von Containern.

<br>

## Kapitel: 703.2 Cloud Deployment (Status: In Arbeit)

**Weight**: 2

**Beschreibung und Ziel**  

**Vorgehen** 

<br>

**Beispiele und Arbeitsergebnisse**
| Linux          | Container      | Beschreibung      |
| -------------- | -------------- | ----------------- |
|    |   | 

**Fazit und Aussicht**, z.B. Die Durcharbeitung von ... gab mir ein besseres Verständnis über die Funktionsweise von Containern.

<br>

## Kapitel: 702.3 Container Infrastructure (Status: In Arbeit)

**Weight**: 4

**Beschreibung**
* Flocker und flannel kennen
* Service discovery Konzept verstehen
* Grundwissen von CoreOS Container Linux, rkt und etcd
* Sicherheitsrisiken von container Virtualisierung  und images verstehen und wie man sie migriert
  
<br>

**Beispiele und Arbeitsergebnisse**

| Linux          | Container      | Beschreibung      |
| -------------- | -------------- | ----------------- |
|    |   | 

**Fazit und Aussicht**, z.B. Die Durcharbeitung von ... gab mir ein besseres Verständnis über die Funktionsweise von Containern.


## Links

* [Exam 701: DevOps Tools Engineer](https://www.lpi.org/our-certifications/exam-701-objectives) 
* [E701 Dokumentation](https://github.com/w901-fr19-mi/E701)
* [myE701 Original Repository](https://github.com/w901-fr19-mi/myE701) 

**Weitere nützliche Programme**

* [Windows SSH Client, putty](https://putty.org)
* [Grafischer Windows SFTP Client, Bitvise SSH Client](https://www.bitvise.com/ssh-client-download)
* [Visual Studio Code](https://code.visualstudio.com/)
