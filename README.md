# Dziennik szkolny

Desktopowy dziennik szkolny dla Windows, oparty na Pythonie, CustomTkinter i SQLite.

## Uruchomienie

pobierz cały zip i go rospakuj

Zainstaluj Python 3.10 lub nowszy, a następnie w katalogu projektu uruchom:

```powershell
python -m pip install -r requirements.txt
python main.py
```

Baza `school_diary.db` i tabele zostaną utworzone automatycznie przy pierwszym uruchomieniu. Początkowe konto administratora:

- login: `admin`
- hasło: `admin123`

Po zalogowaniu administrator powinien utworzyć konta użytkowników, klasy, przedmioty, powiązania rodziców z uczniami oraz plan lekcji.

## Utworzenie EXE

```powershell
pyinstaller --onefile --windowed main.py
```

Plik bazy danych jest przechowywany obok uruchomionego programu (w przypadku EXE — obok pliku wykonywalnego).
