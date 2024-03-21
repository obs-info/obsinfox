# OBSINFOX: A Multi-Label Dataset of French Fake News


We present a corpus of 100 articles selected from 17 sources of French press considered unreliable by expert organizations. Those articles have all been annotated by 8 human annotators using 11 labels. 


## Labels

- `Fake News`: the article describes at least a false or exaggerated fact.

**Example:** *La 5G est le meilleur moyen de prendre le contrôle de votre esprit* / *5G is the best way to take control of your mind*. 
  
- `Places, Dates, People`: the article mentions at least one place, date or person.

**Example:** *La cérémonie d'investure d'Emmanuel Macron pour son second mandat a eu lieu à Paris le samedi 7 mai 2022* / *Emmanuel Macron's investiture ceremony for his second term took place in Paris on Saturday, May 7, 2022*.

- `Facts`: the article reports at least one fact, i.e. a state of affairs or event, which may be true or false.

**Example:** *La terre est ronde*, *La terre est plate* / *Earth is round*, *Earth is flat*.
  
- `Opinions`: the article expresses at least one opinion.

**Example:** *Il devient évident que la zone ne pourra être sécurisée avant le printemps 2025* / *It is becoming clear that the area cannot be secured before the spring of 2025*.
  
- `Subjective`: the article contains more opinions than facts.

**Example:** *Tribune - La Vème République en péril* / *Tribune - The Fifth Republic in danger*.
  
- `Reported Information`: the information of the article is reported by another person or source, and is not directly endorsed.

**Example:** *Selon le rapporteur du Sénat, le projet de loi ne sera pas examiné avant la rentrée prochaine* / *According to the Rapporteur of the Senate, the law project will not be examined before the start of next year*.
  
- `Sources Cited`: the article cites at least one source, for at least one fact.

**Example:** *Selon le porte-parole de la base de Cap Canavéral, le sergent Ginger Shreitmueller, la fusée Titan 4 a explosé 40 secondes après son décollage* / *According to Cap Canaveral base spokesman Sergeant Ginger Shreitmueller, the Titan 4 rocket exploded 40 seconds after lift-off*.
  
- `False Information`: the article contains at least one false fact.

**Example:** *Depuis des décennies, la pénicilline est presque inutile contre toute maladie* / *For decades, penicillin has been almost useless against any disease*.
  
- `Insinuation`: the article suggests a certain reading of a fact, without saying so explicitly.

**Example:** ``Vaccin anti-Covid : que penser des troubles menstruels ?'' / ``Covid vaccine: what about menstrual disorders?''.

  
- `Exaggeration`: the article  describes a real fact with exaggeration.

**Example:** *Ursula von der Leyen menace les Italiens à la veille des élections* \[alors quUrsula von der Leyen, souhaitait simplement s'assurer que les élections aient lieu dans le respect des principes démocratiques défendus par l'Union Européenne] / *Ursula von der Leyen is threatening the Italians on the eve of the elections* \[when in fact Ursula von der Leyen simply wanted to ensure that the elections took place in accordance with the democratic principles upheld by the European Union].
  
- `Offbeat Title`: the article has a misleading headline not accurately reflecting the content of the article.

**Example:** *La France condamnée pour avoir placé un enfant musulman dans une famille chrétienne* \[alors qu'en réalité la France a été condamnée pour avoir placé l'enfant dans une famille où il a été victime d'abus] / *France condemned for placing a Muslim child in a Christian family* \[when in fact France was condemned for having placed the child in a family where he or she had been abused].

These labels have been chosen to better caracterize the content of each article. Some of them are objective (`Places, Dates, People`, `Facts`, `Sources Cited`, etc.) while others rely more on the annotators' perception. Analyzing the co-ocurrence between the labels help understand how alternative news are perceived by readers.


## Metadata

Additional metadata are provided for possible further analyses.

- `Title`: the title of the article.
- `URL`: the url of the article.
- `Annotator`: the anonymized reference to the annotator. 

## Sources

| Source | URL  |  Number of articles
|---|---|---|
| La Lettre Patriote | www.lalettrepatriote.com |  6
| Le Média en 4-4-2 | www.lemediaen442.fr |   8
| Le Saker Francophone | www.lesakerfrancophone.fr |  4
| Le Salon Beige | www.lesalonbeige.fr |  5
| Les DéQodeurs | www.lesdeqodeurs.fr |  5
| Les Moutons Rebelles | www.lesmoutonsrebelles.com |  6
| Les Observateurs | www.lesobservateurs.ch |  3
| lezarceleurs | www.lezarceleurs.blogspot.com |  5
| Réseau International | www.reseauinternational.net  |  6
| Riposte Laïque | www.ripostelaique.com | 5
| Breizh Info | www.breizh-info.com  |  4
| Boulevard Voltaire | www.bvoltaire.fr |  7
| dreuz.info | www.dreuz.info  |  6
| France Soir | www.francesoir.fr  |  11
| Le Libre Penseur | www.lelibrepenseur.org  |  6
| Polemia | www.polemia.com   |  5
| Profession Gendarme | www.profession-gendarme.com |  8
| **Total** |  |  100


# Cite us

Icard, B., Maine, F., Faye, G., Casanova, M., Chanson, J., Gadek, G., Atemezing, G., Bancilhon, F., & Égré, P. (2024). A Multi-Label Dataset of French Fake News: Human and Machine Insights, In Proceedings of the International Conference on Language Resources and Evaluation (LREC-COLING 2024).

# License

This dataset and associated code in the repository are distributed under the CC BY-NC 4.0 license.


