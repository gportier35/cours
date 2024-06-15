---
title: "Accueil"
order: 0
in_menu: true
---
:::typeAdmonition collapsible titre

Bloc de texte en Markdown multiligne caché par défaut

:::

---
tags: 4e,électricité
---
# Entraînements lois du courant
## Exercice 1 - En série
Calculer les éléments manquants dans le schéma ci-dessous:
![](https://i.ibb.co/zZNg5FQ/Lois-s-rie.jpg)
:::success
::: spoiler Voir la réponse
- **L'intensité est la même dans tout ce circuit en série.**
- On connaît la résistance $R_1 = 80 Ω$ et $I = 100 mA = 0,1 A$. On cherche la tension $U_{R1}$ à l'aide de la **loi d'Ohm** **$U_{R1}=R_1 \times I =80 \times 0,1 = 8 V$**
- On connaît toutes les tensions sauf cette de la lampe $U_L$. On applique la **loi d'additivité de la tension** : $U_G = U_{R1} + U_{R2}+U_L$ ce qui donne : $U_G - U_{R1} - U_{R2}=U_L$. Donc : **$U_L = 12 - 8 -2 = 2V$**.
- Enfin, on applique de nouveau la **loi d'Ohm** pour trouver la valeur de la résistance $R_2$ : $R_2 = {U_{R2} \over I}={2 \over 0,1}=20Ω$
:::
## Exercice 2 - En dérivation
Calculer les éléments manquants dans le schéma ci-dessous:
![](https://i.ibb.co/L1NHsHw/20231116-144028.jpg)
:::success
::: spoiler Voir la réponse
- Pour pouvoir appliquer la **loi d'additivité de l'intensité dans ce circuit en dérivation** (${I = I_1 + I_2}$), il faut déterminer l'intensité $I_1$.
- On calcule à l'aide de la loi d'Ohm : $I_1 = {U_1 \over R_1}$, sachant que $U_1=12V et R_1 = 100Ω$. $I_1 = {12 \over 100} = 0,12 A$.
- On applique la loi d'additivité de l'intensité avec $I_1 = 0,12 A et I_2 = 10 mA = 0,010 A$ : $I=0,12 + 0,01 = 0,13A$. L'intensité de la branche principale est donc **0,13 A**.
::: 