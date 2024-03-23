# kn_robocik_rekrutacja
Zadanie rekrutacyjne do koła naukowego PWR Robocik.

Są dwa node'y - board_node i submarine_controller. Pierwszy obsługuje planszę, a drugi to kontroler poruszania sie punkcikiem.

Aktywne są 2 service'y - jeden do startu zapisywania polozen, a drugi do zatrzymania.
Zapisane położenia wyświetlają sie po zakonczeniu board_node.

Są parametry - pierwszy to zabronione pola, ktore domyślnie ustawione są jako granice planszy, drugi to życia, a trzeci to prędkość poruszania.
