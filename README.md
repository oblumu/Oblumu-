<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Apprendre HTML</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Apprendre HTML</h1>
    <p>Un guide interactif pour comprendre les bases du HTML étape par étape.</p>
  </header>

  <main>
    <!-- Introduction : C'est quoi HTML -->
    <section id="introduction">
      <h2>C'est quoi HTML ?</h2>
      <img src="./Assets/images/jpg/ju.jpg" alt="">
      <strong>
        HTML (HyperText Markup Language) est le langage utilisé pour structurer le contenu des pages web. Il sert à définir la structure des éléments tels que les titres, paragraphes, images, vidéos, liens, et bien plus.
      </strong>
      <p>
        Chaque page web que vous voyez sur Internet utilise HTML pour organiser son contenu.
      </p>
    </section>

    <!-- Structure de base -->
    <section id="structure-base">
        <img src="./Assets/images/jpg/gt jpg" alt="">
      <h2>La Structure de Base d'une Page HTML</h2>
      <p>Voici à quoi ressemble la structure minimale d'une page HTML :</p>
      <pre>
<code>
&lt;!DOCTYPE html&gt;
&lt;html lang="fr"&gt;
&lt;head&gt;
  &lt;meta charset="UTF-8"&gt;
  &lt;meta name="viewport" content="width=device-width, initial-scale=1.0"&gt;
  &lt;title&gt;Ajouter un titre&lt;/title&gt;
&lt;/head&gt;
&lt;body&gt;
 
&lt;/body&gt;
&lt;/html&gt;
</code>
      </pre>
      <p>Chaque page HTML commence par <code>&lt;!DOCTYPE html&gt;</code>, qui indique au navigateur que nous utilisons HTML5.</p>
    </section>

    <!-- Les balises HTML -->
    <section id="balises-html">
      <h2>Qu'est-ce qu'une Balise HTML ?</h2>
      <p>
        Les balises sont les éléments fondamentaux d'une page HTML. Elles sont toujours entourées de chevrons : <code>&lt;&gt;</code>.
      </p>
      <ul>
        <li><code>&lt;h1&gt;</code> : Titre principal.</li>
        <li><code>&lt;p&gt;</code> : Paragraphe.</li>
        <li><code>&lt;img&gt;</code> : Image.</li>
        <li><code>&lt;a&gt;</code> : Lien.</li>
      </ul>
      <p>Les balises fonctionnent souvent par paires : une balise d'ouverture (<code>&lt;h1&gt;</code>) et une balise de fermeture (<code>&lt;/h1&gt;</code>).</p>
    </section>

    <!-- Les Titres -->
    <section id="titres">
      <h2>Les Titres</h2>
      <p>HTML propose 6 niveaux de titres, du plus important (<code>&lt;h1&gt;</code>) au moins important (<code>&lt;h6&gt;</code>) :</p>
      <h1>Titre H1 (le plus grand)</h1>
      <h2>Titre H2</h2>
      <h3>Titre H3</h3>
      <h4>Titre H4</h4>
      <h5>Titre H5</h5>
      <h6>Titre H6 (le plus petit)</h6>
    </section>

    <!-- Les Paragraphes et Texte -->
    <section id="texte">
      <h2>Les Paragraphes et le Texte</h2>
      <p>Utilisez la balise <code>&lt;p&gt;</code> pour définir un paragraphe :</p>
      <p>Ceci est un exemple de paragraphe.</p>
      <p>Vous pouvez également styliser le texte :</p>
      <ul>
        <li><strong>Gras</strong> avec <code>&lt;strong&gt;</code> ou <code>&lt;b&gt;</code>.</li>
        <li><em>Italique</em> avec <code>&lt;em&gt;</code> ou <code>&lt;i&gt;</code>.</li>
        <li><u>Souligné</u> avec <code>&lt;u&gt;</code>.</li>
      </ul>
    </section>

    <!-- Les Images -->
    <section id="images">
      <h2>Les Images</h2>
      <p>Ajoutez une image avec la balise <code>&lt;img&gt;</code> :</p><!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Apprendre HTML</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Apprendre HTML</h1>
    <p>Un guide interactif pour comprendre les bases du HTML étape par étape.</p>
  </header>

  <main>
    <!-- Introduction : C'est quoi HTML -->
    <section id="introduction">
      <h2>C'est quoi HTML ?</h2>
      <img src="./Assets/images/jpg/ju.jpg" alt="">
      <strong>
        HTML (HyperText Markup Language) est le langage utilisé pour structurer le contenu des pages web. Il sert à définir la structure des éléments tels que les titres, paragraphes, images, vidéos, liens, et bien plus.
      </strong>
      <p>
        Chaque page web que vous voyez sur Internet utilise HTML pour organiser son contenu.
      </p>
    </section>

    <!-- Structure de base -->
    <section id="structure-base">
        <img src="./Assets/images/jpg/gt jpg" alt="">
      <h2>La Structure de Base d'une Page HTML</h2>
      <p>Voici à quoi ressemble la structure minimale d'une page HTML :</p>
      <pre>
