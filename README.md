<!DOCTYPE html>
<html lang="en" class="dark">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>te1biz // Engineering Console</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@400;500;700&family=Space+Grotesk:wght@600;700&display=swap" rel="stylesheet">
  <script>
    tailwind.config = {
      darkMode: 'class',
      theme: {
        extend: {
          colors: {
            pitch: '#090A0C',
            surface: '#0F1115',
            line: '#1C1F26',
            dim: '#636A78',
            bright: '#EDEDED',
            signal: '#E11D48',
          },
          fontFamily: {
            display: ['"Space Grotesk"', 'sans-serif'],
            mono: ['"JetBrains Mono"', 'monospace'],
          }
        }
      }
    }
  </script>
  <style>
    * { border-radius: 0px !important; }
    ::selection { background: #EDEDED; color: #090A0C; }
  </style>
</head>
<body class="bg-pitch text-bright font-mono antialiased selection:bg-bright selection:text-pitch min-h-screen p-6 md:p-16 flex justify-center">

  <main class="w-full max-w-5xl border border-line bg-surface">
    
   
  <header class="border-b border-line p-8 md:p-12 flex flex-col md:flex-row justify-between items-start md:items-end gap-6">
      <div>
        <div class="flex items-center gap-3 text-xs tracking-widest text-dim uppercase mb-3">
          <span class="inline-block w-2 h-2 bg-signal"></span>
          <span>SYSTEM RUNTIME // DEV_MODE</span>
        </div>
        <h1 class="font-display text-5xl md:text-7xl font-bold tracking-tighter text-bright leading-none uppercase">
          EASY REVENGE<span class="text-signal">.</span>
        </h1>
      </div>
      <div class="text-xs text-dim text-left md:text-right space-y-1">
        <p class="text-bright">OPERATOR: te1biz</p>
        <p>ROLE: PRODUCT ENG / NEURAL NETS</p>
        <p>LOC: 2ND YR CS // LVL 17</p>
      </div>
    </header>

    <!-- STATUS TELEMETRY STRIP -->
    <div class="grid grid-cols-2 md:grid-cols-4 border-b border-line text-xs divide-x divide-line bg-pitch">
      <div class="p-4 flex flex-col">
        <span class="text-dim text-[10px] tracking-wider uppercase mb-1">ENV / RUNTIME</span>
        <span class="text-bright">Python 3.12 / Poetry</span>
      </div>
      <div class="p-4 flex flex-col">
        <span class="text-dim text-[10px] tracking-wider uppercase mb-1">INTERFACE</span>
        <span class="text-bright">Semantic HTML5</span>
      </div>
      <div class="p-4 flex flex-col">
        <span class="text-dim text-[10px] tracking-wider uppercase mb-1">VCS TARGET</span>
        <span class="text-bright">Git // origin/main</span>
      </div>
      <div class="p-4 flex flex-col">
        <span class="text-dim text-[10px] tracking-wider uppercase mb-1">NETWORK ACCESS</span>
        <div class="flex items-center gap-3">
          <a href="https://t.me/te1biz" target="_blank" class="text-bright hover:underline hover:text-signal transition-colors">TG ↗</a>
          <span class="text-dim">/</span>
          <span class="text-bright">DC: te1biz</span>
        </div>
      </div>
    </div>

    <!-- MAIN DATA LEDGER (NO BULKY CARDS) -->
    <div class="divide-y divide-line">
      
      <!-- ROW 01: IDENTITY SPEC -->
      <section class="grid grid-cols-1 md:grid-cols-12 text-sm">
        <div class="md:col-span-3 p-6 text-xs text-dim tracking-wider uppercase bg-pitch/40 border-b md:border-b-0 md:border-r border-line">
          01 // DIRECTIVE
        </div>
        <div class="md:col-span-9 p-6 space-y-4">
          <p class="text-base text-bright leading-relaxed max-w-2xl font-sans">
            Engineering resilient system backends, machine intelligence integration, and high-cadence product architectures. Prioritizing deterministic execution over superficial interface cosmetics.
          </p>
          <div class="text-xs text-dim">
            CORE_FOCUS: [<span class="text-bright">Product Engineering</span>, <span class="text-bright">Deep Learning Models</span>, <span class="text-bright">Automation Pipelines</span>]
          </div>
        </div>
      </section>

      <!-- ROW 02: MOUNTED REPOSITORIES -->
      <section class="grid grid-cols-1 md:grid-cols-12 text-sm">
        <div class="md:col-span-3 p-6 text-xs text-dim tracking-wider uppercase bg-pitch/40 border-b md:border-b-0 md:border-r border-line">
          02 // REGISTRY
        </div>
        <div class="md:col-span-9 divide-y divide-line">
          
          <a href="https://github.com/DOUP1G/WebEducation" target="_blank" class="group p-6 flex flex-col md:flex-row md:items-center justify-between gap-4 block hover:bg-pitch transition-colors">
            <div>
              <div class="flex items-center gap-3">
                <span class="font-bold text-bright group-hover:text-signal transition-colors">WebEducation</span>
                <span class="text-[10px] border border-line px-1.5 py-0.5 text-dim">PLATFORM</span>
              </div>
              <p class="text-xs text-dim mt-1 font-sans">Educational web infrastructure, distributed routing, and core business services.</p>
            </div>
            <div class="text-xs text-dim group-hover:text-bright flex items-center gap-2">
              <span>MOUNT REPO</span>
              <span class="font-bold">↗</span>
            </div>
          </a>

          <a href="https://github.com/DOUP1G/FirsterChuv" target="_blank" class="group p-6 flex flex-col md:flex-row md:items-center justify-between gap-4 block hover:bg-pitch transition-colors">
            <div>
              <div class="flex items-center gap-3">
                <span class="font-bold text-bright group-hover:text-signal transition-colors">FirsterChuv</span>
                <span class="text-[10px] border border-line px-1.5 py-0.5 text-dim">COLLAB</span>
              </div>
              <p class="text-xs text-dim mt-1 font-sans">Multi-module engineering codebase and synchronous subsystem communication.</p>
            </div>
            <div class="text-xs text-dim group-hover:text-bright flex items-center gap-2">
              <span>MOUNT REPO</span>
              <span class="font-bold">↗</span>
            </div>
          </a>

          <a href="https://github.com/te1biz/homework" target="_blank" class="group p-6 flex flex-col md:flex-row md:items-center justify-between gap-4 block hover:bg-pitch transition-colors">
            <div>
              <div class="flex items-center gap-3">
                <span class="font-bold text-bright group-hover:text-signal transition-colors">homework</span>
                <span class="text-[10px] border border-line px-1.5 py-0.5 text-dim">LAB</span>
              </div>
              <p class="text-xs text-dim mt-1 font-sans">Low-level algorithm specs, clean structure implementations, and sandbox runs.</p>
            </div>
            <div class="text-xs text-dim group-hover:text-bright flex items-center gap-2">
              <span>MOUNT REPO</span>
              <span class="font-bold">↗</span>
            </div>
          </a>

        </div>
      </section>

      <!-- ROW 03: TERMINAL TELEMETRY -->
      <section class="grid grid-cols-1 md:grid-cols-12 text-sm">
        <div class="md:col-span-3 p-6 text-xs text-dim tracking-wider uppercase bg-pitch/40 border-b md:border-b-0 md:border-r border-line">
          03 // EXECUTION
        </div>
        <div class="md:col-span-9 p-6 font-mono text-xs text-dim space-y-2 bg-pitch">
          <div class="flex items-center justify-between">
            <span class="text-bright">$ poetry run python -m te1biz.runtime</span>
            <span class="text-[10px] text-signal uppercase tracking-wider">EXEC_OK</span>
          </div>
          <p class="text-dim">> [INFO] Neural pipeline ready. All workers initialized.</p>
          <p class="text-dim">> [INFO] Target branches clean. 0 errors detected.</p>
        </div>
      </section>

    </div>

    <!-- TERMINAL FOOTER RULE -->
    <footer class="p-6 border-t border-line flex flex-col sm:flex-row justify-between items-center text-xs text-dim gap-4 bg-pitch">
      <div class="italic">«All devils die. Keep moving.»</div>
      <div class="tracking-widest uppercase text-[10px]">
        STAMP // 2026.11.03
      </div>
    </footer>

  </main>

</body>
</html>
