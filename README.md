# PV207 - Business Process Management - Homeworks

## About

This repository contains the solution of individual homeworks for subject [PV207](https://is.muni.cz/predmet/fi/jaro2020/PV207) from the [Faculty of Informatics Masaryk University](https://www.fi.muni.cz/index.html.en) in the Spring 2020 semester. Solutions were performed in the [jBPM](https://www.jbpm.org/) toolkit.
## Contents

* [Homework 0](/HW0)
* [Homework 1](/HW1)
* [Homework 2](/HW2)

## Homework 0

This homework is about introduction into jBPM toolkit. The requirement was to create basic process which can be completed manually or can be automated. Solution contains process which has Exclusive Gateway with default route to Manual task (the "manual solution") and the other route to Intermediate Signal. The other route has condition for Process Variable mode that if it is equal to value Drone then the process should choose the other route and be completed the automated way.