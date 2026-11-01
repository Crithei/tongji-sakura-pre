# Cherry Blossoms as Witness · 樱花为证
**Group presentation script · 23 slides · about 11 min 45 s · English, with Chinese key phrases**

Group members: 吕思扬 · 李欣芸 · 张弥月 · 李成蹊 · 唐家辉 · 卓虹礼

How to use the deck: open `index.html` (or the online link) and press **F** for fullscreen. Use **→ / Space** for the next slide, **N** to show these notes on screen, and **T** to start the timer (target 11:45).
Live controls: slide 15 uses **1–5** to switch analysis figures. Slide 16 uses **A / B / C** to switch the model view. Slide 17 uses **1–5** to switch seasons. Slide 18 plays the AR recording; click a chapter to jump. Slide 19 is the QR code for the audience to try it. **R** turns auto-rotate on and off.

> Total ≈ 1593 words of narration. **Bold** = stress. `[ ]` = action cue. Chinese lines are read in Chinese.
> Suggested split for six speakers: Opening & history (01–05) · Site & significance (06–09) · Modelling (10–12) · Records & analysis (13–15) · Twin, seasons & AR (16–19) · Interpretation & close (20–23).

---

## 01 · Title — 0:30
*Cherry Blossoms as Witness*

Good morning. Our project is about a tree you've probably walked past many times: the **cherry trees on Aixiao Road**. Our title comes from four characters carved on a stone beneath them: **樱花为证**, "cherry blossoms as witness". We'll show what these trees witness, how we read their **site**, how we built a **digital twin** of one of them, and how AR lets us see it in **every season**.

## 02 · The object · 遗产对象 — 0:30
*It is November. The tree is bare.*

Today is November, and the trees outside are **bare**. Sakura Avenue blooms for about two weeks a year. For the other fifty, its meaning is invisible. That gap is our design problem.
The avenue began with about **100 saplings in 1997** and has grown to **more than 200 trees**. On this campus plan, our study corridor is the pink strip: **33 trees**, with **one sample tree** as the twin.

## 03 · History · 历史溯源 — 0:35
*A gift, a deadline, and a domestic substitute.*

The school archives had almost nothing on these trees, so we rebuilt their history from **newspapers, alumni newsletters and oral history**.
In 1996, the School of Computer Science partnered with the Japanese company **CSK**. For Tongji's **90th anniversary** in 1997, CSK gifted 100 cherry trees. One detail surprised us: importing them from Japan would have missed the anniversary, so the saplings were actually **bought in China**. They were planted on **20 May 1997**.

## 04 · The inscription · 碑文 — 0:20
**

`[pause, let the slide land]`
This is the stone: **樱花为证，中日友好，世代为继**. "Cherry blossoms as witness. China–Japan friendship, carried on through generations."
The key word is **witness**. These trees were not planted as decoration. They were asked to **remember** something.

## 05 · Living memory · 校园记忆 — 0:30
**

And people keep coming back. The former dean who signed the 1996 agreement says: "**These trees are like my children.**" He visits every spring. Here he is with his wife in 2024.
In 2014, a retired couple photographed seven graduates under the blossoms and wrote to the university to find them. A Weibo post found them **within two hours**. The avenue has become a stage for graduation, return and kindness.

## 06 · Site · 场地平面 — 0:35
*Thirty-three trees, one corridor.*

Now we zoom in from the campus to the grove. We counted **33 trees** in our study corridor: **18** on the tennis-court side and **15** on the football-field side. On the tennis-court side they stand about **5 metres** apart, so the row runs for about **85 metres**. The two rows are about **12.5 metres** apart, measured from the campus CAD drawing.
The tree we modelled is **T01**, the first tree of the right-hand row, near Nan Avenue.

## 07 · Site · 空间关系 — 0:30
*A street beneath the trees.*

This is section A–A across the corridor. The two rows of cherries turn an ordinary road into a **linear space**. Walkers and cyclists **share the centre**, and in spring the two crowns almost **meet over the road**. At the edges, shrubs and benches give people a place to **pause**.
This is a qualitative reading from the CAD drawing and our photos. We did not count traffic, and the heights in the section are schematic.

## 08 · Site · 植物群落 — 0:30
*Three layers under one canopy.*

Under the cherries there are **three planting layers**. The canopy is the cherry itself. Below it is an **evergreen shrub layer**, with Euonymus and a Viburnum hedge on both sides. On the ground there is **Ophiopogon**, and **Orychophragmus**, which flowers purple at the same time as the cherries.
At the bottom is the **rhythm** of the rows: 18 trees at even spacing on one side, 15 on the other. Plant names come from our field report and the tree label; they are not botanically verified.

