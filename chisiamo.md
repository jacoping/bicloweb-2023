---
layout: pages
title: Chi siamo
permalink: /chisiamo
rank: 2
show: true
---

Biclò è un progetto in grado di favorire la transizione dei cittadini dall’uso di auto e moto a
quello di bici tradizionali, elettriche o monopattini, risolvendo il problema di furti, vandalismi e usura dei mezzi personali attraverso lo sviluppo di una rete di infrastrutture di posteggio, le “Biclostazioni™”, nell’area metropolitana di Firenze.
Le Biclostazioni avranno accesso automatizzato tramite app, saranno al coperto, videosorvegliate, dotate di comode rastrelliere, di prese di ricarica per i mezzi elettrici e di kit per la prima manutenzione dei mezzi.

Biclò è un progetto per chi va in bici, ma anche per chi non ci va. Più di tutto è un progetto per la nostra città: perchè decongestiona il traffico cittadino, migliora la qualità dell’aria, riduce le emissioni di CO2 e l’inquinamento acustico, ottimizza i tempi di percorrenza e la conciliazione vita lavoro, promuove una cultura della cura della propria bicicletta e del parcheggio ordinato dei mezzi, libera lo spazio occupato dalle auto in sosta a favore di piazze e spazi verdi a disposizione di tutti.

Biclò accelera le trasformazioni dell’oggi, avvicinando il domani migliore.


<br><br>

<h1 class="text-center"> Il team </h1>
Abbiamo ideato Biclò a partire da un nostro bisogno individuale, di parcheggiare al sicuro le nostre biciclette.
Poi ci siamo resi conto che il nostro bisogno individuale era in realtà un bisogno collettivo, e che un network di parcheggi per biciclette ha il potenziale di rendere migliori le nostre città.

<br>



{% for m in site.data.members %}
<div class="d-flex flex-column align-items-center">
    <div class="rounded-circle" style="width: 200px; height: 200px; background-image: url('{{m.foto}}'); background-size: cover;"></div> 
    <h3> {{ m.nome }} </h3>
    <h4> {{ m.ruolo }} </h4>
</div>
<p class="fw-lighter"> {{ m.bio }} </p>
<br>
{% endfor %}



<br><br>
<p class="text-center"> Se vuoi aggiornamenti o informazioni,<br>o solo per parlare con noi scrivi a:
<a class="text-light" href="mailto: info@biclo.it"> info@biclo.it</a> </p>


