**Vorbereitende Aufgabe:**
- Clonen Sie die aktuellegit-Aufgabe
- Lesen Sie das Kapitel: Git-Branching und beantworten Sie folgende Fragen.  

**Git Branching:**

1. Was ist ein Git-Branch?
2. Warum ist es sinnvoll, Branches in Git zu verwenden?
3. Wie erstellt man einen neuen Branch in Git?
4. Wie wechselt man zwischen verschiedenen Branches in Git?
5. Erkläre den Unterschied zwischen einem lokalen und einem Remote-Branch.

**Git Merges:**

1. Was ist ein Git-Merge?
2. Wie führt man einen Merge in Git durch?
3. Erkläre den Unterschied zwischen einem Fast-Forward Merge und einem Recursive Merge.
4. Was ist ein Merge-Konflikt, und wie löst man ihn?

**Git Rebase:**

1. Was ist ein Git-Rebase?
2. Wie führt man ein Rebase in Git durch?
3. In welchen Situationen könnte es sinnvoll sein, ein Rebase anstelle eines Merges zu verwenden?
4. Was sind die potenziellen Risiken beim Rebasen?

**Allgemeine Fragen:**

1. Wie kannst du den aktuellen Branch in Git identifizieren?
2. Welchen Befehl würdest du verwenden, um lokale Änderungen zu stashen, bevor du zu einem anderen Branch wechselst?

**Praktische Umsetzung:**
- Erstellen Sie einen neuen Branch "Task1" und wechseln Sie in diesen
- Machen Sie aus "Apfe" einen "Apfel", commiten Sie und pushen Sie den neuen Branch zum remote
- Wechseln Sie zurück in den main Branch und machen Sie aus dem "Apfe" "Bier".
- Versuchen Sie nun den Task1 Branch in main zu mergen
- Warum kommt es zu dem Konflikt und wie erkennen Sie, wo ein Konflikt vorliegt?
- Lösen Sie den Merge-Konflikt und löschen Sie anschließen den Task1 Branch lokal und remote
- Erstellen Sie einen Branch "update" und wechseln Sie in diesen.
- Fügen Sie drei Dinge zur Einkaufsliste und stellen Sie sicher, dass der Branch auch remote auf dem aktuellen Stand verfügbar ist.
- Mergen Sie update in main und pushen Sie zum Remote.