## 09 · Significance assessment · 价值评估 — 0:35
*Four values, one avenue.*

To assess significance, we used the **Burra Charter's** four values.
**Historic** value is strongest: the avenue is dated, documented and inscribed. **Social** value is equally strong, because people renew its meaning every spring. **Aesthetic** value is high but brief. **Scientific** value is emerging: with a known planting date, the trees are a baseline for monitoring.
One honest finding: the sources **disagree on the species**. A city report says Somei Yoshino, but the label on the tree reads **日本早樱**, Prunus subhirtella. We leave this open for fieldwork.

## 10 · Digital twin · 建模流程 — 0:40
*From a partial scan to a traceable tree.*

Here is how we built the twin. We started from **three kinds of field data**: a 3D scan mesh of the trunk, **eight photographs**, and tape measurements of the girth.
The scan only captured the **lower part** of the tree, so we worked in layers. First, we **kept the scan untouched**: 16,894 triangles. Then we **patched** the holes from cross-sections. Then we **rebuilt the crown**: 6 axes fitted to the scan, 50 limbs read from photos, and about 1,500 twigs generated by rules. Finally, a light web model drives the **seasons and the AR**.

## 11 · Reconstruction · 分层重建 — 0:35
*Five steps, from a stump of data to a full crown.*

This slide shows the reconstruction step by step. On the left is all the scan gave us: the **trunk and a few limbs**. We then add 6 axes fitted to the scan, 50 limbs we read from the photographs, and finally about **1,500 twigs and shoots** generated by rules.
The bars are an honest warning. By count and by length, most of the crown is **rule-generated**: **70.6 percent** of the summed axis length. So the big structure is evidence, but the fine twigs are **interpretation**.

## 12 · Evidence layers · 证据分层 — 0:30
*Every branch says where it came from.*

Because so much is reconstructed, we kept **every source on its own layer**. Dark green is the **original scan**. Light green is **surface repair**. Pink limbs were **traced from photos**. The pale twigs are **generated by rules**.
On the left is the field photograph we compared against. The colours show **where each part came from**, not how accurate it is. This follows the **London Charter**: a heritage visualisation should keep its interpretation visible.

## 13 · Drawn record · 正投影图纸 — 0:30
*The twin as a set of drawings.*

A heritage record should also be **drawable**. These are direct projections of the model: a **plan** and two **elevations**. The crown spans about 7.5 by 8.6 metres, and the highest point is at 6.87 metres.
On the right are horizontal sections cut straight through the mesh. At ground level the root collar is **irregular**; by 70 centimetres the trunk has **split into two stems**. These are model readings, and the axes are not yet oriented to north.

## 14 · Measurement ledger · 尺寸台账 — 0:35
*Measured, modelled, and still unknown.*

We keep three columns apart. **Measured**: the base girth is about 120 centimetres, which gives an equivalent diameter of 38 centimetres. **Modelled**: the highest point is 6.87 metres, and the branch framework leans **2.19 metres** off the root, so the crown is strongly **asymmetric**.
And **unknown**: the true height, the crown spread oriented to north, and the standard diameter at breast height. At the bottom, the scan points of stem A show why: low down the trunk is **not round**, so a fitted circle is off by up to 13 centimetres.

## 15 · Structural analysis · 结构分析 — 0:45
*Reading the architecture of one tree.*

With the axes in a table, we can analyse the tree's architecture. `[1]` The **orientation rose**: branch length peaks in one sector, but the model is not oriented to north yet, so we make no claim about sunlight. `[2]` By **height**, most branch length sits between **3.5 and 4 metres**. `[3]` The **density maps** show where branches cluster and where there are gaps. `[4]` The **footprint** of the crown framework is 33 square metres, with its centre 2.2 metres off the trunk. `[5]` And we checked the main forks against **field photos** from similar angles.

## 16 · Inside the twin · 模型解读 — 0:25
*Three ways to read a tree.*

`[drag to rotate]` This is the twin, live.
`[A]` The surface keeps the bark's **original colour**. `[B]` The wireframe is the **geometric record**. `[C]` The skeleton: the pink lines are the **56 scan-fitted and photo-read limbs**, and the light lines are the **1,566 rule-based twigs**. This branching is **29 years of growth**, and it is the base the seasons are built on.

## 17 · Four seasons · 四季 — 0:35
**

