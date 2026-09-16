# AI Style Reverse-Engineer ULTRA — The Ultimate AI Style Architect Matrix Widget

AI Style Reverse-Engineer ULTRA is a lightweight, zero-dependency, browser-based **AI Style Architect Matrix Widget** for creators, developers, prompt engineers, AI-art communities, bloggers, and website owners who want to organize visual characteristics into structured AI image-generation prompts.

**Canonical Production URL:**  
https://promptflip.netlify.app

**Developer Article / Secondary Backlink Context:**  
https://dev.to/dev_alex_matrix/building-a-zero-dependency-cyberpunk-ai-prompt-widget-for-website-sidebars-full-source-code-23aa

---

## 🚀 Production Application

Use the live **AI Style Reverse-Engineer ULTRA** application:

https://promptflip.netlify.app

The project is designed around a simple workflow:

```text
Visual Reference
      ↓
Style Observation
      ↓
AI Style Architecture Matrix
      ↓
Structured Prompt
      ↓
Copy / Share / Refine
```

---

## 🔎 What Is AI Style Reverse-Engineer ULTRA?

AI Style Reverse-Engineer ULTRA is a client-side prompt-engineering interface that organizes visual generation characteristics into independent architectural layers.

Instead of manually constructing one long AI image prompt, users can work through individual visual dimensions such as:

- Subject
- Composition
- Camera
- Lens
- Lighting
- Environment
- Materials
- Color architecture
- Atmosphere
- Fashion and styling
- Detail density
- Rendering direction
- Negative constraints

The resulting structured prompt can be used as a starting point for experimentation with Midjourney and other AI image-generation workflows.

The tool is intended for visual analysis and prompt construction rather than claiming to recover an original proprietary prompt from an image.

---

# 🎯 Core Search Use Cases

## Reverse-engineer Midjourney prompts from image

AI Style Reverse-Engineer ULTRA provides a structured workflow for analyzing observable visual characteristics and translating those observations into organized prompt components.

The process can help users experiment with:

- Camera language
- Lens characteristics
- Lighting
- Composition
- Color
- Materials
- Environment
- Atmosphere
- Rendering characteristics
- Negative constraints

Production application:

https://promptflip.netlify.app

---

## Midjourney style architecture tool

The **Midjourney style architecture tool** concept behind this project treats an image prompt as a collection of visual layers rather than an unstructured paragraph.

Each layer can be modified independently, allowing creators to experiment with the relationship between:

```text
Subject
+
Composition
+
Camera
+
Lens
+
Lighting
+
Environment
+
Materials
+
Color
+
Atmosphere
+
Styling
+
Detail
+
Rendering
+
Negative Constraints
```

---

## Free client-side prompt previewer

AI Style Reverse-Engineer ULTRA functions as a **Free client-side prompt previewer** using browser-native HTML, CSS, and JavaScript.

The included implementation does not require:

- React
- Vue
- Angular
- Node.js
- Database infrastructure
- Server-side rendering
- An AI API key
- A backend server

The prompt-preview engine operates locally in the browser.

---

# ✨ Features

- Zero external framework dependencies
- Standalone HTML implementation
- Cyberpunk-inspired interface
- Responsive mobile-first design
- 360px sidebar compatibility
- Prompt architecture matrix
- Client-side prompt generation
- Copy-to-clipboard support
- Browser-native Web Share API support
- Prompt word counter
- Character counter
- Reset functionality
- Responsive two-column desktop interface
- Single-column mobile interface
- Ghost HTML embedding support where custom HTML is permitted
- XenForo custom-widget compatibility where HTML/JavaScript is permitted
- Static-hosting compatibility
- Netlify-compatible deployment
- Production URL configured as `https://promptflip.netlify.app`

---

# 🧠 AI Style Architect Matrix

| Architecture Layer | Function |
|---|---|
| Subject | Defines the primary visual subject |
| Composition | Defines framing and arrangement |
| Camera | Establishes camera character |
| Lens | Defines optical perspective |
| Lighting | Establishes illumination |
| Environment | Defines surroundings |
| Materials | Defines surface characteristics |
| Color | Establishes palette and tonal direction |
| Atmosphere | Establishes environmental depth |
| Fashion | Defines styling and wardrobe |
| Detail | Controls visual detail density |
| Rendering | Defines final rendering characteristics |
| Negative | Defines unwanted characteristics |

