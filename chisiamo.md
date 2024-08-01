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

<h2 class=""> Il nostro team </h2>
Abbiamo ideato Biclò a partire da un nostro bisogno individuale, di parcheggiare al sicuro le nostre biciclette.
Poi ci siamo resi conto che il nostro bisogno individuale era in realtà un bisogno collettivo, e che un network di parcheggi per biciclette ha il potenziale di rendere migliori le nostre città.


<div class="container">
{% for m in site.data.members %}
    <div class="row my-5">
        <div class="col-sm-4 d-flex flex-column align-items-center">
        <h3 class="h5 mb-0"> {{ m.nome }} </h3>
        <h4 class="h5 mb-3 fw-lighter"> {{ m.ruolo }} </h4>
            <div class="rounded-circle mb-3" style="width: 200px; height: 200px; background-image: url('{{m.foto}}'); background-size: cover;"></div>
        </div>   
         <div class="col-sm-1">
        </div> 
        <div class="col-sm-6">
            <p class="fw-light lh-2"> {{ m.bio }} </p>
        </div>
    </div>
{% endfor %}
</div>


<!-- VERSIONE PRECEDENTE
{% for m in site.data.members %}
<div class="mt-5 d-flex flex-column align-items-center">
    <div class="rounded-circle" style="width: 200px; height: 200px; background-image: url('{{m.foto}}'); background-size: cover;"></div> 
    <h3 class="h5 mt-2 mb-0 fw-light"> {{ m.nome }} </h3>
    <h4 class="h5 mb-3"> {{ m.ruolo }} </h4>
    <p style="max-width: 400px" class="fw-lighter lh-1"> {{ m.bio }} </p>
{% endfor %}
-->

<br>
<h2 class="mt-5"> La cooperativa </h2>
<p>Biclò è una Società Cooperativa Impresa Sociale. Abbiamo scelto questa forma societaria perché crediamo nei valori della cooperazione e della responsabilità sociale di impresa.</p>
<!-- <p> <a target="_blank" href="/res/biclo-statuto.pdf"> Scarica lo statuto della cooperativa </a> </p> -->
<p> <a target="_blank" href="/res/biclo-bilanciosociale-2023.pdf"> Scarica il bilancio sociale 2023 </a> </p>





<br><br>
<p class="text-center"> Per aggiornamenti o informazioni, o anche solo per fare due chiacchiere, scrivici: <br>
<a class="text-light" href="mailto: info@biclo.it"> info@biclo.it</a> </p>


