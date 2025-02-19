# Projekt-Seminar Deep Learing (Prof. Dr. Jörn Hees) #
## Gruppe: Simon Lausch, Jan Felix Fuchs, Paul Jansen und Tobias Pappen ##
## Thema: Deep Reinforcement Learning (Atari Spiel Freeway) ##

### Zur Einteilung der Gruppe: ###
Die vierer Gruppe aus den oben genannten Personen wurde in die folgenden zwei Teilgruppen aufgeteilt:
  1. Tobias Pappen
  2. Simon Lausch, Jan Felix Fuchs und Paul Jansen <br>

Beide Gruppen verfolgten unterschiedliche Ansätze des Deep Reinforcement Learning, um das Atari Spiel Freeway möglichst erfolgreich von einer künstlichen Intelligenz spielen zu lassen. Tobias Pappen ging in Einzelarbeit dem model-based Ansatz ME-TRPO nach. Alle weiteren Informationen zu der Arbeit von Tobias Pappen finden sich in einem zusätzlichen, extra dafür angelegten GitHub Repository. Dieses Repository enthält ausschließlich die Ergebnisse der Dreiergruppe, welche sich mit dem model-free Ansatz Deep Q-Learning beschäftigte. Aus Gründen der Berwertbarkeit, teilte sich die Gruppe ca. nach der Hälfte des Semesters auf die einzelne Personen auf, um dann in Einzelarbeit unterschiedlichen Ansätzen nachzugehen. Folglich bestehen die in diesem Repository hinterlegten Ergebnisse aus zwei Bestandteilen:
1. Die gemeinsame Gruppenarbeit, welche dazu diente ein ersten DQN zu implementieren und eine Baseline für spätere Vergleiche zu finden.
2. Die drei Einzelarbeiten, in deren Rahmen unterschiedlichen Ansätzen im Zusammenhang mit Deep Q-Learning nachgegangen wurde.

Nähere Informationen zum Vorgehen und den individuellen Ansätzen der Gruppenmitglieder finden sich in den jeweiligen Notebooks.

### Zum Aufbau des Repositories: ###
Wie bereits zuvor erwähnt, enthält dieses GitHub Repository ausschließlich die Ergebnisse der Dreiergruppe bestehend aus Simon Lausch, Jan Felix Fuchs und Paul Jansen.
Das Repository enthält die folgenden Dateien bzw. Verzeichnisse:
- ***Notebooks:***
Dieses Verzeichnis enthält die drei Notebooks der Gruppenmitglieder. In jedem Notebook sind die Ergebnisse der Einzelarbeiten festgehalten. Darüberhinaus wurden die Ergebnisse der Gruppenarbeit gebündelt im Notebook von Jan Felix Fuchs festgehalten. Der Übergang von der Gruppen- zur Einzelarbeit ist dabei an der entsprechenden Stelle gekennzeichnet.
- ***Trained Models DQN:***
Dieses Verzeichnis enthält die trainierten Models, die im Rahmen der Gruppenarbeit (Implementierung eines DQN) entstanden sind.
- ***Diagram DQN:***
Dieses Verzeichnis enthält die Graphen, die während des Trainings des DQN enstanden sind
- ***Trained Models CNN Jan Felix:***
Dieses Verzeichnis enthält die trainierten Models, die im Rahmen der Einzelarbeit von Jan Felix Fuchs entstanden sind
- ***Trained models_cropped RAM_Simon:***
Dieses Verzeichnis enthält die trainierten Models, die im Rahmen der Einzelarbeit von Simon Lausch entstanden sind
- ***Diagram CNN Jan Felix:***
Dieses Verzeichnis enthält die Graphen, die während der Einzelarbeit von Jan Felix Fuchs entstanden sind
- ***Diagram CNN Paul:***
Dieses Verzeichnis enthält die Graphen, die während der Einzelarbeit von Paul Jansen entstanden sind
- ***Diagram DQN Cropped Ram Simon:***
Dieses Verzeichnis enthält die Diagramme, die während der Einzelarbeit von Simon Lausch entstanden sind
- ***Finale Präsentation***
Diese Datei enthält die Powerpoint Präsentation, die für die finale Vorstellung der  im Rahmen des Deep Learning Kurses erarbeiteten Deep Reinforcement Learning Strategien verwendet wurde

### Zur Einrichtung der Arbeitsumgebung: ###
Zur Einrichtung unserer Arbeitsumgebung haben wir die Python Distribution Anaconda verwendet.
Über diese haben wir die Module installiert (hier direkt mit dem jeweiligen Befehl):
- pip install gym[atari]
- pip install ale_py
- pip install autorom[accept-rom-license]
- pip install torch
- conda install pytorch-cuda = 11.6
