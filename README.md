# CryptoLab-CProjet-

Un laboratoire expérimental en C - MR. EDEN JOHEIR

<img width="891" height="640" alt="Capture d’écran 2026-11-07 à 16 07 18" src="https://github.com/user-attachments/assets/6bc3dedd-0f0e-4d71-92a5-962a08bc8692" />



Mon premier programme en C,le chiffrement de César

Ce programme demande un texte et un nombre de décalage, puis remplace chaque lettre par une autre lettre située plus loin dans l’alphabet. Par exemple, avec un décalage de 3, A devient D.

La fonction cesar parcourt le texte caractère par caractère. Elle repère les lettres, conserve les majuscules et les minuscules, et laisse les espaces et la ponctuation inchangés. Le calcul avec % 26 permet de revenir au début de l’alphabet quand on dépasse Z ou z.

Dans main, fgets lit le texte saisi et scanf récupère le décalage. Le programme affiche ensuite le résultat.

Ce code est un exercice d’apprentissage : le chiffrement de César ne protège pas réellement un message.

