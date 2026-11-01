# Cherry Blossoms as Witness · 樱花为证
**Oral presentation script · 6 min 40 s (400 s) · single presenter**

How to use the deck: open `index.html` and press **F** for fullscreen. Use **→ / Space** for the next slide, **N** to show these notes on screen, and **T** to start the 400-second timer.
Live controls: slide 8 uses **A / B / C** to switch the model view. Slide 9 uses **1–5** to switch seasons. **R** turns auto-rotate on and off.

> Total ≈ 750 words. That is about 5:30 at a normal pace, or about 6:10 at a slower, careful pace, leaving time for the live AR moment and pauses.
> **Bold** = stress. `[ ]` = action cue. Chinese lines are read in Chinese.

---

## 01 · Title — 0:25
Good morning. My project is about a tree you've probably walked past many times: the **cherry trees on Aixiao Road**. My title comes from four characters carved on a stone beneath them: **樱花为证**, "cherry blossoms as witness". In the next six minutes I'll show what these trees witness, how I built a **digital twin** of one of them, and how AR lets us see it in **every season**.

## 02 · The object — 0:30
Today is November, and the trees outside are **bare**. Sakura Avenue blooms for about two weeks a year. For the other fifty, its meaning is invisible. That gap is my design problem.
The avenue began with about **100 saplings in 1997** and has grown to **more than 200 trees**. My scope is **one sample tree** as the twin, with the avenue and the memorial stone as its setting.

## 03 · History — 0:35
The school archives had almost nothing on these trees, so I rebuilt their history from **newspapers, alumni newsletters and oral history**.
In 1996, the School of Computer Science partnered with the Japanese company **CSK**. For Tongji's **90th anniversary** in 1997, CSK gifted 100 cherry trees. One detail surprised me: importing them from Japan would have missed the anniversary, so the saplings were actually **bought in China**. They were planted on **20 May 1997**.

## 04 · The inscription — 0:20
`[pause, let the slide land]`
This is the stone: **樱花为证，中日友好，世代为继**. "Cherry blossoms as witness. China–Japan friendship, carried on through generations."
The key word is **witness**. These trees were not planted as decoration. They were asked to **remember** something.

## 05 · Living memory — 0:30
And people keep coming back. The former dean who signed the 1996 agreement says: "**These trees are like my children.**" He visits every spring. Here he is with his wife in 2024.
In 2014, a retired couple photographed seven graduates under the blossoms and wrote to the university to find them. A Weibo post found them **within two hours**. The avenue has become a stage for graduation, return and kindness.

## 06 · Significance — 0:35
To assess significance, I used the **Burra Charter's** four values.
**Historic** value is strongest: the avenue is dated, documented and inscribed. **Social** value is equally strong, because people renew its meaning every spring. **Aesthetic** value is high but brief. **Scientific** value is emerging: with a known planting date, the trees are a baseline for monitoring.
One honest finding: the sources **disagree on the species**. A city report says Somei Yoshino, but the label on the tree reads **日本早樱**, Prunus subhirtella. I leave this open for fieldwork.

## 07 · Digital-twin workflow — 0:30
Here is the workflow. I captured the tree while it was **leafless**, so every branch was visible. I rebuilt the trunk and branches in **Rhino**, then extracted **1,622 branch centre-lines**.
That step matters: leaves and blossoms later grow on the **real twigs**, not at random. The result has about **440,000 triangles**, a height of **6.9 metres**, and a crown about **7.5 by 8.6 metres**, all in a 12-megabyte web model.

## 08 · Inside the twin — 0:25
`[drag to rotate]` This is the twin, live.
`[A]` The surface keeps the bark's **original colour**. `[B]` The wireframe is the **geometric record**. `[C]` The skeleton: the pink lines are the **56 primary limbs**, and the dark lines are over **1,500 twigs**. This branching is **29 years of growth**, and it is the base the seasons are built on.

## 09 · Four seasons — 0:35
It's November, but with the twin I can **bring back spring**.
`[2]` About **4,700 five-petal blossoms**, each placed on a real twig. `[3]` Summer: individual leaves. `[4]` Autumn: the leaves turn yellow and orange and thin out. `[5]` Winter: bare branches, which is what you'd see outside **today**.
To be clear about the method: the seasons are a **display simulation**, not measured phenology. **The structure is real. The seasons are interpretation.**

## 10 · Augmented reality — 0:35
For AR, I made a deliberate choice: the image target is the **Tongji emblem**. The trees exist because of the university's anniversary, so it felt right that the university's own symbol **calls them back**.
`[point to QR]` You can scan this now. It opens in the browser, with **no app to install**. Point it at the emblem, and the tree appears; then switch seasons on the spot.
`[LIVE DEMO ≈ 15 s on phone. If it fails, keep talking over the phone mock-up on the slide.]`

## 11 · Interpretation — 0:30
To bring it together, I read the tree as **four layers of time**. **The gift**: one moment in 1997. **The ritual**: every spring. **The growth**: 29 years, recorded in the skeleton. **The witness**: any day, through AR.
My principle: **real structure, simulated seasons, documented stories**, and each layer says which one it is.

## 12 · Reflection & thanks — 0:25
Finally, what the twin **cannot yet say**. The seasons need calibration with real **phenology data**. The species needs **botanical verification**. Next, I'd scale from one tree to the **whole avenue** and add these voices as an **audio layer** in AR.
The stone says **世代为继**, "carried on through generations". A digital twin is one way to carry it on. **Thank you.**

---

## Before presenting · 上台前检查
- [ ] **Check slide 07, step 01.** The deck says the tree was captured by "photographs around the leafless trunk → Rhino". If you actually used LiDAR or another method, change the wording to match.
- [ ] **Check slide 02's plan.** It is a schematic, not a survey. Replace it with a real campus map or site photo if you have one.
- [ ] **Check the image sources.** The photos come from the Feishu research notes and are credited on the slides. The Xuan Guorong 2024 photo is from Xiaohongshu @诺坎普の猫.
- [ ] **Test on the classroom computer.** Double-click `index.html` and wait for the model to load (about 3–5 s). With no internet, the fonts fall back to system fonts but everything else works.
- [ ] **Charge your phone and print the emblem target** (`assets/emblem-target.jpg`), or show it on a second screen for the AR demo.
- [ ] **Record a 15-second backup clip** of the AR working, in case the camera or network fails.

## 可能的提问 · Likely questions
- **Why only one tree?** It is a sample. One tree is enough to prove the pipeline, and the 1,622-axis skeleton is a reusable structure for scaling to the avenue.
- **How accurate are the seasons?** The branches are reconstructed from the real tree. The blossom and leaf counts and colours are illustrative, and I say so on the slide.
- **Why web AR instead of an app?** It needs zero installation, so anyone on campus can use it. It also works offline and runs on both iPhone and Android.
- **Why the emblem as the target?** It is meaningful, because the trees were an anniversary gift. It is also practical: the emblem is high-contrast, appears everywhere on campus, and is easy to print.