---

# ⚡ Why Client-Side?

The core widget intentionally keeps its architecture simple.

```text
HTML
  +
CSS
  +
Vanilla JavaScript
  =
Standalone AI Prompt Widget
```

This makes the source easy to inspect, customize, embed, fork, and deploy.

The production application is available at:

https://promptflip.netlify.app

---

# 📱 360px Website Sidebar Installation

The interface includes responsive CSS specifically designed to remain usable in narrow website containers.

For a standard approximately **360px-wide sidebar**:

1. Copy the complete source from the **Production Source Code** section below.
2. Open the website's Custom HTML or HTML Widget editor.
3. Paste the complete source.
4. Save the widget.
5. Open the published page.
6. Test the interface at approximately 360px width.

The included media queries automatically change the desktop layout into a mobile-friendly single-column layout.

---

# 👻 Ghost Blog Installation

On a Ghost installation where custom HTML is permitted:

1. Create or edit a post or page.
2. Add an HTML card.
3. Copy the complete Production Source Code below.
4. Paste the source into the HTML card.
5. Preview the page.
6. Publish when the widget renders correctly.

Ghost configurations can restrict scripts or custom markup, so the site's configured HTML policy determines whether inline JavaScript is permitted.

Production application:

https://promptflip.netlify.app

---

# 🦊 XenForo Installation

For XenForo installations that permit custom HTML and JavaScript:

1. Open the permitted XenForo administration/customization interface.
2. Create the appropriate custom widget or HTML container.
3. Copy the complete Production Source Code below.
4. Paste the source.
5. Save the widget.
6. Test it from the member-facing page.

If a XenForo configuration sanitizes `<script>` or `<style>` elements, place those resources in the platform's permitted custom-resource areas and retain the HTML structure in the widget container.

---

# 🏗️ Production Source Code

The following is a complete standalone HTML document containing the CSS and JavaScript required by the widget.

Copy the entire block without removing any section.

