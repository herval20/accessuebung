
<style>
    .bg-rainbow {
      background-image: linear-gradient(-60deg, #735DA5 50%, #D3C5E5 50%);
     
    }
</style>
  

<div class="fixed inset-0 -z-10 opacity-50 bg-rainbow"></div>
<div class="fixed inset-0 -z-10 opacity-50 bg-rainbow bg-rainbow2"></div>
<div class="fixed inset-0 -z-10 opacity-50 bg-rainbow bg-rainbow3"></div>


<div class="h-24"></div>


<div class="content-wrapper relative top-125 left-230 top-110 left-1/2 top-1/2 transform -translate-x-1/2 -translate-y-1/2 bg-white/80 rounded shadow-md p-10 text-center max-w-3xl">
    <h1 class="text-5xl font-bold" style="color: #735DA5;">Animation und Bewegung</h1>
  
    <p class="text-lg text-gray-700 mb-4">
      <b>Bewegte und blinkende Inhalte</b><br>
      Animationen und bewegte Inhalte können für Nutzer mit vestibulären Störungen oder Bewegungsempfindlichkeiten problematisch sein. Etwa 35% der Erwachsenen über 40 Jahren leiden an einer Form von vestibulärer Dysfunktion, die Schwindel oder Migräne verursachen kann. Auch Menschen mit ADHD können von bewegten, blinkenden oder scrollenden Inhalten abgelenkt werden.
    </p>
  
    <p class="text-lg text-gray-700 mb-4">
      <b>Empfohlene Richtlinien</b><br>
      Schnelle Bewegungen oder blinkende Inhalte können bei Menschen mit photosensitiver Epilepsie Anfälle auslösen. Die WCAG-Richtlinien empfehlen, dass Inhalte nicht mehr als dreimal pro Sekunde blinken und keine schnellen Farbwechsel aufweisen, um gesundheitliche Risiken zu vermeiden. Tools wie das <code>Photosensitive Epilepsy Analysis Tool (PEAT)</code> helfen, potenziell gefährliche Inhalte zu identifizieren.
    </p>
  
    <p class="text-lg text-gray-700 mb-4">
      <b>Vermeidung unnötiger Bewegungen</b><br>
      Wenn Bewegungen nicht notwendig für das Verständnis der Inhalte sind, sollten sie entfernt oder deaktiviert werden. Wenn sie nicht entfernt werden können, sollten Nutzer die Möglichkeit haben, Bewegungen zu pausieren oder auszublenden. Dies gilt insbesondere für Inhalte, die automatisch gestartet werden und länger als fünf Sekunden dauern.
    </p>
  
    <p class="text-lg text-gray-700 mb-4">
      <b>Medienabfragen für reduzierte Bewegung</b><br>
      Mit der CSS-Medienabfrage <code>@prefers-reduced-motion</code> können Designern und Entwicklern ermöglichen, Animationen basierend auf den Systemeinstellungen des Nutzers zu reduzieren oder zu deaktivieren. Nutzer können in ihren Betriebssystemeinstellungen entscheiden, ob sie Animationen sehen möchten.
    </p>
  
    <p class="text-lg text-gray-700 mb-4">
      <b>Benutzersteuerung</b><br>
      Fügen Sie Steuerelemente wie eine Ein/Aus-Schaltfläche hinzu, mit der Nutzer Animationen aktivieren oder deaktivieren können. Diese Schaltfläche sollte standardmäßig auf "Aus" eingestellt sein. Weitere Medienabfragen wie <code>@prefers-color-scheme</code> und <code>@prefers-contrast</code> können ebenfalls verwendet werden, um die Benutzererfahrung noch weiter anzupassen.
    </p>
  
    <p class="text-lg text-gray-700 mb-4">
      <b>Fazit</b><br>
      Um Barrierefreiheit zu gewährleisten, sollten Designer Bewegungen in digitalen Designs mit Bedacht einsetzen und den Nutzern die Kontrolle über Animationen ermöglichen. Die Berücksichtigung von reduzierter Bewegung hilft, Probleme für Menschen mit Bewegungsempfindlichkeit oder anderen gesundheitlichen Einschränkungen zu vermeiden.
    </p>
</div>
