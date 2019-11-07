# Vaja2-ADC-continous-conversion-STM32F0

# Odgovori na vprašanja
b) Glede na vašo razvojno ploščico in razširitveno vezje z tipkami ter potenciometri, izberite ustrezni analogni vhod. Kateri pin je to? PA0.

e) Glede na potenciometer na vaši ploščici izberite-obkljukajte ustrezni kanal/pin. Na zaslonu se vam mora ustrezno pobarvati izbrani pin v zeleno barvo. Kaj se izpiše poleg pina? ADC_IN10

f) V Clock Configuration spremenimo APB1 peripheral clock (MHz) na 16 MHz. Kaj opazite? Izhodne frekvence se spremenijo na 16MHz.

h)Clock prescaler nastavimo z deliteljem 4. Kolikšna je sedaj preskalirana frekvenca takta fpreskalirana? 4MHz

j) Sampling time (čas vzorčenja tvz_ciklih) spremenite na 239.5 ciklov. Pravi čas vzorčenja se nato poveča še za 12 ciklov. Koliko znaša pravi čas vzorčenja tvz v mikro sekundah? 62,875us

# Komentar

Mikroprocesor izvaja neprekinjene ADC pretvorbe z izbranim potenciometrom. Takšne pretvorbe so primerne za hitro in nenehno branje vhodne vrednosti