```html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="description" content="AI Style Reverse-Engineer ULTRA - free client-side AI style architecture and prompt preview widget.">
<meta name="robots" content="index,follow">
<title>AI Style Reverse-Engineer ULTRA</title>

<style>
:root{
  --bg:#05050a;
  --panel:#0b0b14;
  --panel2:#10101c;
  --border:#292943;
  --text:#f5f5ff;
  --muted:#9292ad;
  --accent:#a855f7;
  --accent2:#22d3ee;
  --danger:#fb7185;
  --shadow:0 18px 55px rgba(0,0,0,.45);
}

*{
  box-sizing:border-box;
}

html{
  scroll-behavior:smooth;
}

body{
  margin:0;
  background:
    radial-gradient(circle at 20% 0%,rgba(168,85,247,.15),transparent 30%),
    radial-gradient(circle at 90% 20%,rgba(34,211,238,.1),transparent 28%),
    var(--bg);
  color:var(--text);
  font-family:Inter,system-ui,-apple-system,BlinkMacSystemFont,"Segoe UI",sans-serif;
  min-height:100vh;
}

button,
input,
textarea,
select{
  font:inherit;
}

button{
  cursor:pointer;
}

.app{
  width:min(1100px,100%);
  margin:auto;
  padding:16px;
}

.header{
  border:1px solid var(--border);
  background:linear-gradient(145deg,rgba(16,16,28,.96),rgba(7,7,13,.96));
  border-radius:22px;
  padding:22px;
  box-shadow:var(--shadow);
  position:relative;
  overflow:hidden;
}

.header:before{
  content:"";
  position:absolute;
  inset:0;
  pointer-events:none;
  background:
    linear-gradient(90deg,transparent 49%,rgba(168,85,247,.04) 50%,transparent 51%);
  background-size:28px 28px;
}

.badge{
  display:inline-flex;
  align-items:center;
  gap:7px;
  border:1px solid rgba(168,85,247,.45);
  background:rgba(168,85,247,.1);
  color:#d8b4fe;
  border-radius:999px;
  padding:6px 10px;
  font-size:11px;
  font-weight:800;
  letter-spacing:.08em;
  text-transform:uppercase;
}

h1{
  margin:14px 0 8px;
  font-size:clamp(27px,5vw,48px);
  line-height:1;
  letter-spacing:-.04em;
}

.gradient{
  background:linear-gradient(90deg,#d8b4fe,#67e8f9);
  -webkit-background-clip:text;
  background-clip:text;
  color:transparent;
}

.subtitle{
  color:var(--muted);
  line-height:1.65;
  max-width:800px;
  margin:0;
}

.grid{
  display:grid;
  grid-template-columns:360px minmax(0,1fr);
  gap:16px;
  margin-top:16px;
}

.card{
  border:1px solid var(--border);
  background:rgba(11,11,20,.92);
  border-radius:20px;
  padding:18px;
  box-shadow:var(--shadow);
}

.card-title{
  display:flex;
  justify-content:space-between;
  align-items:center;
  gap:12px;
  margin-bottom:15px;
}

.card-title strong{
  font-size:14px;
}

.status{
  color:#67e8f9;
  font-size:10px;
  font-weight:800;
  letter-spacing:.08em;
  text-transform:uppercase;
}

.field{
  margin-bottom:14px;
}

.field:last-child{
  margin-bottom:0;
}

label{
  display:block;
  color:#c4c4d8;
  font-size:11px;
  font-weight:800;
  letter-spacing:.04em;
  margin-bottom:7px;
  text-transform:uppercase;
}

input,
textarea,
select{
  width:100%;
  border:1px solid var(--border);
  outline:none;
  border-radius:12px;
  background:#070710;
  color:var(--text);
  padding:11px 12px;
  transition:.2s ease;
}

input:focus,
textarea:focus,
select:focus{
  border-color:rgba(168,85,247,.8);
  box-shadow:0 0 0 3px rgba(168,85,247,.1);
}

textarea{
  resize:vertical;
  min-height:90px;
  line-height:1.55;
}

.range-row{
  display:flex;
  align-items:center;
  gap:10px;
}

input[type="range"]{
  padding:0;
  accent-color:var(--accent);
}

.range-value{
  min-width:42px;
  text-align:right;
  color:#d8b4fe;
  font-weight:800;
  font-size:12px;
}

.actions{
  display:grid;
  grid-template-columns:1fr 1fr;
  gap:9px;
  margin-top:15px;
}

.btn{
  border:1px solid var(--border);
  border-radius:12px;
  background:#10101b;
  color:#fff;
  padding:11px 12px;
  font-size:12px;
  font-weight:800;
  transition:.2s ease;
}

.btn:hover{
  transform:translateY(-1px);
  border-color:#515170;
}

.btn.primary{
  background:linear-gradient(135deg,#7e22ce,#a855f7);
  border-color:#a855f7;
}

.btn.cyan{
  background:linear-gradient(135deg,#0891b2,#06b6d4);
  border-color:#22d3ee;
}

.matrix{
  display:grid;
  grid-template-columns:repeat(2,minmax(0,1fr));
  gap:9px;
  margin-bottom:14px;
}

.matrix-item{
  border:1px solid #202035;
  background:#080811;
  border-radius:12px;
  padding:10px;
}

.matrix-item small{
  display:block;
  color:#777792;
  font-size:9px;
  text-transform:uppercase;
  font-weight:800;
  letter-spacing:.08em;
  margin-bottom:4px;
}

.matrix-item span{
  color:#d8d8e8;
  font-size:11px;
  line-height:1.4;
}

.prompt-box{
  position:relative;
}

.prompt-box textarea{
  min-height:360px;
  padding-right:45px;
  font-family:"SFMono-Regular",Consolas,monospace;
  font-size:12px;
  line-height:1.7;
}

.copy-mini{
  position:absolute;
  top:9px;
  right:9px;
  width:32px;
  height:32px;
  border-radius:9px;
  border:1px solid var(--border);
  background:#141423;
  color:#fff;
}

.counter{
  display:flex;
  justify-content:space-between;
  gap:10px;
  margin-top:8px;
  color:#73738e;
  font-size:10px;
}

.share-box{
  margin-top:14px;
  border:1px dashed #35354e;
  border-radius:13px;
  padding:12px;
  background:#080811;
}

.share-text{
  color:#aaaac0;
  font-size:11px;
  line-height:1.6;
}

.link{
  color:#67e8f9;
  text-decoration:none;
  word-break:break-all;
}

.footer{
  text-align:center;
  color:#68687e;
  font-size:10px;
  line-height:1.6;
  padding:18px 8px 5px;
}

@media(max-width:760px){
  .grid{
    grid-template-columns:1fr;
  }

  .matrix{
    grid-template-columns:1fr 1fr;
  }
}

@media(max-width:390px){
  .app{
    padding:9px;
  }

  .header,
  .card{
    border-radius:16px;
  }

  .header{
    padding:16px;
  }

  .card{
    padding:13px;
  }

  .matrix{
    grid-template-columns:1fr;
  }

  .actions{
    grid-template-columns:1fr;
  }

  h1{
    font-size:29px;
  }
}
</style>
</head>

<body>

<div class="app">

  <header class="header">
    <span class="badge">AI STYLE ARCHITECT MATRIX</span>

    <h1>
      AI Style
      <span class="gradient">Reverse-Engineer ULTRA</span>
    </h1>

    <p class="subtitle">
      Build structured AI image prompts from visual style observations using a free
      client-side prompt architecture engine.
    </p>
  </header>

  <main class="grid">

    <section class="card">

      <div class="card-title">
        <strong>STYLE INPUT MATRIX</strong>
        <span class="status">CLIENT-SIDE</span>
      </div>

      <div class="field">
        <label for="subject">Subject</label>
        <input id="subject" value="cinematic futuristic portrait">
      </div>

      <div class="field">
        <label for="composition">Composition</label>
        <select id="composition">
          <option>centered hero composition</option>
          <option>rule of thirds</option>
          <option>symmetrical editorial composition</option>
          <option>dynamic diagonal composition</option>
          <option>wide environmental composition</option>
          <option>close-up portrait composition</option>
        </select>
      </div>

      <div class="field">
        <label for="camera">Camera</label>
        <select id="camera">
          <option>cinematic full-frame camera</option>
          <option>high-end digital cinema camera</option>
          <option>medium format camera</option>
          <option>editorial studio camera</option>
          <option>documentary camera aesthetic</option>
        </select>
      </div>

      <div class="field">
        <label for="lens">Lens</label>
        <select id="lens">
          <option>85mm portrait lens</option>
          <option>35mm cinematic lens</option>
          <option>50mm natural perspective lens</option>
          <option>24mm wide-angle lens</option>
          <option>135mm compressed portrait lens</option>
        </select>
      </div>

      <div class="field">
        <label for="lighting">Lighting</label>
        <select id="lighting">
          <option>dramatic volumetric lighting</option>
          <option>soft cinematic key light</option>
          <option>neon rim lighting</option>
          <option>golden-hour directional light</option>
          <option>high-contrast studio lighting</option>
          <option>moody low-key lighting</option>
        </select>
      </div>

      <div class="field">
        <label for="environment">Environment</label>
        <input id="environment" value="luxury futuristic architectural environment">
      </div>

      <div class="field">
        <label for="materials">Materials</label>
        <input id="materials" value="polished metal, glass, stone and premium fabric">
      </div>

      <div class="field">
        <label for="color">Color Architecture</label>
        <input id="color" value="deep black, violet, cyan highlights and controlled gold">
      </div>

      <div class="field">
        <label for="atmosphere">Atmosphere</label>
        <input id="atmosphere" value="subtle atmospheric haze with cinematic depth">
      </div>

      <div class="field">
        <label for="fashion">Fashion / Styling</label>
        <input id="fashion" value="luxury contemporary ceremonial styling">
      </div>

      <div class="field">
        <label for="detail">Detail Density</label>

        <div class="range-row">
          <input id="detail" type="range" min="1" max="10" value="8">
          <span id="detailValue" class="range-value">8/10</span>
        </div>
      </div>

      <div class="field">
        <label for="negative">Negative Constraints</label>
        <textarea id="negative">blurry, distorted anatomy, low detail, oversaturated colors, watermark, text artifacts</textarea>
      </div>

      <div class="actions">
        <button class="btn primary" id="generate">GENERATE</button>
        <button class="btn" id="reset">RESET</button>
      </div>

    </section>

    <section class="card">

      <div class="card-title">
        <strong>REVERSE-ENGINEERED PROMPT</strong>
        <span class="status" id="status">READY</span>
      </div>

      <div class="matrix" id="matrix"></div>

      <div class="prompt-box">
        <textarea id="output" readonly></textarea>
        <button class="copy-mini" id="copyPrompt" title="Copy prompt">⧉</button>
      </div>

      <div class="counter">
        <span id="wordCount">0 words</span>
        <span id="charCount">0 characters</span>
      </div>

      <div class="actions">
        <button class="btn cyan" id="copyFull">COPY PROMPT</button>
        <button class="btn" id="share">CREATE SHARE TEXT</button>
      </div>

      <div class="share-box">
        <div class="share-text" id="shareText">
          Generate a prompt to create a share-ready message.
        </div>
      </div>

    </section>

  </main>

  <footer class="footer">
    AI Style Reverse-Engineer ULTRA · Free client-side prompt previewer ·
    <a class="link" href="https://promptflip.netlify.app" target="_blank" rel="noopener">
      https://promptflip.netlify.app
    </a>
  </footer>

</div>

<script>
(function(){

  "use strict";

  const TARGET_URL = "https://promptflip.netlify.app";

  const defaults = {
    subject: "cinematic futuristic portrait",
    composition: "centered hero composition",
    camera: "cinematic full-frame camera",
    lens: "85mm portrait lens",
    lighting: "dramatic volumetric lighting",
    environment: "luxury futuristic architectural environment",
    materials: "polished metal, glass, stone and premium fabric",
    color: "deep black, violet, cyan highlights and controlled gold",
    atmosphere: "subtle atmospheric haze with cinematic depth",
    fashion: "luxury contemporary ceremonial styling",
    detail: 8,
    negative: "blurry, distorted anatomy, low detail, oversaturated colors, watermark, text artifacts"
  };

  const ids = [
    "subject",
    "composition",
    "camera",
    "lens",
    "lighting",
    "environment",
    "materials",
    "color",
    "atmosphere",
    "fashion",
    "detail",
    "negative"
  ];

  const el = id => document.getElementById(id);

  const matrix = el("matrix");
  const output = el("output");
  const detail = el("detail");
  const detailValue = el("detailValue");
  const wordCount = el("wordCount");
  const charCount = el("charCount");
  const status = el("status");
  const shareText = el("shareText");

  function value(id){
    return el(id).value.trim();
  }

  function updateCounters(text){
    const words = text.trim()
      ? text.trim().split(/\s+/).filter(Boolean).length
      : 0;

    wordCount.textContent = words + " words";
    charCount.textContent = text.length + " characters";
  }

  function architectureData(){
    return [
      ["SUBJECT", value("subject")],
      ["COMPOSITION", value("composition")],
      ["CAMERA", value("camera")],
      ["LENS", value("lens")],
      ["LIGHTING", value("lighting")],
      ["ENVIRONMENT", value("environment")],
      ["MATERIALS", value("materials")],
      ["COLOR", value("color")],
      ["ATMOSPHERE", value("atmosphere")],
      ["FASHION", value("fashion")],
      ["DETAIL", "ultra-detailed level " + value("detail") + "/10"],
      ["NEGATIVE", value("negative")]
    ];
  }

  function renderMatrix(data){
    matrix.innerHTML = "";

    data.forEach(item => {
      const box = document.createElement("div");
      box.className = "matrix-item";

      const small = document.createElement("small");
      small.textContent = item[0];

      const span = document.createElement("span");
      span.textContent = item[1];

      box.appendChild(small);
      box.appendChild(span);
      matrix.appendChild(box);
    });
  }

  function buildPrompt(){

    const data = architectureData();

    const prompt =
      "AI STYLE ARCHITECT MATRIX — ULTRA PROMPT\n\n" +

      "SUBJECT:\n" +
      data[0][1] + "\n\n" +

      "COMPOSITION:\n" +
      data[1][1] + "\n\n" +

      "CAMERA:\n" +
      data[2][1] + "\n\n" +

      "LENS:\n" +
      data[3][1] + "\n\n" +

      "LIGHTING:\n" +
      data[4][1] + "\n\n" +

      "ENVIRONMENT:\n" +
      data[5][1] + "\n\n" +

      "MATERIALS:\n" +
      data[6][1] + "\n\n" +

      "COLOR ARCHITECTURE:\n" +
      data[7][1] + "\n\n" +

      "ATMOSPHERE:\n" +
      data[8][1] + "\n\n" +

      "FASHION / STYLING:\n" +
      data[9][1] + "\n\n" +

      "DETAIL DENSITY:\n" +
      data[10][1] + "\n\n" +

      "RENDERING DIRECTION:\n" +
      "photorealistic rendering, physically coherent materials, realistic skin and surface response, refined micro-contrast, cinematic tonal separation, natural depth of field, high dynamic range, professional color grading, coherent perspective, detailed textures, clean edges, controlled highlights\n\n" +

      "NEGATIVE CONSTRAINTS:\n" +
      data[11][1];

    output.value = prompt;
    renderMatrix(data);
    updateCounters(prompt);
    status.textContent = "GENERATED";
  }

  async function copyText(text){

    try{
      await navigator.clipboard.writeText(text);
      status.textContent = "COPIED";
    }catch(error){

      output.focus();
      output.select();

      try{
        document.execCommand("copy");
        status.textContent = "COPIED";
      }catch(copyError){
        status.textContent = "SELECTED";
      }
    }

    setTimeout(() => {
      status.textContent = "READY";
    },1800);
  }

  function createShareText(){

    const text =
      "I just built an AI image prompt with AI Style Reverse-Engineer ULTRA — a free client-side prompt architecture and preview workflow.\n\n" +
      "Explore the tool: https://promptflip.netlify.app";

    shareText.textContent = text;

    if(navigator.share){

      navigator.share({
        title: "AI Style Reverse-Engineer ULTRA",
        text: text,
        url: "https://promptflip.netlify.app"
      }).catch(() => {});

    }else{
      copyText(text);
    }
  }

  function reset(){

    Object.keys(defaults).forEach(id => {
      el(id).value = defaults[id];
    });

    detailValue.textContent = defaults.detail + "/10";
    buildPrompt();
  }

  detail.addEventListener("input", () => {
    detailValue.textContent = detail.value + "/10";
    buildPrompt();
  });

  ids.forEach(id => {

    if(id === "detail") return;

    el(id).addEventListener("input", buildPrompt);
    el(id).addEventListener("change", buildPrompt);

  });

  el("generate").addEventListener("click", buildPrompt);

  el("reset").addEventListener("click", reset);

  el("copyPrompt").addEventListener("click", () => {
    copyText(output.value);
  });

  el("copyFull").addEventListener("click", () => {
    copyText(output.value);
  });

  el("share").addEventListener("click", createShareText);

  reset();

})();
</script>

</body>
</html>
```

