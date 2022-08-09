**Hypothesis**

A hypothesis is an educated guess about something in the world around you. It should be testable, either by experiment or observation. 
Ex: A new medicine you think might work.
    A way of teaching you think might be better.
    A possible location of new species.

If you are going to propose a hypothesis, it’s customary to write a statement. Your statement will look like this:
“If I…(do this to an independent variable)….then (this will happen to the dependent variable).”
For example:
    If I (decrease the amount of water given to herbs) then (the herbs will increase in size).
    If I (give patients counseling in addition to medication) then (their overall depression scale will decrease).

**Hypothesis testing**

Hypothesis testing in statistics is a way for you to test the results of a survey or experiment to see if you have meaningful results. You’re basically testing whether your results are valid by figuring out the odds that your results have happened by chance. If your results may have happened by chance, the experiment won’t be repeatable and so has little use.

Figure out your null hypothesis, (The null hypothesis, H0 is the commonly accepted fact; it is the opposite of the alternate hypothesis)
State your null hypothesis,
Choose what kind of test you need to perform,
Either support or reject the null hypothesis.



**Statistical Significance - ANOVA Test (Varianzanalyse) , F-test**

Varianzanalyse (ANOVA) ist eine statistische Formel, die zum Vergleich von Varianzen zwischen den Mitteln (oder dem Durchschnitt) verschiedener Gruppen verwendet wird.
ANOVA hilft dabei, diese Gruppe zu vergleichen, um herauszufinden, ob sie statistisch unterschiedlich sind oder ähnlich sind.
Das Ergebnis von ANOVA ist die „F-Statistik“. Dieses Verhältnis zeigt den Unterschied zwischen der Varianz innerhalb der Gruppe und der Varianz zwischen Gruppen an, was letztendlich eine Zahl ergibt, die eine Schlussfolgerung zur Folge hat, dass die Nullhypothese unterstützt oder zurückgewiesen wird. Wenn zwischen den Gruppen ein erheblicher Unterschied besteht, wird die Nullhypothese nicht unterstützt und das F-Verhältnis wird größer sein.

*Einweg-ANOVA*

H0: All group means are equal.
HA: At least one group mean is different from the rest.

Die Einweg-Varianzanalyse wird auch als einfaktorielle ANOVA oder einfache ANOVA bezeichnet. Wie der Name schon sagt, eignet sich die einseitige ANOVA für Experimente mit nur einer unabhängigen Variable (Faktor) mit zwei oder mehr Ebenen. Zum Beispiel kann eine abhängige Variable der Monat des Jahres sein, in dem sich mehr Blumen im Garten befinden. Es wird zwölf Stufen geben. Eine einfache ANOVA geht von Folgendem aus:

Unabhängigkeit: Der Wert der abhängigen Variable für eine Beobachtung ist unabhängig vom Wert aller anderen Beobachtungen.
Normalität: Der Wert der abhängigen Variable ist normal verteilt
Varianz: Die Varianz ist in verschiedenen Versuchsgruppen vergleichbar.
Fortlaufend: Die abhängige Variable (Anzahl der Blumen) ist kontinuierlich und kann auf einer Skala gemessen werden, die unterteilt werden kann.

*Vollfaktorielle ANOVA (auch als bidirektionale ANOVA bezeichnet)*

Eine vollfaktorielle ANOVA wird verwendet, wenn es zwei oder mehr unabhängige Variablen gibt. Jeder dieser Faktoren kann über mehrere Stufen verfügen. Eine vollfaktorielle ANOVA kann nur bei einem vollfaktoriellen Experiment verwendet werden, bei dem jede mögliche Permutation von Faktoren und deren Ebenen genutzt wird. Dies könnte der Monat des Jahres sein, in dem mehr Blumen im Garten sind, und dann die Anzahl der Sonnenscheinstunden. Diese bidirektionale ANOVA misst nicht nur die unabhängige gegenüber der unabhängigen Variable, sondern auch, wenn sich die beiden Faktoren gegenseitig beeinflussen. Eine Zweiweg-ANOVA geht von Folgendem aus:

Kontinuierlich: Wie bei einer einfachen ANOVA sollte die abhängige Variable kontinuierlich sein.
Unabhängigkeit: Jede Stichprobe ist unabhängig von anderen Stichproben ohne Crossover.
Varianz: Die Varianz der Daten zwischen den verschiedenen Gruppen ist gleich.
Normalität: Die Stichproben sind repräsentativ für eine normale Bevölkerung.
Kategorien: Die unabhängigen Variablen sollten in separaten Kategorien oder Gruppen vorliegen.

*Warum funktioniert ANOVA?*
Einige Leute stellen die Notwendigkeit einer ANOVA in Frage; schließlich können Mittelwerte nur durch Betrachten bewertet werden. Aber ANOVA tut mehr als nur Mittelwerte vergleichen.

Obwohl die Mittelwerte verschiedener Gruppen unterschiedlich zu sein scheinen, könnte dies eher auf einen Stichprobenfehler als auf die Auswirkung der unabhängigen Variable auf die abhängige Variable zurückzuführen sein. Wenn dies auf einen Stichprobenfehler zurückzuführen ist, ist der Unterschied zwischen den Mittelwerten der Gruppen bedeutungslos. ANOVA hilft dabei, herauszufinden, ob der Unterschied der Mittelwerte statistisch signifikant ist.

**ANOVA zeigt auch indirekt, ob eine unabhängige Variable die abhängige Variable beeinflusst. Angenommen, dass ANOVA beispielsweise im obigen Blutzuckerspiegel-Experiment feststellt, dass Gruppenmittel statistisch nicht signifikant sind und der Unterschied zwischen Gruppenmitteln nur auf Probenahmefehler zurückzuführen ist. Dieses Ergebnis zeigt, dass die Art des Medikaments (unabhängige Variable) kein signifikanter Faktor ist, der den Blutzuckerspiegel beeinflusst.**

*F-value*
If the variation between the sample means is high relative to the variation within each of the samples, then the F-value will be large.

The higher the F-value in an ANOVA, the higher the variation between sample means relative to the variation within the samples.
The higher the F-value, the lower the corresponding p-value.
If the p-value is below a certain threshold (e.g. α = .05), we can reject the null hypothesis of the ANOVA and conclude that there is a statistically significant difference between group means.

In the majority of analyses, an alpha of 0.05 is used as the cutoff for significance. If the p-value is less than 0.05, we reject the null hypothesis that there's no difference between the means and conclude that a significant difference does exist. If the p-value is larger than 0.05, we cannot conclude that a significant difference exists. 

That's pretty straightforward, right?  Below 0.05, significant. Over 0.05, not significant. 

s.h. Heft How to calculate ANOVA