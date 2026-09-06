---
stato: bozza
---

# Goal

Altitudine intermedia nella gerarchia dell'azione. L'activity theory (Leontiev)
articola il comportamento su tre livelli: _attività_ (orientata al motivo — il
perché profondo, il bisogno che muove), _azione_ (subordinata a un goal/scopo
cosciente — l'obiettivo formulato), _operazione_ (condizionata dal contesto — la
tecnica adattata alle condizioni correnti). Il goal è il livello medio: più
concreto del motivo, più intenzionale dell'operazione. La stessa azione può
servire motivi diversi; la stessa operazione può realizzare goal diversi.

In Norman il goal è l'apice del ciclo di azione: il punto da cui parte
l'esecuzione (Goal → Plan → Specify → Perform) e a cui torna la valutazione
(Perceive → Interpret → Compare → _nuovo Goal_). Norman lo presuppone come dato
— il ciclo descrive come raggiungere un goal, non come formarlo. È il confine
aperto del modello: tutto ciò che precede l'intenzione resta fuori.

## Il goal nel metodo

`goal`, `task` e la coda `o2/` sono tre altitudini, non sinonimi. Nel metodo:

- _goal_ = l'obiettivo che orienta un arco di lavoro (livello azione, Leontiev)
- _task_ = il compito operativo che lo realizza (livello operazione)
- `o2/` = la coda di operazioni concrete, eseguibili (indice `tasks.md`)

Battezzare la coda o il suo indice col nome `goals` sarebbe sbagliato:
mescolerebbe altitudini e descriverebbe il contenuto in modo falso — per questo
l'indice di `o2/` si chiama `tasks.md`. Il nodo sul Goal esiste per tenere
distinte le quote, non per cambiare la nomenclatura dei file.

Il polo Goal si sdoppia anche nella relazione runtime/meta-ciclo
(`development-meta-cycle`): il Goal del ciclo **runtime** tiene gli obiettivi
costitutivi del dominio (lo scopo per cui l'artefatto in opera esiste), il Goal
del ciclo di **sviluppo** tiene la posizione auspicata dell'artefatto lungo
dimensioni comuni a tutti gli artefatti — attrito, autonomia dell'umano,
temporalità del loop. Quell'articolazione, e lo scioglimento dello split
dev/runtime, vivono in `development-goal`; qui il Goal è trattato nella sua
forma generale, comune ai due cicli.

## La KB informa il Goal, non lo genera

Il Goal non viene dalla KB — nasce all'incrocio tra motivo (che viene da sopra,
dalla vita, dal committente) e KB (che informa, raffina, vincola). Quando la
valutazione produce un esito, l'i3 lo conserva nel filo finché la tensione resta
aperta; solo la conoscenza maturata risale nella KB. Il ciclo successivo legge
l'artefatto persistente — filo corrente e KB stabile — e forma il goal
successivo. La KB informa il ciclo, ma non è la sorgente del motivo né il
contenitore automatico di ogni verdetto.

Questa distinzione ha una conseguenza di progetto: la KB e lo strato output
devono essere _goal-guidati sulla rilevanza, neutri sulla valenza_. I goal
determinano legittimamente cosa mostrare e a quale granularità (rilevanza); il
verdetto buono/cattivo appartiene all'i3, non all'i2. Un i2 già carico di
valenza riflette il bias di chi lo ha prodotto e annulla la funzione di
sicurezza dell'arco di valutazione — l'artefatto non riesce più a portare
cattive notizie.

## Formazione del Goal dai due archi

L'i3 — il Compare di Norman — ha due modalità che il modello originale non
distingue esplicitamente:

- _Verdetto_: confronta l'esito di o3 con un goal esistente; chiude un loop
  noto. È il Norman puro.
- _Triage/formazione-goal_: elabora input esogeni (il mondo ha agito da solo —
  busta paga, normativa, alert) che aprono loop nuovi. Il goal non preesiste: si
  forma nell'i3.

