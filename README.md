# 📊 Expense Tracker

Un'app Flutter per la gestione delle spese personali. Consente di aggiungere, visualizzare e rimuovere transazioni, con un grafico riepilogativo delle spese per categoria.

---

## Funzionalità

- **Aggiungi spese**: inserisci titolo, importo, data e categoria.
- **Visualizza spese**: lista dinamica di tutte le spese registrate.
- **Rimuovi spese**: possibilità di eliminare una spesa con funzione di undo.
- **Grafico delle spese**: rappresentazione visiva delle spese per categoria.
- **Design responsive**: layout adattivo per dispositivi piccoli e grandi.
- **Tema chiaro/scuro**: supporto per modalità dark/light.

---

## Struttura del progetto

lib/

├── main.dart # Punto d'ingresso dell'app

├── models/

│ └── expense.dart # Modello Expense e categorie

├── widgets/

│ ├── expenses.dart # Schermata principale con lista e grafico

│ ├── new_expense.dart # Form per aggiungere nuove spese

│ ├── expenses_list/

│ │ ├── expenses_list.dart # Lista scrollabile delle spese

│ │ └── expense_item.dart # Singolo elemento della lista

│ └── chart/

│ ├── chart.dart # Grafico delle spese per categoria

│ └── chart_bar.dart # Barra del grafico

---

## Come eseguire il progetto

1. Clona il repository:

      ```bash
      git clone https://github.com/BrambillaMarco/flutter-expense-tracker
      cd flutter-expense-tracker


2. Assicurati di avere Flutter installato e configurato:
Guida ufficiale Flutter: https://docs.flutter.dev/get-started

3. Avvia l'app:

flutter run

---

## Screenshot

<img width="500" height="1055" alt="Screenshot_1758801134" src="https://github.com/user-attachments/assets/f11ad0ee-97ff-4d02-b0d1-01bad9a75e44" />

<img width="500" height="1055" alt="Screenshot_1758801333" src="https://github.com/user-attachments/assets/6d621a8e-f990-445b-afca-90014152cfac" />

<img width="500" height="1055" alt="Screenshot_1758801345" src="https://github.com/user-attachments/assets/b922b6bf-3643-406d-9a46-104a882eebd3" />

---

## Cosa ho imparato

-Gestire lo stato con StatefulWidget e setState.

-Suddividere la UI in widget modulari e riutilizzabili.

-Implementare layout responsive per diverse dimensioni dello schermo.

-Gestire input utente e validazioni.

-Visualizzare dati con grafici e rappresentazioni dinamiche.

-Implementare undo per la rimozione di elementi nella lista.





