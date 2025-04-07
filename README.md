# Analyse von Verkaufsdaten inkl. Umsatzvorhersagen

In dieser Analyse wurden Verkaufsdaten untersucht und ein Vorhersagemodell zur Prognose von Umsätzen entwickelt. Der Fokus lag auf der Implementierung eines Random Forest-Modells, das durch umfangreiches Feature Engineering und eine sorgfältige Evaluierung optimiert wurde.

## Ergebnisse
- Zeitbasierte Features trugen wesentlich zur Verbesserung der Modellgenauigkeit bei, indem sie saisonale Muster und Trends in den Verkaufsdaten erfassten.
- Die wichtigsten Prädiktoren für die Zielvariable (Sales) sind:
  - Kundenanzahl
  - Wochentag
  - Promotionseffekte
- Das Random Forest-Modell erzielte folgende Ergebnisse:
  - **Trainings-RMSE**: 943.99
  - **Test-RMSE**: 946.23
  - **Test-R²**: 0.94
  - **RMSE-Differenz**: 2.25
  - **R²-Differenz**: 0.0001

Das Modell zeigt keine Anzeichen von Overfitting und kann zur Unterstützung fundierter Entscheidungen in Bezug auf , Marketing und Ressourcenplanung eingesetzt werden.

## Projektübersicht
- **Datenquellen**: `train.csv` und `store.csv`
- **Features**: Zeitbasierte Features, Kundenanzahl, Promotionseffekte
- **Modelle**: Random Forest, Gradient Boosting, Lineare Regression
- **Tools**: Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn



https://online.xd-i.com/users/sign_in
