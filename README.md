# UE02 Shooting Island 

### Projektbeschreibung: 
Es wurde ein 2D Game gemacht in dem es das Ziel ist 10 Targets (in meinem Falle fallende Kometen) mit einem Schusswaffe zu zerstören. Wenn der Counter 10 erreicht hat hat man gewonnen, lässt man allerdings einen Kometen aus, startet das Minispiel wieder von vorne.

### Entwicklungsplattform: 
Windows 10, Unity 2020.3.18f1, Visual Studio Version 2019 Community

### Zielplattform: 
WebGL Referenzauflösung (960x600) 
https://3ahmns2122mtin.github.io/10CSchrofner-UE02-shootingisland/

### Visuelle Einblicke in das Projekt: 
(https://github.com/3ahmns2122mtin/10CSchrofner-UE02-shootingisland/files/7324754/Beschreibung1.pdf)
[(https://user-images.githubusercontent.com/91070191/144301997-013c5b55-386f-4c00-9f61-cffe41479c0c.png)
(https://user-images.githubusercontent.com/91070191/144302434-07f1efab-1491-4e49-80b4-12e8ea9d2ddd.jpg)



### Drittmaterial: 
Font: https://assetstore.unity.com/packages/2d/fonts/pixel-font-tripfive-64734
Hintergrundbild (Bearbeitet): https://www.google.com/url?sa=i&url=https%3A%2F%2Fwallpaperaccess.com%2Fstar-minimal&psig=AOvVaw2xER0RNKHDRzPrmjHkNmTJ&ust=1638473231016000&source=images&cd=vfe&ved=0CAsQjRxqFwoTCOifzMqqw_QCFQAAAAAdAAAAABAD
Hintergrundmusik: https://www.youtube.com/watch?v=Tp_0oMPGBZs&t=9s
Win-Musik: https://www.youtube.com/watch?v=rTl4p5FHBMI&t=205s
Asteroid (Target) (Bearbeitet): https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.pinterest.com%2Fpin%2F571746115171758720%2F&psig=AOvVaw1WZ4X64p1ALngzSJ15NglV&ust=1638473450409000&source=images&cd=vfe&ved=0CAsQjRxqFwoTCNDv87Krw_QCFQAAAAAdAAAAABAL
Level Restart Sound: https://www.youtube.com/watch?v=jg19BE0H0ic

### Anforderungsliste:  
- [x] WebGL export/upload lauffähig/spielbar
- [x] 2D Untiyprojekt Version 2020.3.18f1 LTS öffnen
- [x] In Assets Folder MyGame anlegen.
- [x] Den Ordner Scenes in Assets > MyGame ziehen
- [x] Die Szene SampleScene im Ornder Scenes umbenennen in ShootingScene
- [x] Ein Canvas GameObject anlegen.
- [x] Das Canvas auf screenindependent einstellen: Komponente Canvas --> Render Mode --> Screen Space - Camera, 
das GameObject Main Camera per Drag & Drop auf Render Camera ziehen in der Komponente Canvas.
- [x] In der Komponente Canvas Scaler unter UI Scale Mode --> Scale with Screen Size einstellen und als Reference Resolution 960x600 einstellen.
- [x] In Asstets > MyGame den Folder Sprites anlegen. 
- [x] Ein Hintergrund Sprite reinladen.
- [x] In der Hierarchy dem Canvas GameObject ein Kind GameObject vom Typ Image hinzufügen und in Background umbenennen.
- [x] Das Image ggf. positionieren und größentechnisch anpassen.
- [x] Dem Canvas Eltern GameObject ein empty GameObject (Create Empty) hinzufügen. 
- [x] Auf dem Empty GameObject ein Reset auführen (Komponente Rect Transform --> Menü = 3 vertikale Punkte öffnen --> obester Eintrag. 
- [x] Das empty GameObject umbenennen in ParentTargets.
- [x] in Assets > MyGame > Prefabs Folder anlegen.
- [x] Sprite Target in der Hierarchy als Kind GameObject von ParentTargets ziehen und umbenennen in Target.
- [x] Das GameObject per Drag and Drop in den Prefabs Ornder ziehen. Sollte dann blau erscheinen. 
- [x] Ändern des Mauszeigers: 1) auf Sprite clicken und im Inspector Texture Type Cursor setzen. Wichtig ist am Ende Apply (unten rechts) zu bestätigen, sonst werden die 
- [x] Änderungen nicht übernommen. 2) Unter BuildSettings > PlayerSettings per Drag and Drop das Cursorsprite in Default Cursor ziehen. 
- [x] In Assets > MyGame einen neuen Ordner anlegen Scripts
- [x] In Scripts ein neues C# Script anlegen: Rechtsklick > Create > C# Script. Script gleich umbenennen in Target. Mit Doppelklick öffnen in Visual Studio (https://github.com/HTL-SBG/FAQIssuesUnityVSGitGitHub/issues/2).
- [x] Anhängen des Scripts Target als Komponente an das GameObject Target (per Drag and Drop). 
- [x] Einen 2D Collider als Komponente dem Target hinzufügen. 
- [x] Dem Script Target eine Methode OnMouseDown() hinzufügen. 
- [x] In der OnMouseDown() Methodendeklaration, die Methodenaufruf Destroy(gameObject); hinzufügen
- [x] Das GO Target in der Hierarchy auswählen und mit Apply All die Änderungen bestätigen. 
- [x] In der Szene ein empty GameObject anlegen, umbenennen in GameManager und Reset ausführen. 
- [x] Im Scripts Ordner ein neues C# Script erstellen mit dem Namen GameManager.
- [x] Das GameManager Script per Drag and Drop dem GameObject GameManager hinzufügen.
- [x] WebGL Build machen in docs Ordner von dem Projektstand 25.11 
- [x] docs Ordner auf GitHub laden
- [x] Eine funktionale Änderung einbauen (zusätzliches Audio, hit Bad Targets --> Decrement by 1, etc.) 
- [x] WebGL Build machen in docs Ordner 
- [x] docs Ordner auf GitHub laden
- [x] Readme aktualisieren
- [x] Projekt etwas aufhüpschen


Copyright by CSchrofner :)
