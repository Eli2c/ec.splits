# ec.splits
![ec splits-banner (1)](https://github.com/user-attachments/assets/bb9b3e99-8a83-47a8-a442-3cb63685c463)

w tym repozytorium znajdują się wszystkie pliki potrzebne do zbudowania klawiatur od ec.splits.

legenda nazw plików 3D:

nazwa_wersja(opcjonalne oznaczenie _lp oznacza low profile)_B-bottom lub T-top_L-left lub R-right

np. s1_v1_lp_BR
Poradnik korzystania z klawiatur:


1. Dokonywanie zmian w programie VIAL(klawiatury przewodowe):

Z programu Vial można kożystać w przeglądarce(https://vial.rocks/) lub przez pobranie aplikacji(https://get.vial.today/download/).
Program Vial umożliwia dokonywanie zmian rozłożenia przycisków w klawiaturach przewodowych z obsługą VIA/Vial(wszystkie klawiatury przewodowe od ec.splits obsługują program Vial)
<img width="2559" height="1390" alt="image" src="https://github.com/user-attachments/assets/a1b60c02-9f77-47f8-b5d5-64122e0a08c8" />

Aby dokonać zmiany należy nacisnąć na przycisk którego funkcję chce się zmienic a następnie wybrać tą funkcję poprzez kliknięcie na nią w klawiatruę w dolnej części ekranu
Program Vial może też wprowadzić klawiaturę w tryb bootloader poprzez przejście do zakłądki "security" a następnie kliknięcie przycisku "reboot to bootloader"

Więcej informacji: https://get.vial.today/

2. Dokonywanie zmian w programie ZMK-STUDIO(klawiatury bezprzewodowe):

Aby dokonać zmianę rozłożenia klawiatury w programie ZMK-STUDIO należy udać się na stronę internetową(https://zmk.studio/) lub pobrać aplikację(https://zmk.studio/download)
Program ZMK-STUDIO umożliwia dokonywanie zmian rozłożenia przycisków w wszystkich bezprzewodowych klawiaturach od ec.splits
<img width="2559" height="1392" alt="image" src="https://github.com/user-attachments/assets/8df4707a-aa54-48d0-86a8-1c95c39a7790" />


Aby dokonać zmiany w programie ZMK-STUDIO należy klawiaturę odblokować, aby to zrobić należy nacisnąć te przyciski(dla klawiatór s1 i s2):
![Screenshot_2026-02-03-17-14-23-14_e5d3893ac03954c6bb675ef2555b879b](https://github.com/user-attachments/assets/377162d4-1f21-45e6-86ef-234b47298d7b)
dla większości klawiatur odpowiednie będą przyciski oznaczone na zielono, oznaczenie czerwone jest dla starszych egzemplarzy.

Dokonywanie zmian w programie ZMK-STUDIO działa na takiej samej zasadzie jak w programie Vial(kliknięcie na dany przycisk i wybór) ale należy wyszukać daną funkcję.
W programie ZMK-STUDIO także można wprowadzić klawiaturę w tryb bootloader, robi się to przez przypisanie funkcji "bootloader" do dowolnego przycisku.

3. Tryb bootloader/ wgrywanie oprogramowania

tryb bootloader oznacza tryb w którym kontroler(y) klawiatury wchodzą w tryb wgrywania oprogramowania. Są wtedy widoczne jako dyski zewnętrzne. Aby wgrać nowe oprogramowanie wystarczy przeciągnąć je na ten dysk.

