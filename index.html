<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=720" />
  <title>Alcancía familiar</title>
  <style>
    *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }
 
    :root {
      --bg-primary: #ffffff;
      --bg-secondary: #f5f5f3;
      --bg-tertiary: #efefec;
      --text-primary: #1a1a18;
      --text-secondary: #6b6b67;
      --border-light: rgba(0,0,0,0.1);
      --border-mid: rgba(0,0,0,0.18);
      --radius-md: 8px;
      --radius-lg: 12px;
    }
    @media (prefers-color-scheme: dark) {
      :root {
        --bg-primary: #1e1e1c;
        --bg-secondary: #2a2a27;
        --bg-tertiary: #333330;
        --text-primary: #f0efe8;
        --text-secondary: #9e9d97;
        --border-light: rgba(255,255,255,0.1);
        --border-mid: rgba(255,255,255,0.18);
      }
    }
    html { -webkit-text-size-adjust: 100%; text-size-adjust: 100%; }
    body {
      font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
      background: var(--bg-tertiary);
      color: var(--text-primary);
      min-height: 100vh;
      padding: 1.5rem 1rem 3rem;
    }
    .app { max-width: 720px; margin: 0 auto; }
    .header { text-align: center; margin-bottom: 1.5rem; }
    .header h1 { font-size: 26px; font-weight: 600; color: var(--text-primary); letter-spacing: -0.3px; }
    .header p { font-size: 14px; color: var(--text-secondary); margin-top: 4px; }
    .kids-grid { display: grid; grid-template-columns: repeat(4, 1fr); gap: 10px; margin-bottom: 1.25rem; }
    .kid-btn { padding: 12px 8px; border-radius: var(--radius-lg); border: 1.5px solid var(--border-light); background: var(--bg-primary); cursor: pointer; text-align: center; transition: all 0.15s; }
    .kid-btn:hover { background: var(--bg-secondary); }
    .kid-btn .avatar { width: 44px; height: 44px; border-radius: 50%; margin: 0 auto 7px; display: flex; align-items: center; justify-content: center; font-size: 16px; font-weight: 600; }
    .kid-btn .kname { font-size: 13px; font-weight: 500; color: var(--text-primary); }
    .kid-btn .kbal { font-size: 12px; color: var(--text-secondary); margin-top: 2px; }
    .panel { background: var(--bg-primary); border-radius: var(--radius-lg); border: 0.5px solid var(--border-light); padding: 1.25rem; margin-bottom: 0.875rem; }
    .ptitle { font-size: 11px; font-weight: 600; color: var(--text-secondary); margin-bottom: 0.875rem; text-transform: uppercase; letter-spacing: 0.06em; }
    .metrics { display: grid; grid-template-columns: repeat(3, 1fr); gap: 10px; margin-bottom: 0.875rem; }
    .metric { background: var(--bg-secondary); border-radius: var(--radius-md); padding: 12px; }
    .metric .ml { font-size: 12px; color: var(--text-secondary); margin-bottom: 4px; }
    .metric .mv { font-size: 19px; font-weight: 500; color: var(--text-primary); }
    .mv.grn { color: #0F6E56; }
    .mv.red { color: #993C1D; }
    .form-row { display: flex; gap: 8px; align-items: flex-end; flex-wrap: wrap; margin-bottom: 10px; }
    .fg { flex: 1; min-width: 80px; }
    .fg label { font-size: 12px; color: var(--text-secondary); display: block; margin-bottom: 4px; }
    .fg input, .fg select { width: 100%; height: 38px; border-radius: var(--radius-md); border: 0.5px solid var(--border-mid); background: var(--bg-primary); color: var(--text-primary); padding: 0 10px; font-size: 14px; outline: none; }
    .fg input:focus { box-shadow: 0 0 0 2px rgba(100,100,255,0.2); border-color: rgba(100,100,255,0.4); }
    .btn { height: 38px; padding: 0 16px; border-radius: var(--radius-md); border: 0.5px solid var(--border-mid); cursor: pointer; font-size: 13px; font-weight: 500; white-space: nowrap; transition: opacity 0.15s; }
    .btn:hover { opacity: 0.82; }
    .btn-g { background: #E1F5EE; color: #085041; border-color: #5DCAA5; }
    .btn-r { background: #FAECE7; color: #712B13; border-color: #D85A30; }
    .tx-list { max-height: 220px; overflow-y: auto; }
    .tx-item { display: flex; justify-content: space-between; align-items: center; padding: 8px 0; border-bottom: 0.5px solid var(--border-light); }
    .tx-item:last-child { border-bottom: none; }
    .tx-desc { font-size: 14px; color: var(--text-primary); }
    .tx-date { font-size: 12px; color: var(--text-secondary); margin-top: 2px; }
    .tx-amt { font-size: 14px; font-weight: 500; }
    .tx-amt.pos { color: #0F6E56; }
    .tx-amt.neg { color: #993C1D; }
    .del-btn { background: none; border: none; cursor: pointer; color: var(--text-secondary); font-size: 13px; padding: 2px 6px; border-radius: 4px; margin-left: 6px; }
    .del-btn:hover { color: #993C1D; background: #FAECE7; }
    .chart-container { position: relative; width: 100%; }
    .proj-row { display: flex; gap: 10px; align-items: flex-end; flex-wrap: wrap; }
    .proj-res { background: var(--bg-secondary); border-radius: var(--radius-md); padding: 10px 16px; font-size: 13px; color: var(--text-secondary); flex: 1; min-width: 160px; }
    .proj-res .pval { font-size: 20px; font-weight: 500; color: var(--text-primary); display: block; }
    .empty { text-align: center; color: var(--text-secondary); padding: 2rem 0; font-size: 14px; }
    .ibadge { font-size: 11px; background: #EAF3DE; color: #3B6D11; border-radius: 4px; padding: 2px 7px; margin-left: 6px; }
    .legend-row { display: flex; flex-wrap: wrap; gap: 14px; margin-bottom: 12px; font-size: 12px; color: var(--text-secondary); }
    .legend-row span { display: flex; align-items: center; gap: 5px; }
    .legend-sq { width: 10px; height: 10px; border-radius: 2px; display: inline-block; }
    .var-positive { color: #0F6E56; font-weight: 500; }
    .var-negative { color: #993C1D; font-weight: 500; }
    .var-zero { color: var(--text-secondary); }
    .tabs { display: flex; gap: 4px; margin-bottom: 1rem; flex-wrap: wrap; }
    .tab { padding: 7px 16px; border-radius: var(--radius-md); border: 0.5px solid var(--border-light); background: var(--bg-primary); cursor: pointer; font-size: 13px; color: var(--text-secondary); transition: all 0.15s; }
    .tab.active { background: var(--bg-secondary); color: var(--text-primary); font-weight: 500; border-color: var(--border-mid); }
    .section { display: none; }
    .section.visible { display: block; }
    table { border-collapse: collapse; width: 100%; }
    th, td { padding: 6px 8px; }
    th { font-weight: 500; }
 
    @media (max-width: 600px) {
      body { padding: 1rem 0.75rem 2rem; }
      .header h1 { font-size: 20px; }
      .kids-grid { gap: 6px; }
      .kid-btn { padding: 8px 4px; }
      .kid-btn .avatar { width: 34px; height: 34px; font-size: 13px; margin-bottom: 5px; }
      .kid-btn .kname { font-size: 11px; }
      .kid-btn .kbal  { font-size: 11px; }
      .metrics { gap: 6px; }
      .metric { padding: 9px 8px; }
      .metric .ml { font-size: 11px; }
      .metric .mv { font-size: 15px; }
      .panel { padding: 1rem 0.875rem; }
      .tabs { flex-wrap: nowrap; overflow-x: auto; padding-bottom: 2px; }
      .tab { padding: 6px 12px; font-size: 12px; flex-shrink: 0; white-space: nowrap; }
      .fg input, .fg select { font-size: 16px; }
    }
  </style>
</head>
<body>
  <div class="app">
    <div class="header">
      <h1>Alcancía familiar</h1>
      <p>Ahorro con interés compuesto del 2% mensual</p>
    </div>
    <div class="kids-grid" id="kidsGrid"></div>
    <div class="tabs">
      <button class="tab active" onclick="switchTab('resumen')">Resumen</button>
      <button class="tab" onclick="switchTab('grafico')">Ingresos por mes</button>
      <button class="tab" onclick="switchTab('registro')">Registrar</button>
      <button class="tab" onclick="switchTab('proyeccion')">Proyección</button>
    </div>
    <div id="sResumen" class="section visible">
      <div id="resumenMetrics"></div>
      <div class="panel" id="lineChartPanel">
        <div class="ptitle">Evolución del saldo</div>
        <div class="chart-container" style="height:220px">
          <canvas id="lineChart"></canvas>
        </div>
      </div>
      <div class="panel">
        <div class="ptitle">Movimientos</div>
        <div class="tx-list" id="txList"></div>
      </div>
    </div>
    <div id="sGrafico" class="section">
      <div class="panel">
        <div id="graficoHeader"></div>
        <div class="chart-container" id="barChartWrap" style="height:220px">
          <canvas id="barChart"></canvas>
        </div>
      </div>
      <div class="panel">
        <div class="ptitle">Variación de saldo mes a mes</div>
        <div id="varTable" style="margin-bottom:12px"></div>
        <div class="chart-container" id="varChartWrap" style="height:220px">
          <canvas id="varChart"></canvas>
        </div>
      </div>
    </div>
    <div id="sRegistro" class="section"></div>
    <div id="sProyeccion" class="section"></div>
  </div>
 
  <!-- Scripts AL FINAL del body, no en el head -->
  <script src="https://cdnjs.cloudflare.com/ajax/libs/Chart.js/4.4.1/chart.umd.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/chartjs-adapter-date-fns/3.0.0/chartjs-adapter-date-fns.bundle.min.js"></script>
  <script>
    const KIDS = [
      { id: 'lucia',    name: 'Lucía',    color: '#7F77DD', bg: '#EEEDFE', txt: '#3C3489', av: 'L' },
      { id: 'nicolas',  name: 'Nicolás',  color: '#1D9E75', bg: '#E1F5EE', txt: '#085041', av: 'N' },
      { id: 'sara',     name: 'Sara',     color: '#D4537E', bg: '#FBEAF0', txt: '#72243E', av: 'S' },
      { id: 'bautista', name: 'Bautista', color: '#BA7517', bg: '#FAEEDA', txt: '#633806', av: 'B' },
    ];
    const RATE = 0.02;
    const API = 'https://script.google.com/macros/s/AKfycbzeU9SHzfflIiy-uzI4v9DwAe5W2xfBe4fbxAZeRbgxMNYQvixvgoymZbsKUNBmhH-b/exec';
    let sel = 'lucia';
    let kids = {};
    let charts = {};
    let activeTab = 'resumen';
    let syncing = false;
 
    KIDS.forEach(k => { kids[k.id] = { transactions: [] }; });
 
    function showSyncStatus(msg, color) {
      let el = document.getElementById('syncStatus');
      if (!el) {
        el = document.createElement('div');
        el.id = 'syncStatus';
        el.style.cssText = 'position:fixed;bottom:16px;right:16px;padding:8px 14px;border-radius:8px;font-size:13px;font-weight:500;z-index:999;transition:opacity .4s';
        document.body.appendChild(el);
      }
      el.textContent = msg;
      el.style.background = color === 'ok' ? '#E1F5EE' : color === 'err' ? '#FAECE7' : '#f5f5f3';
      el.style.color = color === 'ok' ? '#085041' : color === 'err' ? '#712B13' : '#6b6b67';
      el.style.opacity = '1';
      if (color !== 'loading') setTimeout(() => { el.style.opacity = '0'; }, 2500);
    }
 
    function localSave() {
      try { localStorage.setItem('alcancia_v3', JSON.stringify({ kids })); } catch(e) {}
    }
 
    function localLoad() {
      try {
        const s = localStorage.getItem('alcancia_v3');
        if (s) { const p = JSON.parse(s); if (p.kids) kids = p.kids; }
      } catch(e) {}
    }
 
    async function load() {
      localLoad();
      renderAll();
      showSyncStatus('Sincronizando…', 'loading');
      try {
        const res = await fetch(API + '?action=getAll');
        const json = await res.json();
        if (json.ok && json.data.length) {
          KIDS.forEach(k => { kids[k.id] = { transactions: [] }; });
          json.data.forEach(row => {
            const kid = row.kid;
            if (kids[kid]) {
              kids[kid].transactions.push({
                id: String(row.id),
                desc: row.desc,
                amount: parseFloat(row.amount),
                date: row.date
              });
            }
          });
          localSave();
          renderAll();
        }
        showSyncStatus('Sincronizado ✓', 'ok');
      } catch(e) {
        showSyncStatus('Sin conexión — datos locales', 'err');
      }
    }
 
    async function save() {
      localSave();
      if (syncing) return;
      syncing = true;
      showSyncStatus('Guardando…', 'loading');
      const allTxs = [];
      KIDS.forEach(k => {
        kids[k.id].transactions.forEach(tx => {
          allTxs.push({ id: tx.id, kid: k.id, desc: tx.desc, amount: tx.amount, date: tx.date });
        });
      });
      try {
        await fetch(API, {
          method: 'POST',
          body: JSON.stringify({ action: 'save', transactions: allTxs })
        });
        showSyncStatus('Guardado ✓', 'ok');
      } catch(e) {
        showSyncStatus('Error al guardar', 'err');
      }
      syncing = false;
    }
 
    function todayStr() { return new Date().toISOString().split('T')[0]; }
    function futureDate(m) { const d = new Date(); d.setMonth(d.getMonth() + m); return d.toISOString().split('T')[0]; }
    function fmt(n) { return '$' + Math.round(n).toLocaleString('es-CL'); }
    function fmtDate(d) { const [y,m,day] = d.split('-'); return `${day}/${m}/${y}`; }
    function monthLabel(d) {
      const [y,m] = d.split('-');
      return ['Ene','Feb','Mar','Abr','May','Jun','Jul','Ago','Sep','Oct','Nov','Dic'][parseInt(m)-1] + ' ' + y.slice(2);
    }
    function monthsBetween(d1, d2) {
      const a = new Date(d1), b = new Date(d2);
      return Math.max(0, (b.getFullYear()-a.getFullYear())*12 + (b.getMonth()-a.getMonth()) + (b.getDate()-a.getDate())/30.5);
    }
    function computeBalance(txs, upTo) {
      const sorted = [...txs].sort((a,b) => a.date.localeCompare(b.date));
      if (!sorted.length) return 0;
      let bal = 0, lastDate = null;
      sorted.forEach(tx => {
        if (lastDate) {
          const m = monthsBetween(lastDate, tx.date < upTo ? tx.date : upTo);
          bal = bal * Math.pow(1+RATE, m);
        }
        if (tx.date <= upTo) bal += tx.amount;
        lastDate = tx.date;
      });
      if (lastDate) { const m = monthsBetween(lastDate, upTo); if (m > 0) bal = bal * Math.pow(1+RATE, m); }
      return bal;
    }
    function getMonthlyData(txs) {
      if (!txs.length) return [];
      const sorted = [...txs].sort((a,b) => a.date.localeCompare(b.date));
      const first = sorted[0].date.slice(0,7);
      const today = todayStr().slice(0,7);
      const months = [];
      let cur = first;
      while (cur <= today) {
        months.push(cur);
        const [y,m] = cur.split('-');
        cur = new Date(parseInt(y), parseInt(m), 1).toISOString().slice(0,7);
      }
      return months.map(mo => {
        const bal = Math.round(computeBalance(txs, mo + '-28'));
        const deposits = Math.round(txs.filter(t => t.date.startsWith(mo) && t.amount > 0).reduce((s,t) => s+t.amount, 0));
        const withdrawals = Math.round(Math.abs(txs.filter(t => t.date.startsWith(mo) && t.amount < 0).reduce((s,t) => s+t.amount, 0)));
        return { month: mo, bal, deposits, withdrawals };
      });
    }
    function kc() { return KIDS.find(k => k.id === sel); }
 
    function destroyCharts() {
      Object.values(charts).forEach(c => { try { c.destroy(); } catch(e) {} });
      charts = {};
    }
 
    function renderGrid() {
      document.getElementById('kidsGrid').innerHTML = KIDS.map(k => {
        const bal = computeBalance(kids[k.id].transactions, todayStr());
        const act = sel === k.id;
        return `<button class="kid-btn" onclick="selectKid('${k.id}')"
          style="${act ? `border-color:${k.color};border-width:2px` : ''}">
          <div class="avatar" style="background:${k.bg};color:${k.txt}">${k.av}</div>
          <div class="kname">${k.name}</div>
          <div class="kbal">${fmt(bal)}</div>
        </button>`;
      }).join('');
    }
 
    /* ── RESUMEN ── */
    function renderResumen() {
      const txs = kids[sel].transactions;
      const bal = computeBalance(txs, todayStr());
      const deps = txs.filter(t => t.amount > 0).reduce((s,t) => s+t.amount, 0);
      const withs = Math.abs(txs.filter(t => t.amount < 0).reduce((s,t) => s+t.amount, 0));
      const interest = Math.max(0, bal - deps + withs);
      const color = kc().color;
 
      // Actualiza solo las métricas — no toca el canvas
      document.getElementById('resumenMetrics').innerHTML = `
        <div class="panel">
          <div class="ptitle">Resumen de ${kc().name}</div>
          <div class="metrics">
            <div class="metric"><div class="ml">Saldo actual</div><div class="mv">${fmt(bal)}</div></div>
            <div class="metric"><div class="ml">Total ahorrado</div><div class="mv grn">+${fmt(deps)}</div></div>
            <div class="metric"><div class="ml">Retiros</div><div class="mv red">-${fmt(withs)}</div></div>
          </div>
          <div style="font-size:13px;color:var(--text-secondary)">
            Intereses ganados: <strong style="color:#0F6E56">${fmt(interest)}</strong>
            <span class="ibadge">2% mensual</span>
          </div>
        </div>`;
 
      renderTxList();
 
      // Destruye solo el gráfico de línea si existe
      if (charts.line) { try { charts.line.destroy(); } catch(e){} charts.line = null; }
 
      if (!txs.length) return;
 
      const sorted = [...txs].sort((a,b) => a.date.localeCompare(b.date));
      const today = new Date();
      const pts = [];
      const d = new Date(sorted[0].date); d.setDate(1);
      while (d <= today) {
        pts.push({ x: d.toISOString().split('T')[0], y: Math.round(computeBalance(txs, d.toISOString().split('T')[0])) });
        d.setMonth(d.getMonth() + 1);
      }
      pts.push({ x: todayStr(), y: Math.round(computeBalance(txs, todayStr())) });
 
      // El canvas ya existe en el DOM — solo lo inicializamos
      const canvas = document.getElementById('lineChart');
      charts.line = new Chart(canvas, {
        type: 'line',
        data: {
          datasets: [{
            data: pts,
            borderColor: color,
            backgroundColor: color + '28',
            fill: true,
            tension: 0.4,
            pointRadius: 3,
            pointBackgroundColor: color,
            parsing: { xAxisKey: 'x', yAxisKey: 'y' }
          }]
        },
        options: {
          responsive: true,
          maintainAspectRatio: false,
          plugins: { legend: { display: false }, tooltip: { callbacks: { label: ctx => fmt(ctx.parsed.y) } } },
          scales: {
            x: {
              type: 'category',
              ticks: { maxTicksLimit: 10, callback: function(val, idx) { const v = pts[idx]?.x; return v ? monthLabel(v.slice(0,7)) : ''; } },
              grid: { display: false }
            },
            y: {
              ticks: { callback: v => '$' + Math.round(v).toLocaleString('es-CL') },
              grid: { color: 'rgba(128,128,128,.1)' }
            }
          }
        }
      });
    }
 
    function renderTxList() {
      const txs = [...kids[sel].transactions].sort((a,b) => b.date.localeCompare(a.date));
      const el = document.getElementById('txList');
      if (!el) return;
      if (!txs.length) { el.innerHTML = '<div class="empty">Sin movimientos aún</div>'; return; }
      el.innerHTML = txs.map(tx => `
        <div class="tx-item">
          <div>
            <div class="tx-desc">${tx.desc}</div>
            <div class="tx-date">${fmtDate(tx.date)}</div>
          </div>
          <div style="display:flex;align-items:center">
            <span class="tx-amt ${tx.amount >= 0 ? 'pos' : 'neg'}">${tx.amount >= 0 ? '+' : ''}${fmt(tx.amount)}</span>
            <button class="del-btn" onclick="delTx('${tx.id}')">✕</button>
          </div>
        </div>`).join('');
    }
 
    /* ── GRÁFICO MENSUAL ── */
    function renderMonthlyChart() {
      const txs = kids[sel].transactions;
      const monthly = getMonthlyData(txs);
      const color = kc().color;
      const barH = Math.max(220, monthly.length * 40 + 80);
 
      // Destruye charts anteriores
      if (charts.bar) { try { charts.bar.destroy(); } catch(e){} charts.bar = null; }
      if (charts.var) { try { charts.var.destroy(); } catch(e){} charts.var = null; }
 
      // Actualiza header y altura de los wraps — sin tocar los canvas
      document.getElementById('graficoHeader').innerHTML = `
        <div class="ptitle">Saldo mes a mes — ${kc().name}</div>
        <div class="legend-row">
          <span><span class="legend-sq" style="background:${color}"></span>Saldo al cierre</span>
          <span><span class="legend-sq" style="background:#1D9E75"></span>Ingresos del mes</span>
          <span><span class="legend-sq" style="background:#D85A30"></span>Retiros del mes</span>
        </div>`;
      document.getElementById('barChartWrap').style.height = barH + 'px';
      document.getElementById('varChartWrap').style.height = barH + 'px';
 
      if (!monthly.length) {
        document.getElementById('varTable').innerHTML = '<div class="empty">Sin movimientos aún.</div>';
        return;
      }
 
      const labels   = monthly.map(m => monthLabel(m.month));
      const balData  = monthly.map(m => m.bal);
      const depData  = monthly.map(m => m.deposits);
      const witData  = monthly.map(m => -m.withdrawals);
      const varData  = monthly.map((m,i) => i === 0 ? 0 : m.bal - monthly[i-1].bal);
 
      charts.bar = new Chart(document.getElementById('barChart'), {
        type: 'bar',
        data: {
          labels,
          datasets: [
            { label: 'Saldo',    data: balData, backgroundColor: color+'cc', borderColor: color,     borderWidth: 1, yAxisID: 'ySaldo', order: 2 },
            { label: 'Ingresos', data: depData, backgroundColor: '#1D9E7599', borderColor: '#1D9E75', borderWidth: 1, yAxisID: 'yMov',   order: 1 },
            { label: 'Retiros',  data: witData, backgroundColor: '#D85A3099', borderColor: '#D85A30', borderWidth: 1, yAxisID: 'yMov',   order: 1 },
          ]
        },
        options: {
          indexAxis: 'y', responsive: true, maintainAspectRatio: false,
          plugins: { legend: { display: false }, tooltip: { callbacks: { label: ctx => ctx.dataset.label + ': ' + fmt(Math.abs(ctx.parsed.x)) } } },
          scales: {
            ySaldo: { display: false }, yMov: { display: false },
            x: { ticks: { callback: v => '$' + Math.round(Math.abs(v)).toLocaleString('es-CL') }, grid: { color: 'rgba(128,128,128,.1)' } },
            y: { grid: { display: false }, ticks: { autoSkip: false } }
          }
        }
      });
 
      charts.var = new Chart(document.getElementById('varChart'), {
        type: 'bar',
        data: {
          labels,
          datasets: [{ label: 'Variación', data: varData,
            backgroundColor: varData.map(v => v >= 0 ? '#1D9E7599' : '#D85A3099'),
            borderColor: varData.map(v => v >= 0 ? '#1D9E75' : '#D85A30'),
            borderWidth: 1 }]
        },
        options: {
          indexAxis: 'y', responsive: true, maintainAspectRatio: false,
          plugins: { legend: { display: false }, tooltip: { callbacks: { label: ctx => (ctx.parsed.x >= 0 ? '+' : '') + fmt(ctx.parsed.x) } } },
          scales: {
            x: { ticks: { callback: v => (v < 0 ? '-' : '+') + '$' + Math.round(Math.abs(v)).toLocaleString('es-CL') }, grid: { color: 'rgba(128,128,128,.1)' } },
            y: { grid: { display: false }, ticks: { autoSkip: false } }
          }
        }
      });
 
      document.getElementById('varTable').innerHTML = `
        <div style="overflow-x:auto">
          <table style="table-layout:fixed">
            <thead><tr style="border-bottom:.5px solid var(--border-light)">
              <th style="text-align:left;color:var(--text-secondary);font-weight:500;width:22%">Mes</th>
              <th style="text-align:right;color:var(--text-secondary);font-weight:500;width:26%">Saldo</th>
              <th style="text-align:right;color:var(--text-secondary);font-weight:500;width:26%">Ingresos</th>
              <th style="text-align:right;color:var(--text-secondary);font-weight:500;width:26%">Variación</th>
            </tr></thead>
            <tbody>${monthly.map((m,i) => {
              const v = i === 0 ? null : m.bal - monthly[i-1].bal;
              const vc = v === null ? 'var-zero' : v >= 0 ? 'var-positive' : 'var-negative';
              const vs = v === null ? '—' : (v >= 0 ? '+' : '') + fmt(v);
              return `<tr style="border-bottom:.5px solid var(--border-light)">
                <td style="color:var(--text-primary)">${monthLabel(m.month)}</td>
                <td style="text-align:right;font-weight:500;color:var(--text-primary)">${fmt(m.bal)}</td>
                <td style="text-align:right;color:#0F6E56">${m.deposits ? '+'+fmt(m.deposits) : '—'}</td>
                <td style="text-align:right" class="${vc}">${vs}</td>
              </tr>`;
            }).join('')}</tbody>
          </table>
        </div>`;
    }
 
    /* ── REGISTRAR ── */
    function renderRegistro() {
      document.getElementById('sRegistro').innerHTML = `
        <div class="panel">
          <div class="ptitle">Registrar movimiento — ${kc().name}</div>
          <div class="form-row">
            <div class="fg" style="flex:2;min-width:120px">
              <label>Descripción</label>
              <input type="text" id="txDesc" placeholder="Ej: lavado de auto…" />
            </div>
            <div class="fg" style="max-width:130px">
              <label>Monto ($)</label>
              <input type="number" id="txAmt" placeholder="5000" min="1" />
            </div>
            <div class="fg" style="max-width:155px">
              <label>Fecha</label>
              <input type="date" id="txDate" value="${todayStr()}" />
            </div>
          </div>
          <div style="display:flex;gap:8px;flex-wrap:wrap">
            <button class="btn btn-g" onclick="addTx(1)">+ Ingreso</button>
            <button class="btn btn-r" onclick="addTx(-1)">− Descuento</button>
          </div>
        </div>`;
    }
 
    /* ── PROYECCIÓN ── */
    function renderProyeccion() {
      const txs = kids[sel].transactions;
      const fd = futureDate(6);
      document.getElementById('sProyeccion').innerHTML = `
        <div class="panel">
          <div class="ptitle">Proyección futura — ${kc().name}</div>
          <div class="proj-row">
            <div class="fg" style="max-width:200px">
              <label>¿Cuánto tendrá el…?</label>
              <input type="date" id="projDate" value="${fd}" onchange="updateProj()" />
            </div>
            <div class="proj-res">
              <span class="pval" id="projVal">${fmt(computeBalance(txs, fd))}</span>
              <span id="projLbl">al ${fmtDate(fd)}</span>
            </div>
          </div>
          <p style="font-size:13px;color:var(--text-secondary);margin-top:.875rem">
            Interés compuesto del 2% mensual aplicado hasta la fecha elegida.
          </p>
        </div>`;
    }
 
    function updateProj() {
      const d = document.getElementById('projDate')?.value;
      if (!d) return;
      const el = document.getElementById('projVal');
      const lb = document.getElementById('projLbl');
      if (el) el.textContent = fmt(computeBalance(kids[sel].transactions, d));
      if (lb) lb.textContent = 'al ' + fmtDate(d);
    }
 
    function addTx(sign) {
      const desc = document.getElementById('txDesc')?.value.trim();
      const amt  = parseFloat(document.getElementById('txAmt')?.value);
      const date = document.getElementById('txDate')?.value;
      if (!desc || !amt || amt <= 0 || !date) { alert('Completa todos los campos.'); return; }
      kids[sel].transactions.push({ id: Date.now().toString(), desc, amount: sign * amt, date });
      save(); renderAll();
      const d = document.getElementById('txDesc'); if (d) d.value = '';
      const a = document.getElementById('txAmt');  if (a) a.value = '';
    }
 
    function delTx(id) {
      kids[sel].transactions = kids[sel].transactions.filter(t => t.id !== id);
      save(); renderAll();
    }
 
    function selectKid(id) {
      sel = id;
      renderAll();
    }
 
    function switchTab(tab) {
      activeTab = tab;
      const tabs = ['resumen','grafico','registro','proyeccion'];
      document.querySelectorAll('.tab').forEach((t,i) => t.classList.toggle('active', tabs[i] === tab));
      document.querySelectorAll('.section').forEach(s => s.classList.remove('visible'));
      document.getElementById('s' + tab.charAt(0).toUpperCase() + tab.slice(1)).classList.add('visible');
      renderSection();
    }
 
    function renderSection() {
      if (activeTab === 'resumen')     renderResumen();
      else if (activeTab === 'grafico')     renderMonthlyChart();
      else if (activeTab === 'registro')    renderRegistro();
      else if (activeTab === 'proyeccion')  renderProyeccion();
    }
 
    function renderAll() {
      renderGrid();
      renderSection();
    }
 
    load();
  </script>
</body>
</html>
