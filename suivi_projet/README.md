# PROJET_HAX712X : Enquête sur la circulation des vélos à Montpellier

## On va décrire notre projet

## Dans cette section, on va mettre les objectifs

## Ici, on va décrire les données que l'on a utilisé

## Peut etre les plannings (à voir...)

```{mermaid}
    gantt
        title Preparing Polyglot Notebooks Talk for Stir Trek 2023
        axisFormat %m-%d
        section Proposal <br> and <br> Evaluation
            Submit Abstract         :done,                2023-01-15, 2023-02-18
            Session Evaluation      :done, EVAL,          2023-02-18, 2023-03-05
            Talk Accepted           :milestone, done,     after EVAL,
        section Talk <br> Preparation
            Research & Outlining    :done, OUTLINE,       2023-03-12, 9d
            Create Mermaid Examples :done, MER_EXAMPLE,   after OUTLINE, 5d
            Write Mermaid Articles  :active, MER_ART,     after MER_EXAMPLE, 7d
            Write Jupyter Articles  :                     after MER_ART, 3d
        section Delivery
            Final Notebook          :crit, NOTEBOOK,      2023-04-19, 7d
            Rehearsal               :crit,                after NOTEBOOK, 2023-05-04
            Stir Trek 2023          :milestone, crit,     2023-05-05, 1d
```
