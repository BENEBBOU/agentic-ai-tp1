# TP1 - Les bases de PyTorch

Notebook : [`TP1_Bases_PyTorch_corrige.ipynb`](TP1_Bases_PyTorch_corrige.ipynb)

- Tensors, autograd, `nn.Module`, fonctions de coût, optimiseurs, boucle d'entraînement, `train()` / `eval()`, `Dataset` / `DataLoader`, sauvegarde.
- **Exercice 1** : régression linéaire multiple (salaire selon l'ancienneté et l'expertise), retour aux coefficients en unités d'origine, effet du bruit.
- **Exercice 2** : classification MNIST avec un MLP (accuracy, precision, recall, F1, matrice de confusion, erreurs, sauvegarde).
- **Exercice 3** : classification des fleurs Iris, comparaison avec un modèle sans couche cachée.
- **Exercice 4** : CNN sur MNIST (≈ 98,9 % sur le test), Dropout.

Chaque exercice est complété et chaque question reçoit une réponse argumentée, appuyée sur les résultats obtenus.

## Exécution

```bash
uv sync
uv run jupyter lab      # ou ouvrir le notebook dans VS Code avec le noyau .venv
```

MNIST est téléchargé automatiquement dans `data/`.
