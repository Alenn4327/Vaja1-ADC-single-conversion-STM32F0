# Vaja1-ADC-single-conversion-STM32F0
<h4>Glede na vašo razvojno ploščo in razširitveno vezje z tipkami in potencimetri, izberite ustrezni analogni vhod. Kateri pin je to?</h4>
<p>Pin PC0.</p>

<h4>V pinout zavihku ugotovite, koliko ADC pretvornikov ima vaša razvojna plošča?</h4
<p>1 pretvornik.</p>

<h4>Izbran ADC pretvornik ima oznako s trikotnikom, kaj to pomeni?</h4>
<p>Trikotnik ima ker je delno v konfliktu z drugim pinom.</p>

<h4>Kaj morate storiti, da razrešite to omejitev?</h4>
<p>Pin PC0 nastavimo na Analog ADC_IN10 in izberemo IN10 pretvornik. Pine, ki jih pa ne uporabljamo pa nastavimo na reset_state.</p>

<h4>Koliko ADC vhodnih kanalov ima vaša razvojna plošča?</h4>
<p>16 pretvornikov. IN0 do IN15.</p>

<h4>Kaj se izpiše poleg pina?</h4>
<p>Izpiše se: ADC_IN10.</p>

<h4>Kakšne so možne ločljivosti pretvorbe in območja vrednosti</h4>
<li>a.  8 bit, od 0 do 256</li>
<li>b.  10 bit, od 0 do 1024</li>
<li>c.  12 bit, od 0 do 4096</li>

<h4>Komentar</h4>
<p>Razvojna ploščica deluje tako, da pošilja podatke stanja potenciometra preko ADC pina v spremenljivko, ki se nato izpiše v programu STM studio z zakasnitvijo 100ms. V STMstudio lahko spremljamo spremembe v živo.</p>

<p>Izdelal Nik Vogrinec in Voje Luka.</p>
