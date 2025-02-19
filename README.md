# ZavrsniRad
Ova simulacija predstavlja robotski sustav za paletizaciju koristeći YouBot mobilni robotski manipulator. Simulacija je napisana za CoppeliaSim. Cilj simulacije je automatizirati proces preuzimanja i postavljanja kutija na odgovarajuće palete koristeći YouBot robot. YouBot je mobilni robot s 5-osnom robotskom rukom i gripperom, koji može premještati objekte između različitih lokacija.
## Tok simulacije
### 1. Inicijalizacija:

Robot se postavlja na početnu poziciju.

Definiraju se početne konfiguracije zglobova robotske ruke za preuzimanje i postavljanje kutija.

### 2. Preuzimanje kutija:

Robot se pomiče do platforme za preuzimanje (Pickup).

Gripper otvara, robotska ruka se spušta, zatvara gripper i preuzima kutiju.

Kutija se zatim podiže i postavlja u pripremljeni položaj na robotskoj ruci.

### 3. Postavljanje kutija na palete:

Robot se pomiče do odgovarajuće palete (gf1 ili gf2).

Robotska ruka postavlja kutiju na određeno mjesto na paleti.

Gripper otpušta kutiju, a robot se vraća u neutralni položaj.

### 4. Ponavljanje procesa:

Proces se ponavlja za svaku kutiju (block1, block2, block3, block4, block5).

Svaka kutija ima svoju ciljnu poziciju na paleti.

### 5. Završetak simulacije:

Nakon što su sve kutije postavljene, simulacija se zaustavlja.

## Izvedba simulacije

1. Preuzeti datoteku paletizacijaNOVO.ttt
2. Otvoriti datoteku u CoppeliaSim, ukoliko nemate CoppeliaSim preuzeti sa https://www.coppeliarobotics.com/
3. Pokrenuti datoteku
4. Pritisnuti Play za izvedbu simulacije
