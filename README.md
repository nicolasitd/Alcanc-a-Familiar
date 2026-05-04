function delTx(id) {
      kids[sel].transactions = kids[sel].transactions.filter(t => t.id !== id);
      save(); renderAll();
    }
 
    function selectKid(id) {
      sel = id;
      destroyCharts();
      renderAll();
    }
 
    function switchTab(tab) {
      activeTab = tab;
      const tabs = ['resumen','grafico','registro','proyeccion'];
      document.querySelectorAll('.tab').forEach((t,i) => t.classList.toggle('active', tabs[i] === tab));
      document.querySelectorAll('.section').forEach(s => s.classList.remove('visible'));
      document.getElementById('s' + tab.charAt(0).toUpperCase() + tab.slice(1)).classList.add('visible');
      destroyCharts();
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
