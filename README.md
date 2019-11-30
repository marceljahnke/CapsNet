# CapsNet
Capsule network implementation for the laboratory "Neural Networks in Medical Applications" at the Leibniz university hanover (WiSe 19/20)

Capsule Network Implementierung für das Labor "Neuronale Netze für medizinische Anwendungen" an der Leibniz Universität Hannover (WiSe 19/20)

## Voraussetzungen
Um das Jupyter Python Notebook erfolgreich ausführen zu können wird die Version 3.6.1 von Python benötigt. Diese kann in einer virtuellen Umgebung mithilfe von Anaconda3 installiert werden. 

	conda create -n CapsNet python=3.6.1 anaconda

Die Standardpakete können bei Abfrage per Eingabe von ```y``` installiert werden. Im Anschluss muss die virtuelle Umgebung aktiviert werden.

	activate CapsNet

Die weiteren Pakete können über Anaconda oder pip installiert werden. Benötigt werden:

  * keras
  * tensorflow
  * numpy
  * matplotlib (optional für Visualisierung)

Falls noch kein jupyter notebook vorhanden ist muss dies ebenfalls installiert werden. Über Anaconda ist dies leicht über die Startseite möglich.

## Ausführen
Um das Jupyter Notebook zu starten muss mit aktivierter virtueller Umgebung folgender Befehl ausgeführt werden

	jupyter notebook CapsuleNetwork.ipynb
