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
Programmet læser tekstlinjer fra en fil og gemmer i en singly linked list.
Derudover, sletter den et element i listen (***Smells Like Teen Spirit - Nirvana***), og indsætter et nyt element (***Tarkan – Şımarık***) ved en given position som her er hardcoded til 4. Slutteligt, bliver den nye playliste outputtet.

# Filer
- `playlist.txt`: **Selve playlisten**
- `playlist-out.txt`: **Ny playliste** (genereres efter programkørsel) 
- `main.c`: **Samlet kørsel**
- `singly_linked_list.c/h`: funktioner givet af kurset.