<code>
&lt;!DOCTYPE html&gt;
&lt;html lang="fr"&gt;
&lt;head&gt;
  &lt;meta charset="UTF-8"&gt;
  &lt;meta name="viewport" content="width=device-width, initial-scale=1.0"&gt;
  &lt;title&gt;Ajouter un titre&lt;/title&gt;
&lt;/head&gt;
&lt;body&gt;
 
&lt;/body&gt;
&lt;/html&gt;
</code>
      </pre>
      <p>Chaque page HTML commence par <code>&lt;!DOCTYPE html&gt;</code>, qui indique au navigateur que nous utilisons HTML5.</p>
    </section>

    <!-- Les balises HTML -->
    <section id="balises-html">
      <h2>Qu'est-ce qu'une Balise HTML ?</h2>
      <p>
        Les balises sont les éléments fondamentaux d'une page HTML. Elles sont toujours entourées de chevrons : <code>&lt;&gt;</code>.
      </p>
      <ul>
        <li><code>&lt;h1&gt;</code> : Titre principal.</li>
        <li><code>&lt;p&gt;</code> : Paragraphe.</li>
        <li><code>&lt;img&gt;</code> : Image.</li>
        <li><code>&lt;a&gt;</code> : Lien.</li>
      </ul>
      <p>Les balises fonctionnent souvent par paires : une balise d'ouverture (<code>&lt;h1&gt;</code>) et une balise de fermeture (<code>&lt;/h1&gt;</code>).</p>
    </section>

    <!-- Les Titres -->
    <section id="titres">
      <h2>Les Titres</h2>
      <p>HTML propose 6 niveaux de titres, du plus important (<code>&lt;h1&gt;</code>) au moins important (<code>&lt;h6&gt;</code>) :</p>
      <h1>Titre H1 (le plus grand)</h1>
      <h2>Titre H2</h2>
      <h3>Titre H3</h3>
      <h4>Titre H4</h4>
      <h5>Titre H5</h5>
      <h6>Titre H6 (le plus petit)</h6>
    </section>

    <!-- Les Paragraphes et Texte -->
    <section id="texte">
      <h2>Les Paragraphes et le Texte</h2>
      <p>Utilisez la balise <code>&lt;p&gt;</code> pour définir un paragraphe :</p>
      <p>Ceci est un exemple de paragraphe.</p>
      <p>Vous pouvez également styliser le texte :</p>
      <ul>
        <li><strong>Gras</strong> avec <code>&lt;strong&gt;</code> ou <code>&lt;b&gt;</code>.</li>
        <li><em>Italique</em> avec <code>&lt;em&gt;</code> ou <code>&lt;i&gt;</code>.</li>
        <li><u>Souligné</u> avec <code>&lt;u&gt;</code>.</li>
      </ul>
    </section>

    <!-- Les Images -->
    <section id="images">
      <h2>Les Images</h2>
      <p>Ajoutez une image avec la balise <code>&lt;img&gt;</code> :</p>
      <img src="./Assets/images/jpg/chrome.jpg" alt="Exemple d'image" />
      <p>Syntaxe : <code>&lt;img src="URL" alt="Description"&gt;</code></p>
    </section>

    <!-- Les Liens -->
    <section id="liens">
      <h2>Les Liens</h2>
      <p>Ajoutez un lien hypertexte avec la balise <code>&lt;a&gt;</code> :</p>
      <a href="https://www.w3schools.com/html/" target="_blank">En savoir plus sur HTML</a>
      <p>Syntaxe : <code>&lt;a href="URL"&gt;Texte du lien&lt;/a&gt;</code></p>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 Apprendre HTML - Tous droits réservés</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>￼Enter