---

# 🔗 Production Tracking Destination

The widget contains the production destination directly in its footer:

```text
https://promptflip.netlify.app
```

The JavaScript sharing function also uses the exact production destination:

```javascript
const TARGET_URL = "https://promptflip.netlify.app";
```

Generated share text includes:

```text
Explore the tool: https://promptflip.netlify.app
```

The browser-native Web Share API uses:

```javascript
url: "https://promptflip.netlify.app"
```

---

# 🌐 Canonical Production URL

The primary production destination for this project is:

**https://promptflip.netlify.app**

All operational calls-to-action in this README point to the production application.

## Open the Application

https://promptflip.netlify.app

## Use the AI Style Architect

https://promptflip.netlify.app

## Use the Free Client-Side Prompt Previewer

https://promptflip.netlify.app

---

# 🔗 Developer Documentation & Backlink Context

The project also has a technical development article covering the zero-dependency cyberpunk widget and website-sidebar implementation:

https://dev.to/dev_alex_matrix/building-a-zero-dependency-cyberpunk-ai-prompt-widget-for-website-sidebars-full-source-code-23aa

The production application remains:

https://promptflip.netlify.app

---

# 🧩 Technical Architecture

```text
AI Style Reverse-Engineer ULTRA
│
├── HTML
│   ├── Application Header
│   ├── Style Input Matrix
│   ├── Prompt Architecture Matrix
│   ├── Prompt Preview
│   ├── Copy Controls
│   └── Share Controls
│
├── CSS
│   ├── Cyberpunk Interface
│   ├── Responsive Grid
│   ├── 360px Optimization
│   ├── Matrix Cards
│   └── Mobile Breakpoints
│
└── JavaScript
    ├── Default State
    ├── Input State
    ├── Architecture Mapping
    ├── Prompt Builder
    ├── Matrix Renderer
    ├── Clipboard API
    ├── Web Share API
    ├── Word Counter
    ├── Character Counter
    └── Reset System
```

