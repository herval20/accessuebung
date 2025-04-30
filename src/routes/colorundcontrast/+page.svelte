
<style>
    .bg-rainbow {
      background-image: linear-gradient(-60deg, #735DA5 50%, #D3C5E5 50%);
      animation: slide 9s ease-in-out infinite alternate;
      animation-play-state: running;
    }
    .bg-rainbow2 {
      animation-direction: alternate-reverse;
      animation-duration: 10s;
    }
    .bg-rainbow3 {
      animation-duration: 11s;
    }

    .content-wrapper {
      margin-top: 80px;
    }
</style>
  

<div class="fixed inset-0 -z-10 opacity-50 bg-rainbow"></div>
<div class="fixed inset-0 -z-10 opacity-50 bg-rainbow bg-rainbow2"></div>
<div class="fixed inset-0 -z-10 opacity-50 bg-rainbow bg-rainbow3"></div>

<div class="h-24"></div>


<div class="content-wrapper relative top-100 left-230 left-1/2 top-1/2 transform -translate-x-1/2 -translate-y-1/2 bg-white/80 rounded shadow-md p-10 text-center max-w-3xl mt-20">
    <h1 class="text-5xl font-bold" style="color: #735DA5;">Color und Contrast</h1>
  
  
    <p class="text-lg text-gray-700 mb-4">
      <b class="color: #735DA5;">Einführung</b><br>
      Das Verständnis von Farbe und Kontrast ist entscheidend für barrierefreies Design, um Menschen mit verschiedenen Sehbeeinträchtigungen zu unterstützen. Menschen nehmen Farben anhand von Lichtwellenlängen wahr, und diese Wahrnehmung kann durch Faktoren wie Helligkeit, Sättigung und Farbton beschrieben werden (HSL-Modell).
    </p>
  
    <p class="text-lg text-gray-700 mb-4">
      <b>Farbkontrast und seine Bedeutung</b><br>
      Farbkontrast ist wichtig, um Text auf dem Bildschirm gut lesbar zu machen. Ein zu geringer Kontrast kann dazu führen, dass Inhalte schwer zu erkennen sind, besonders für Menschen mit Sehbehinderungen. Eine Formel zur Berechnung des Farbkontrasts nutzt die relative Leuchtkraft von Farben, wobei ein Verhältnis von 21:1 (Schwarz auf Weiß) den höchsten Kontrast darstellt.
    </p>
  
    <p class="text-lg text-gray-700 mb-4">
      Um Barrierefreiheit zu gewährleisten, sollten Textgrößen und wichtige Symbole mindestens ein Farbkontrastverhältnis von 4.5:1 erreichen.
    </p>
  
    <p class="text-lg text-gray-700 mb-4">
      <b>Zusätzliche visuelle Indikatoren</b><br>
      Es ist auch wichtig, dass Farben nicht als einzige visuelle Information verwendet werden. Für Menschen mit Farbfehlsichtigkeit sollten zusätzlich andere Indikatoren wie Muster oder Symbole eingebaut werden, damit die Nutzer die Inhalte besser verstehen können.
    </p>
  
    <p class="text-lg text-gray-700 mb-4">
      <b>Medienabfragen für eine bessere Anpassung</b><br>
      Medienabfragen wie <code>@prefers-color-scheme</code> und <code>@prefers-contrast</code> ermöglichen es, Designs anzupassen. Nutzer können zwischen hellen und dunklen Modi oder hohem Kontrast wählen, was die Zugänglichkeit weiter erhöht.
    </p>
  
    <p class="text-lg text-gray-700 mb-4">
      <b>Fazit</b><br>
      Zusammenfassend lässt sich sagen, dass Designer und Entwickler sicherstellen sollten, dass ihre Designs die richtigen Kontraste aufweisen und zusätzliche Anpassungsoptionen bieten, um die Benutzerfreundlichkeit und Barrierefreiheit für alle zu gewährleisten.
    </p>
  </div>
  