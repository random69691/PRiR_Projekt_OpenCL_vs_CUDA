# Temat: Porównanie wydajności implementacji algorytmu obliczania wyznacznika macierzy metodą rozkładu LU, w środowisku CUDA oraz OpenCL

Projekt z przedmiotu Programowanie Równoległe i Rozproszone.

# TODO
- [ ] Stworzyć implementację CUDA
- [ ] Stworzyć implementację OpenCL
- [ ] Stworzyć skrypt do generowania wykresów
- [ ] Napisać dokumentacje (10 stron Latex)
- [ ] Opisać metodę rozkładu LU
- [ ] Opisać programowanie w środowiskach CUDA i OpenCL



---
# Info
+ Testujemy obie implementacje na tej samej maszynie (karcie)
+ Możemy przetestować np na dwóch sprzętach, żeby coś w tej dokumentacji było xD (Paweł chyba ma Nvidię z CUDA)

# Instrukcja używania repo
1. Robimy fork na tym repozytorium u góry po prawej opcja Fork.
2. Włączamy terminal, wpisujemy
> git clone **adres z zielonego przycisku Clone or download (dla własnego repozytorium github)** stworzy się nowy katalog o nazwie: **"PRiR_Projekt_OpenCL_vs_CUDA"**
2. Gdy cos zmienimy, np dodamy nowy plik wpisujemy
> git add . (dodaje do STASH'a pliki które pójdą w następnym commicie)
3. Komitujemy zmiany do swojego lokalnego! sklonowanego repozytorium:
> git commit -m "Tresć commita."
4. Wysyłamy zmiany na serwer github:
> git push (potem wpisujemy swoj login i haslo z githuba)
5. Robimy pull request przy nowym comicie z poziomu konta github.com
6. Gotowe! Smacznego!
