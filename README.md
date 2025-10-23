# 🧠 Teachable Machine Project: Hand Gesture Recognition

## 🎯 Project Name
**Thumbs Detector** – Recognition of hand gestures (“Thumbs up” 👍 / “Thumbs down” 👎)

---

## 📝 Project Goal
The goal of this project was to train a simple image recognition model that can distinguish between the two hand gestures **“Thumbs up”** and **“Thumbs down.”**  
The model should recognize whether a person is showing approval (thumbs up) or disapproval (thumbs down).

---

## ⚙️ Procedure

### 🔹 Steps in Teachable Machine
1. I created a **new image project** using the [Teachable Machine](https://teachablemachine.withgoogle.com/).  
2. Defined two **classes**: `Thumbs up` and `Thumbs down`.  
3. Collected **training images** for each class using my webcam.  
4. Trained the model and **tested** it live with the webcam.  
5. Finally, I used the **live preview** to check the model’s prediction accuracy.

---

### 🔹 Data Collection
- **Image source:** Webcam only (no uploaded images).  
- **Number of classes:** 2  
- **Class 1:** Thumbs up 👍  
- **Class 2:** Thumbs down 👎  
- **Number of images:** Around 20–25 images per class.  
- **Variations:** Different distances from the camera, slightly different hand angles.  

---

### 🔹 Observations During Data Collection
- Lighting conditions were not always consistent — bright and dark areas affected recognition accuracy.  
- The “Thumbs down” gesture was harder to capture, since it’s less natural and the thumb was sometimes partially hidden.  
- I used a plain, light-colored background to avoid distractions.  

---

### 🔹 Training
- Training took only a few seconds (around 30–45 seconds).  
- There were no error messages or technical issues.  
- After training, the model immediately showed live results via the webcam.

---

## 🔬 Test Results

- The model recognized **“Thumbs up”** almost perfectly (≈ 100%).  
- The **“Thumbs down”** gesture was much harder to classify correctly.  
- In similar hand positions or under poor lighting, it was sometimes misclassified as “Thumbs up.”  

---

## 📊 Reliability Evaluation
**Overall Rating:** medium to good.  
- One of the two classes (Thumbs up) was clearly dominant.  
- The model was stable overall, but not yet generalizable enough.  

---

## 🚀 Suggestions for Improvement
To improve recognition accuracy, I would:
- **Collect more training images** (at least 50–100 per class).  
- **Use different lighting conditions** (bright, shadowy, artificial light).  
- Capture gestures from **different angles and distances.**  
- Keep **both classes balanced** (same number of examples).  
- **Train for more epochs** to allow the model to learn better.  

---

## 💡 Conclusion
My model could recognize the “Thumbs up” gesture very reliably,  
but had difficulty correctly identifying “Thumbs down.”  
This project showed how strongly image quality, lighting, and data diversity affect a model’s learning ability.  
With more data and better variation, the model could become more robust and accurate in the future.

---

📅 **Author:** Burcu Kiran  
🧩 **Tool:** [Teachable Machine by Google](https://teachablemachine.withgoogle.com/)  
🕒 **Project duration:** approx. 1 hour (data collection, training, testing)



-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------


## 🎯 Projektname
**Thumbs Detector** – Erkennung von Handgesten („Daumen hoch“ 👍 / „Daumen runter“ 👎)

---

## 📝 Ziel des Projekts
Das Ziel meines Projekts war es, ein einfaches Bilderkennungsmodell zu trainieren, das zwischen den beiden Handgesten **„Daumen hoch“** und **„Daumen runter“** unterscheiden kann.  
Das Modell soll erkennen, ob eine Person Zustimmung (Daumen hoch) oder Ablehnung (Daumen runter) zeigt.

---

## ⚙️ Vorgehensweise

### 🔹 Schritte in der Teachable Machine
1. Ich habe ein **neues Bildprojekt** in der [Teachable Machine](https://teachablemachine.withgoogle.com/) erstellt.  
2. Zwei **Klassen** angelegt: `Daumen hoch` und `Daumen runter`.  
3. Für jede Klasse **Trainingsbilder mit der Webcam** aufgenommen.  
4. Anschließend das Modell **trainiert** und mit der Webcam **getestet**.  
5. Zum Schluss habe ich die **Live-Vorschau** genutzt, um die Erkennungsqualität zu überprüfen.

---

### 🔹 Datensammlung
- **Bilderquelle:** ausschließlich Webcam (keine Uploads).  
- **Anzahl der Klassen:** 2  
- **Klasse 1:** Daumen hoch 👍  
- **Klasse 2:** Daumen runter 👎  
- **Bilderanzahl:** jeweils ca. 20–25 Bilder pro Klasse.  
- **Variationen:** verschiedene Entfernungen zur Kamera, leicht unterschiedliche Handpositionen.  

---

### 🔹 Besonderheiten während der Datensammlung
- Die Lichtverhältnisse waren teilweise ungleichmäßig – helle und dunkle Bereiche haben die Erkennung beeinflusst.  
- Die Geste „Daumen runter“ war schwieriger aufzunehmen, da die Handposition ungewohnt ist und die Kamera den Daumen teilweise verdeckt hat.  
- Der Hintergrund war neutral (helle Wand), um Ablenkungen zu vermeiden.  

---

### 🔹 Training
- Das Training dauerte nur wenige Sekunden (ca. 30 – 45 s).  
- Es gab keine Fehlermeldungen oder technischen Probleme.  
- Nach dem Training zeigte das Modell sofort Live-Ergebnisse über die Webcam an.

---

## 🔬 Testergebnisse

- Das Modell konnte **„Daumen hoch“** fast immer korrekt erkennen (≈ 100 %).  
- Die Geste **„Daumen runter“** wurde jedoch deutlich seltener richtig erkannt.  
- Bei ähnlicher Handhaltung oder ungünstigem Licht wurde sie teilweise fälschlich als „Daumen hoch“ klassifiziert.  

---

## 📊 Bewertung der Zuverlässigkeit
**Gesamtbewertung:** mittel bis gut.  
- Eine der beiden Klassen war deutlich dominanter (Daumen hoch).  
- Das Modell war insgesamt stabil, aber noch nicht generalisierungsfähig genug.  

---

## 🚀 Verbesserungsvorschläge
Um die Erkennungsqualität zu verbessern, würde ich:
- **Mehr Trainingsbilder aufnehmen** (mind. 50 – 100 pro Klasse).  
- **Verschiedene Lichtverhältnisse** ausprobieren (hell, schattig, künstlich).  
- Die Geste aus **mehreren Winkeln und Entfernungen** zeigen.  
- Beide Klassen **gleichmäßig balancieren** (ähnliche Anzahl an Bildern).  
- Den **Trainingsprozess verlängern** (mehr Epochen).  

---

## 💡 Fazit
Mein Modell konnte die Geste „Daumen hoch“ sehr zuverlässig erkennen,  
hatte aber Schwierigkeiten bei „Daumen runter“.  
Das Projekt hat gezeigt, wie stark Bildqualität, Licht und Datenvielfalt die Lernleistung eines Modells beeinflussen.  
Mit mehr Trainingsdaten und besserer Variation kann das Modell künftig robuster und genauer werden.

---

📅 **Autorin:** Burcu Kiran  
🧩 **Tool:** [Teachable Machine by Google](https://teachablemachine.withgoogle.com/)  
🕒 **Projektzeit:** ca. 1 Stunde (Datenaufnahme, Training, Test)
