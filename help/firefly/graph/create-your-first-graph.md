---
title: ​3. Erstellen des ersten Diagramms
description: Eine Schritt-für-Schritt-Anleitung zum Erstellen Ihres ersten Firefly Graph-Workflows
feature: Image Editing, Gen AI
role: User
level: Beginner
jira: KT-
hide: true
hidefromtoc: true
source-git-commit: 4dd919a2b06f0852dc0010b0f79d5a0b2eae4c1a
workflow-type: tm+mt
source-wordcount: '193'
ht-degree: 1%

---

# &#x200B;3. Den ersten Graph erstellen.

Sobald Sie wissen, was ein Knoten, eine Verbindung und eine Vorlage sind, können Sie Ihren ersten Arbeitsablauf erstellen.

1. Öffnen Sie den Firefly und wählen Sie im Menü links **Graph** aus.
1. Wählen Sie **Neues Diagramm erstellen**.
1. Klicken Sie mit der rechten Maustaste auf die leere Arbeitsfläche und wählen Sie **+ neuer Knoten** aus.
1. Wählen Sie im linken Menü **Eingabe** und anschließend **Eingabebild** aus.
   ![Knoten](../assets/node.png)
Dies ist ein Knoten, mit dem Sie eine Grafik importieren können.
1. Ziehen Sie ein Bild per Drag &amp; Drop auf den Knoten.
   ![Knoten mit Bild](../assets/node-image.png)
1. Klicken Sie mit der rechten Maustaste auf die leere Arbeitsfläche und wählen Sie **+ neuen Knoten** aus und wählen Sie im Dialogfeld **Verlaufsmaske** aus.
1. Klicken Sie mit der rechten Maustaste auf die leere Arbeitsfläche und wählen Sie **+ neuer Knoten** aus und wählen Sie im Dialogfeld **Maske anwenden** aus.
1. Schließen Sie die Knotenausgabe **Eingabebild** an die Knoteneingabe **Maske anwenden** an.
1. Schließen Sie die **Verlaufsmaske**-Ausgabe an die **Maske anwenden**-Maske/Kanaleingabe an.
   ![Knoten einstecken](../assets/plug-in.png)

## Nächster Schritt

Vorlagen als Ausgangspunkt verwenden? Wechseln Sie zu [4. Passen Sie eine Vorlage &#x200B;](https://experienceleague.adobe.com/en/docs/creative-cloud-enterprise-learn/cce-learning-hub/fireflyoverview/firefly-graph/customize-template) an, damit sie Ihren eigenen Auftrag widerspiegelt.
