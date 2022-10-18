# Where is Waldo finder
Dies ist unser Programm um den gestreiften Mann zu finden. 
Es basiert auf dem yolov5 Code von ultralyticss:
https://github.com/ultralytics/yolov5


# Training

Wir haben bereits eine Version trainiert mit einem etwas kleineren Datensatz bereits trainiert (WaldoFinderv4.pt)

Unserer Optimierter Datensatz braucht noch Training!

zum trainieren einfach

`train.py`

Wir haben den Code so modifiziert, dass dieser aus unseren Erfahrungen bessere Ergebnisse liefert bei wenigeren Epochen.


## Testen
zum Testen einfach

`test.py`
bzw. 
`test.py --weights runs\train\exp\weights\best.py`
bei dem neu trainieren.


## Troubleshooting
alle zip Dateien direkt entpacken, das heißt, am Ende sollte noch der Ordner test übrig bleiben etc.

wenn python fehlende libraries nicht findet, einfach
`pip install -r requirements.txt` 
ausführen
> Written with [StackEdit](https://stackedit.io/).
