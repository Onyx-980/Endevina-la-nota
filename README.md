# 🎵 Entrenament Musical · Endevina la nota

Aplicació web interactiva creada per a **estudiants de música** per practicar l'entrenament auditiu, el reconeixement d'intervals, la lectura rítmica i els dictats melòdics curts des de qualsevol dispositiu.

## 🔗 Prova l'aplicació en línia (Netlify)
L'aplicació està allotjada a **Netlify** i funciona directament al navegador sense necessitat d'instal·lar res:
* 👉 **[Obrir l'aplicació al mòbil, tauleta o ordinador](https://endevina-la-nota0.netlify.app)**

## 🎼 Modes d'entrenament inclosos
1. **🎵 Nota i ritme (nivell elemental):**
   * Reconeixement de les notes naturals de **Do 3 a Do 4** (`Do, Re, Mi, Fa, Sol, La, Si, Do agut`).
   * Identificació de patrons rítmics bàsics: **negra, dues corxeres, blanca i blanca amb punt**.
2. **📏 Intervals:**
   * Pràctica d'intervals des de la **2a fins a la 8a**.
   * Selector per triar entre intervals **melòdics** (notes seguides) o **harmònics** (notes alhora).
3. **🎼 Dictat melòdic:**
   * Dictats curts de **3, 4 o 5 notes** (començant sempre pel **Do** com a nota de referència tonal).
   * Botó per esborrar l'última nota introduïda abans de validar la resposta (`⌫ Esborra l'última`).

## 🛠️ Eines musicals i característiques tècniques
* **Afinació de referència:** `La = 442 Hz` amb botó dedicat per escoltar la nota de referència en qualsevol moment.
* **Pulsació i metrònom:** `Negra = 60 BPM` amb metrònom activable o desactivable (`SÍ / NO`) sincronitzat amb cada exercici.
* **Controls d'àudio i feedback:** Botons per generar un **Nou exercici** o **Repetir** l'audició, juntament amb un comptador d'encerts en temps real.
* **Tecnologia:** Desenvolupada en un únic fitxer autònom (**HTML5, CSS3 i JavaScript**) amb síntesi d'àudio WAV en temps real sense dependències externes.

## 🚀 Desplegament i ús en local
Com que es tracta d'una aplicació estàtica en un únic fitxer autònom, és molt fàcil d'executar o desplegar:

* **En local:** Descarrega o clona el repositori i obre el fitxer `index.html` directament a qualsevol navegador web.
* **A Netlify:** Connecta el repositori de GitHub a [Netlify](https://netlify.com) (sense necessitat de *build command*) o arrossega la carpeta del projecte directament a l'àrea de desplegament manual (*Netlify Drop*).

## 📈 Historial de versions
* **Versió 3 (actual):** Incorporació del selector de 3 modes (*Nota i ritme*, *Intervals* melòdics/harmònics i *Dictats* de 3 a 5 notes).
* **Versió 2:** Afegit el botó de referència `La 442 Hz` i el metrònom activable a `negra = 60`.
* **Versió 1:** Llançament inicial amb reconeixement de notes (Do 3 – Do 4) i 4 figures rítmiques.

---
Creat per **@LorenMoya**