---

# ⚙️ Browser Compatibility

The widget uses broadly supported browser technologies:

- HTML5
- CSS3
- JavaScript
- Clipboard API with fallback
- Web Share API when available
- CSS Grid
- CSS Media Queries
- DOM APIs

Web Share functionality depends on browser and device support. Copy functionality includes a fallback selection mechanism.

---

# 🔐 Client-Side Privacy Architecture

The included prompt-generation engine constructs prompts directly in the browser.

The production source does not include:

- Database calls
- Server-side prompt storage
- AI API calls
- API credentials
- Authentication requirements

Users should still review the privacy policies and security restrictions of any third-party website where the widget is embedded.

Production application:

https://promptflip.netlify.app

---

# 🧪 Prompt Architecture Example

The generated architecture follows this general sequence:

```text
SUBJECT
↓
COMPOSITION
↓
CAMERA
↓
LENS
↓
LIGHTING
↓
ENVIRONMENT
↓
MATERIALS
↓
COLOR ARCHITECTURE
↓
ATMOSPHERE
↓
FASHION / STYLING
↓
DETAIL DENSITY
↓
RENDERING DIRECTION
↓
NEGATIVE CONSTRAINTS
```

This structure allows individual visual variables to be adjusted without manually rebuilding the entire prompt.