It's November, but with the twin we can **bring back spring**.
`[2]` About **4,700 five-petal blossoms**, each placed on a twig axis. `[3]` Summer: individual leaves. `[4]` Autumn: the leaves turn yellow and orange and thin out. `[5]` Winter: bare branches, which is what you'd see outside **today**.
To be clear about the method: the seasons are a **display simulation**, not measured phenology. **The structure is evidence. The seasons are interpretation.**

## 18 · AR in use · 实机演示 — 0:35
*On the phone, in place.*

`[video plays]` First, here is the AR working on a phone. We open the page, point the camera at the **emblem**, and the bare tree appears on it. Then we switch: **spring**, **summer**, **autumn**, **winter**, all without leaving the camera.
The tree stays **anchored** as the phone moves. What we still need to test is **outdoor light**, a printed emblem on site, and older phones. And now, you can try it yourselves.

## 19 · Augmented reality · 增强现实 — 0:30
*The emblem is the anchor.*

`[point to QR]` Now it's your turn. Scan this code: it opens in the browser, with **no app to install**. Point your phone at the emblem on the slide, and the tree appears; then switch seasons yourself.
Why the emblem? It was a deliberate choice. The trees exist because of the university's anniversary, so it felt right that the university's own symbol **calls them back**.
`[leave the slide up ≈ 20 s while people scan]`

## 20 · Interpretation · 阐释策略 — 0:30
*Four layers of time in one tree.*

To bring it together, we read the tree as **four layers of time**. **The gift**: one moment in 1997. **The ritual**: every spring. **The growth**: 29 years, recorded in the skeleton. **The witness**: any day, through AR.
Our principle: **real structure, simulated seasons, documented stories**, and each layer says which one it is.

## 21 · Honest boundaries · 解释边界 — 0:35
*What the model can, and cannot, claim.*

Before we close, we want to be clear about what this model **can and cannot claim**. The twin stems come from the scan, so they are **evidence**. But most of the fine crown is **rule-generated**, the crown is not yet oriented to north, and the trunk base is not round.
So our next fieldwork has priorities: first **scale**, meaning true height, crown spread and girth heights; then **form**, meaning photos of hidden sides; and only then the **display**. New evidence comes before more decorative leaves.

## 22 · Reflection · 反思与展望 — 0:25
*Where it goes next.*

Where does it go next? The seasons need calibration with real **phenology data**. The species needs **botanical verification**. We'd scale from one tree to all **33 trees** in the corridor, then the avenue, and add these voices as an **audio layer** in AR.
The stone says **世代为继**, "carried on through generations". A digital twin is one way to carry it on. **Thank you.**

## 23 · Appendix · 参考资料 — 0:00
*Sources and methods.*

Appendix: keep this slide up during questions.

---

## Before presenting · 上台前检查
- [ ] **Check the image sources.** Feishu photos are credited on the slides; the Xuan Guorong 2024 photo is from Xiaohongshu @诺坎普の猫. Site plans come from the campus CAD file; modelling figures come from our analysis set.
- [ ] **Check the AR recording slide (18).** It plays automatically and loops. Chapter jumps need the online link or a double-clicked local file. A plain local `python -m http.server` cannot seek.
- [ ] **Test on the classroom computer.** Wait for the model to load (about 3–5 s). With no internet, the fonts fall back to system fonts but everything else works.
- [ ] **Charge your phone and print the emblem target** (`assets/emblem-target.jpg`), or show it on a second screen for the live AR demo. On slide 19, leave the QR up for about 20 s; if the audience's phones struggle, point back to the recording on slide 18.

## 可能的提问 · Likely questions
- **Was the tree laser-scanned?** We started from an existing scan mesh (.fbx) of the lower trunk. The file does not record the device, so we do not call it TLS. The crown was completed from 8 photos and rules, and each source is on its own layer.
- **How much of the model is real?** The root collar, twin stems and some limbs are scan geometry (16,894 triangles, kept untouched). 56 limbs are scan-fitted or photo-read. About 70% of the summed axis length is rule-generated twigs.
- **Why only one tree?** It is a sample. One tree proves the pipeline, and the layered method can be repeated for all 33 trees in the corridor.
- **How accurate are the dimensions?** The 6.87 m height and 7.47 × 8.56 m span are model readings. True height, north-oriented crown spread and DBH still need field survey; the base girth is 120 cm by tape.
- **How accurate are the seasons?** The branches are reconstructed; blossom and leaf counts and colours are illustrative, and we say so on the slide.
- **Why the emblem as the target?** It is meaningful, because the trees were an anniversary gift. It is also practical: it is high-contrast, appears everywhere on campus, and is easy to print.