Il secondo modo è l'estensione del metodo oltre Norman. Ma il goal-surfacing può
partire anche dall'arco di esecuzione: predisporre un o3, per esempio un
canovaccio, rende espliciti vincoli e poste e può rivelare Goal latenti. In
entrambi i casi il segnale arriva da un arco, mentre la formazione del Goal
resta un atto riflessivo. Conseguenza per il design dell'autonomia: si può
delegare la chiusura di loop noti (verdetto), ma decidere cosa conta è la cosa
meno esternalizzabile nell'artefatto. È il criterio che differenzia un dominio
dal motivo codificabile e ad alta autonomia da uno personale, il cui motivo
richiede supervisione permanente.

## Il Goal come polo simmetrico al Mondo

Il Goal e il Mondo sono i due confini del ciclo. Se il Mondo è il confine
inferiore — la realtà esterna che l'artefatto non controlla e che gli risponde
da sé — il Goal è il confine superiore: il motivo che viene da sopra, dalla vita
o dal committente, e che l'artefatto non genera. I due poli sono simmetrici
nell'essere entrambi fuori dal controllo dell'artefatto, che si limita a mediare
tra un motivo che riceve e un mondo che gli risponde. Per questo, come al Mondo
si toccano i due versi della cerniera inferiore — o3 esce verso il mondo, i1
entra dal mondo — al Goal si toccano i due versi di quella superiore: il piano
(o1) scende dal goal declinandosi in task, e il verdetto (i3) risale
confrontando l'esito con il goal e formando il goal successivo.

La simmetria è più piena di quanto sembri: entrambe le cerniere sono
scrivi-poi-leggi attraverso un medium persistente. Al Mondo o3 scrive un effetto
e i1 lo rilegge più tardi — il mondo trattiene lo stato; al Goal i3 conserva il
verdetto nell'artefatto e il goal successivo lo legge. L'unica vera asimmetria
non è tra le due cerniere ma tra i due medium: il mondo persiste da solo,
l'artefatto solo se qualcuno lo scrive (cfr. `action-cycle`, `system-image`). Un
confronto non registrato è un confronto perso; quando diventa conoscenza stabile
viene poi depositato nella KB.

Qui il ciclo si chiude e si riapre. Il goal si declina in task — la coda
operativa che lo realizza — ma i task non vivono in questo nodo né in `metodo`:
vivono in `o1/plan.md` e `o2/` di ciascun artefatto, perché sono operativi e
volatili. Ciò che è stabile, e quindi metodologico, è dove avviene il confronto
da cui i task nascono: la sintesi dello stato corrente che l'i3 mette a paragone
con il goal. Il confronto assume forme diverse secondo il dominio: stato
osservato contro obiettivi personali, runtime contro configurazione desiderata,
dati pubblicati contro fonti operative. La configurazione cambia, la meccanica
resta la stessa: lo scostamento genera lavoro soltanto dopo essere stato
interpretato e giudicato.

Lo stesso lavoro può nascere anche dall'altro polo: al Mondo un i1 esogeno apre
un goal nuovo per triage, senza un confronto che lo precede (cfr. «Formazione
del Goal dai due archi» e `world`). I due poli sono dunque le due sorgenti del
lavoro: il Goal lo rigenera chiudendo loop noti, il Mondo lo apre con segnali
inattesi.

Il contratto del register root che materializza questo polo vive in
`goal-register`; qui resta il modello del Goal.

## Riferimenti

- A. N. Leont'ev, _Activity, Consciousness, and Personality_ (1978), §3.5 "The
  General Structure of Activity" — gerarchia attività/azione/operazione:
  attività ↔ motivo, azione ↔ goal/scopo cosciente, operazione ↔ condizioni.
- Donald Norman, _The Design of Everyday Things_, Revised and Expanded Edition
  (2013), Cap. 2 — il Goal come apice del ciclo a sette stadi; cfr.
  `action-cycle`. Provenienza e limite di disponibilità corrente sono dichiarati
  nel register `world.md`.

Connessioni:

- [action-cycle](action-cycle.md)
- [goal-register](goal-register.md)
- [development-goal](development-goal.md)
- [development-meta-cycle](development-meta-cycle.md)
- [input](input.md)
- [world](world.md)
- [plan](plan.md)
- [tasks](tasks.md)
- [cognitive-system](cognitive-system.md)
- [cognitive-artifact](cognitive-artifact.md)
- [cognitive-fidelity](cognitive-fidelity.md)
- [cognitive-artifact-design](cognitive-artifact-design.md)