---

# 🛠️ Customization

Developers can extend the matrix by modifying the `architectureData()` function and adding corresponding HTML controls.

Possible additional dimensions include:

```text
Film Stock
Shutter Speed
Aperture
Depth of Field
Perspective
Pose
Hair
Makeup
Background
Texture
Weather
Time of Day
Color Temperature
Post Processing
Aspect Ratio
Mood
Visual Era
Art Direction
```

---

# 📈 SEO-Oriented Topic Coverage

This repository documentation covers technical and informational topics associated with:

- AI Style Reverse-Engineer ULTRA
- AI Style Architect Matrix
- Reverse-engineer Midjourney prompts from image
- Midjourney style architecture tool
- Free client-side prompt previewer
- AI image prompt generator
- AI prompt engineering
- Midjourney prompt architecture
- AI image prompt analyzer
- AI art prompt builder
- visual style analysis
- reverse engineering AI art styles
- browser-based AI tools
- client-side AI utilities
- vanilla JavaScript AI tools
- HTML AI widgets
- responsive AI widgets
- cyberpunk web interfaces
- prompt engineering tools
- image generation prompt workflows

The production application is available at:

https://promptflip.netlify.app

---

# 🤝 Contributing

Contributions can focus on:

- Additional prompt architecture layers
- New visual-style controls
- Accessibility improvements
- Responsive layout improvements
- Browser compatibility
- Clipboard compatibility
- Prompt formatting
- AI image-generation presets
- Performance optimization
- Documentation
- UI improvements

Keep contributions dependency-light and preserve the standalone HTML architecture where practical.

---

# 📄 License

The repository owner should publish the license governing this source code according to the intended distribution terms.

---

# ⭐ Project Summary

**AI Style Reverse-Engineer ULTRA** is a standalone **AI Style Architect Matrix Widget** built with HTML, CSS, and vanilla JavaScript.

It provides a structured workflow for creators searching for ways to **reverse-engineer Midjourney prompts from image**, experiment with a **Midjourney style architecture tool**, and use a **Free client-side prompt previewer** without requiring a backend AI API for the included prompt-construction engine.

**Canonical Production URL:**  
https://promptflip.netlify.app

**Developer Article / Secondary Backlink:**  
https://dev.to/dev_alex_matrix/building-a-zero-dependency-cyberpunk-ai-prompt-widget-for-website-sidebars-full-source-code-23aa
