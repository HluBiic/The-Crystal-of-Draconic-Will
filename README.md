## 3. The Crystal of Draconic Will
- inšpirácia hrou *Rogue 1980* (DOBROVSKÝ P. *50 Let Videoher*, s. 46-51)
- singleplayer, RPG
#### Gameplay
- cieľom hry je prejsť cez dungeon plný nepriateľov ale aj pokladov a získať kryštál oživenia drakov
- na mape sa môžu objaviť rôzne elixíry ktoré budú hráčovi poskytovať rôzne buffy (heal, vyšší armor, vyšší damage, ...) ako aj poklady ktoré môžu obsahovať lepšie zbrane, kľúče k dverám alebo magické zvitky, ktorým si vie uplatniť niektorý z buffov alebo spawnúť nepriateľa
- nepriatelia budú navádzaný na hráča hneď po jeho príchode do danej miestnosti (ich rýchlosť a sila útoku bude záležať na hodnotách EDA) ... tvar nepriateľov zatiaľ nemám konkrétne upresnený (buď kostlivci alebo nejaké magické zvieratko alebo niečo podobného)
- v pravej časti obrazovky sa bude nachádzať jednoduchá verzia inventáru s tlačidlami EQUIP a INFO
	- EQUIP - označí daný predmet ako equipnutý tzn pomocou E ho bude možné použiť. aktuálne equipnutý predmet sa bude zobrazovať aj v políčku nad inventárom vpravo hore (možný scenár: napríklad dvere sú uzamknuté a otvoria sa až po equipnutí kľúča a jeho použití pomocou E na dverách)
	- INFO - vypíše malé info a možno nápovedu k danému predmetu
- v spodnej časti obrazovky sa bude nachádzať textové info o priebehu hry ako napríklad "You found a key!", "You hit the enemy and dealt 24 damage." "Enemy hit you dealing 30 damage.", "You drank the magic potion and gained +30 armor!"
- klasické ovládanie pomocou WASD / šípky, predmety sa budú brať automaticky keď nimi hráč prejde a budú sa ukladať do inventára na pravej časti obrazovky, tlačidlo akcie (použitie equipnutého predmetu, otvorenie dverí) bude pomocou E

### 🐉 **The Crystal of Draconic Will (Rogue-like)**
- Use **turn-based movement**, where player moves one step each time they achieve a calm state.    
- EDA controls exploration rate:    
    - High calm = more frequent movement/actions        
    - Stress = cooldown period before next move.        
- Item interactions auto-trigger when nearby (remove need for E key).
