# Micro processeur en CRAPS

<p style="text-align: justify;">
    Ce projet a été réalisé dans le cadre d'un TP (Travaux Pratiques) dirigé par  <a href="https://fr.linkedin.com/in/jean-christophe-buisson">Jean-Christophe Buisson</a> et appuyé sur son  <a href="https://amazon.fr/stores/Jean-Christophe-Buisson/author/B004N2KQXM">livre</a> à l'<a href="https://www.enseeiht.fr/">ENSEEIHT</a>.
    <br>
    Le but de ce projet était d'implémenter en SHDL* un microprocesseur CRAPS. CRAPS est un microprocesseur 32 bits basé sur l'architecture SPARC, qui appartient à la famille des architectures RISC*. Son jeu d'instructions est simplifié, permettant l'exécution de la majorité des opérations en un seul cycle, ce qui optimise à la fois la vitesse et la simplicité de conception.
    <br>
    En comparaison avec la famille de processeurs CISC, comme ceux basés sur l'architecture x86, les processeurs CISC consomment généralement plus d'énergie. En effet, pour réaliser une opération, ils doivent passer par plusieurs cycles d'horloge.
</p>

<div style="text-align: center;">
| CISC                                                  | RISC                                              |
|-------------------------------------------------------|---------------------------------------------------|
| Moins de registres                                    | Plus de registres                                |
| Plus de modes d'adressage                              | Moins de modes d'adressage                      |
| Les instructions prennent un temps de cycle variable  | Les instructions prennent un cycle unique       |
| Le pipelining est difficile                            | Le pipelining est facilité                     |
</div>
