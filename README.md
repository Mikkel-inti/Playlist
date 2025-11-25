# Playlist
Dette C-program er lavet i forbindelse med kursus: **62712- Basic C-programmeing**, der har målet om at importere en playliste fra **playlist.txt** med 5 sange, der har indholdet:
```
1 Bad Guy – Billie Eilish
2 Bohemian Rhapsody – Queen 
3 Billie Jean – Michael Jackson
4 Rolling in the Deep – Adele 
5 Smells Like Teen Spirit – Nirvana
```
ændre den, og udskrive en ny playliste, **playlist-out.txt**, med indholdet:

```
Bad Guy – Billie Eilish 
Bohemian Rhapsody - Queen
Billie Jean – Michael Jackson 
Tarkan – Şımarık 
Rolling in the Deep – Adele
```

## Programflow
Programmet læser tekstlinjer fra en fil og gemmer det i en singly linked list.
Derudover, sletter den et element i listen (***Smells Like Teen Spirit - Nirvana***), og indsætter et nyt element (***Tarkan – Şımarık***) ved en given position som her er hardcoded til 4. Slutteligt, bliver den nye playliste outputtet.

# Filer
- `playlist.txt`: **Selve playlisten**
- `playlist-out.txt`: **Ny playliste** (genereres efter programkørsel) 
- `main.c`: **Samlet kørsel**
- `singly_linked_list.c/h`: funktioner givet af kurset.

## How to use eksempel:

1. I Vscodium byg og kør programmet eller tryk på `f5`
2. Når programmet er kørt vil du i terminalen kunne se de importerede sange fra `playlist.txt`:
   <img width="611" height="212" alt="image" src="https://github.com/user-attachments/assets/0d9975d6-6081-4213-ab7c-44c357d61db5" />
3. Derudover vil den nye playliste `playlist-out.txt`
<img width="324" height="104" alt="image" src="https://github.com/user-attachments/assets/fd8b2391-17c5-4a0b-8436-83df0b31a33b" />
<img width="480" height="233" alt="image" src="https://github.com/user-attachments/assets/cc0981fa-435d-4f87-8626-3336c7393936" />

