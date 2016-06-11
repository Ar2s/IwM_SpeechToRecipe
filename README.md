###Projekt na zaliczenie przedmiotu "Informatyka w medycynie" 2015/2016 PUT.

#####Wymagania:

Aby używać wszystkich funkcjonalności, najlepiej mieć:

* Python 2.6, 2.7, or 3.3+ (wymagane)
* PyAudio 0.2.9+ (wymagane, tylko jeżeli będzie używany mikrofon)
* SpeechRecognition 3.4.6 (wymagane,najłatwiej zainstalować przy pomocy ``pip install SpeechRecognition``.)
* OpenCV 2.4.12(wymagane, jeżeli zapisujemy recepte)

#####Pliki:
* speech-main.py - słucha do 4 zaleceń podanych z mikrofonu i zapisuje receptę do pliku "recepta_gotowa.jpg"
* speech-mikrofon.py - służy do testowania odpowiedzi z google API przy użyciu mikrofonu
* speech-recepta-z-pliku.py - tworzy automatycznie "recepta_gotowa.jpg" z plików 01_test.wav do 04_test.wav

#####Przykładowe uruchomienie:
* python speech_main.py
