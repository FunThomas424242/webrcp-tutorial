# WebRCP Tutorial

WebRCP Tutorial ist der Versuch das  Tutorial des Original [WebRCP Projektes](http://sourceforge.net/projects/webrcp/), gehostet auf Sourceforge.net, wieder zum Laufen zu bekommen.

Hintergrund: 
Die letzte Aktivität im Originalprojekt auf Sourceforge.net  stammt aus dem Jahre 2013. Seit dem gab es einige Änderungen im Java und Eclipse Umfeld wodurch das 
Projekt wenn überhaupt nur noch eingeschränkt genutzt werden kann.  
Diese Problematik erkannte offenbar bereits das Projekt [w11k/webrcp](https://github.com/w11k/webrcp) auf Github und nahm entsprechende Anpassungen vor. 

Bedauerlicherweise wurde im Rahmen des w11k/webrcp Projektes das ursprüngliche Tutorial nicht mit auf den neuen Technologiestack portiert. 
Das wird mit diesem Projekt hier versucht. 

Da im w11k/webrcp Projekt keine Lizenz angegeben ist wird hier die ursprüngliche Lizenz (EPL) des Projektes von Sourceforge.net angenommen. 
Es sei an dieser Stelle darauf hingewiesen, dass die verwendeten Quellen zum Webstart Mechanismus  alle dem Projekt w11k/webrcp auf Github 
entnommen wurden und nur die Bibliotheken zum Tutorial selbst von sourceforge verwendet wurden. 

Rechtlich stellen die Quellen hier also einen Mix aus den Projekten webrcp auf sourceforge und w11k/webrcp auf  Github dar. Das ist aber kein Problem
da generell bei allen 3 Projekten von der Anwendung der EPL Lizenz auszugehen ist. 

*Aktueller Projekt Status:*
* Build und Deployment auf einen lokalen Tomcat funktioniert mittels puppet.
* Das Tutorial lässt sich unter http://localhost:8080/webrcp-tutorial aufrufen
* Nack Klick auf den Link werden alle benötigten Archive aufs lokale Filesystem geladen (teilweise sind für Debugging Zwecke Popups eingebaut - die bestätigt werden müssen)
* Der eclipse Starter org.eclipse.core.launcher.Main wird mit den originalen Parametern aufgerufen.
* *Der Starter startet nicht korrekt.*

Das Original Projekt stammt von  http://sourceforge.net/projects/webrcp/

