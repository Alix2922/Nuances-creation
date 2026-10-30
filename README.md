# Nuances-creation.index.html
Tissage artisanal conçu en France
<!doctype html>
<html lang="fr">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<meta name="description" content="Nuances Création, atelier de tissage d'art. Tissages sur mesure pour maisons de couture, décorateurs et boutiques de créateurs." />
<title>Nuances Création — Atelier de tissage d'art</title>
<style>
  :root {
    --noir: #0d0d0d;
    --noir-2: #161616;
    --ivoire: #f7f3ea;
    --or: #b08d4f;
    --or-clair: #d8bb7a;
    --gris: #6f675a;
    --blanc: #ffffff;
    --serif: "Cormorant Garamond", "Didot", Georgia, serif;
    --sans: "Jost", "Futura", "Helvetica Neue", Arial, sans-serif;
  }
  * { margin: 0; padding: 0; box-sizing: border-box; }
  html { scroll-behavior: smooth; }
  body {
    font-family: var(--sans);
    background: var(--ivoire);
    color: var(--noir);
    line-height: 1.65;
    -webkit-font-smoothing: antialiased;
  }
  h1, h2, h3, h4 { font-family: var(--serif); font-weight: 500; }
  h2 { font-size: clamp(1.7rem, 4.5vw, 2.6rem); line-height: 1.2; }
  .sur-titre {
    color: var(--or);
    font-size: .72rem;
    letter-spacing: .4em;
    text-transform: uppercase;
    margin-bottom: 1rem;
  }
  .chapeau { max-width: 560px; color: var(--gris); font-weight: 300; }
  section { padding: 4.5rem 1.5rem; }
  .conteneur { max-width: 1100px; margin: 0 auto; }
  .filet { width: 64px; height: 2px; background: var(--or); margin: 1.6rem 0; }

  /* Barre de navigation */
  header { position: fixed; top: 0; left: 0; right: 0; z-index: 20; background: rgba(13,13,13,.94); backdrop-filter: blur(10px); }
  nav { max-width: 1100px; margin: 0 auto; display: flex; align-items: center; justify-content: space-between; padding: .9rem 1.5rem; }
  .monogramme {
    font-family: var(--serif); font-size: 1.3rem; color: var(--or-clair);
    border: 1px solid var(--or); width: 2.4rem; height: 2.4rem;
    display: flex; align-items: center; justify-content: center;
    text-decoration: none; letter-spacing: 0;
  }
  .marque {
    color: var(--blanc); font-family: var(--serif);
    font-size: 1.05rem; letter-spacing: .14em; text-decoration: none;
  }
  .marque small { display: block; font-family: var(--sans); font-size: .55rem; letter-spacing: .35em; text-transform: uppercase; color: var(--or-clair); }
  nav ul { list-style: none; display: flex; gap: 1.5rem; align-items: center; }
  nav a.lien { color: #d9d2c2; text-decoration: none; font-size: .7rem; letter-spacing: .22em; text-transform: uppercase; transition: color .3s; }
  nav a.lien:hover { color: var(--or-clair); }
  .nav-devis { border: 1px solid var(--or); color: var(--or-clair) !important; padding: .55rem 1.2rem; transition: background .3s; }
  .nav-devis:hover { background: var(--or); }

  /* Bannière d'accueil */
  .accueil {
    min-height: 100vh; display: grid;
    grid-template-columns: 1.1fr 1fr;
    background:
      linear-gradient(rgba(13,13,13,.86), rgba(13,13,13,.9)),
      repeating-linear-gradient(45deg, #131313 0 2px, #0d0d0d 2px 10px);
    color: var(--blanc);
    padding-top: 6.5rem;
  }
  .accueil-texte { display: flex; flex-direction: column; justify-content: center; padding: 3rem 3rem 3rem 1.5rem; }
  .accueil-texte h1 { font-size: clamp(2.2rem, 6vw, 3.8rem); font-weight: 400; line-height: 1.1; letter-spacing: .03em; }
  .accueil-texte h1 em { font-style: italic; color: var(--or-clair); }
  .accueil-texte .chapeau { color: #cfc8b8; margin-top: 1.4rem; }
  .boutons { display: flex; gap: 1rem; flex-wrap: wrap; margin-top: 2.2rem; }
  .bouton {
    display: inline-block; text-decoration: none;
    font-size: .72rem; letter-spacing: .25em; text-transform: uppercase;
    padding: 1rem 2rem; transition: all .3s; text-align: center;
  }
  .bouton-or { background: var(--or); color: var(--blanc); }
  .bouton-or:hover { background: var(--or-clair); }
  .bouton-contour { border: 1px solid #7d766a; color: #d9d2c2; }
  .bouton-contour:hover { border-color: var(--or-clair); color: var(--or-clair); }

  /* Vitrine de pièces dans la bannière */
  .accueil-vitrine { display: grid; grid-template-columns: 1fr 1fr; align-content: center; gap: 1rem; padding: 3rem 1.5rem 3rem 0; }
  .piece-vitrine { background: var(--noir-2); border: 1px solid #262626; padding: 1.6rem 1.2rem; text-align: center; }
  .piece-vitrine .echevette {
    width: 74px; height: 74px; margin: 0 auto 1rem;
    background:
      repeating-linear-gradient(90deg, var(--or) 0 1px, transparent 1px 5px),
      repeating-linear-gradient(0deg, #8a6d38 0 1px, transparent 1px 5px);
    border-radius: 50%;
  }
  .piece-vitrine:nth-child(2) .echevette { background:
      repeating-linear-gradient(90deg, #d8dcd0 0 1px, transparent 1px 5px),
      repeating-linear-gradient(0deg, #9aa38e 0 1px, transparent 1px 5px); }
  .piece-vitrine:nth-child(3) .echevette { background:
      repeating-linear-gradient(90deg, #c9b7a4 0 1px, transparent 1px 5px),
      repeating-linear-gradient(0deg, #9c8468 0 1px, transparent 1px 5px); }
  .piece-vitrine h4 { color: var(--or-clair); font-size: 1.05rem; letter-spacing: .06em; }
  .piece-vitrine p { color: #b3ac9c; font-size: .8rem; letter-spacing: .12em; margin-top: .3rem; }

  /* Bandeau avantages */
  .avantages { background: var(--noir); padding: 2.2rem 1.5rem; }
  .avantages .conteneur { display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 1.5rem; text-align: center; }
  .avantage strong { display: block; font-family: var(--serif); font-weight: 500; font-size: 1.15rem; color: var(--or-clair); letter-spacing: .05em; }
  .avantage span { font-size: .72rem; letter-spacing: .2em; text-transform: uppercase; color: #8f887a; }

  /* Collections */
  .collections h2 { text-align: center; }
  .collections .sur-titre { text-align: center; }
  .grille-collections {
    display: grid; gap: 1.5rem; margin-top: 2.5rem;
    grid-template-columns: repeat(auto-fit, minmax(230px, 1fr));
  }
  .carte-collection {
    background: var(--blanc); border: 1px solid #e7dfcb;
    padding: 2.2rem 1.6rem; text-align: center;
    text-decoration: none; color: var(--noir);
    transition: transform .3s, border-color .3s;
  }
  .carte-collection:hover { transform: translateY(-5px); border-color: var(--or); }
  .carte-collection .monogramme-lettre {
    font-family: var(--serif); font-size: 2rem; color: var(--or);
    width: 64px; height: 64px; border: 1px solid #ddd3ba;
    display: flex; align-items: center; justify-content: center;
    margin: 0 auto 1.2rem; border-radius: 50%;
  }
  .carte-collection h3 { font-size: 1.25rem; margin-bottom: .5rem; }
  .carte-collection p { font-size: .88rem; color: var(--gris); }
  .carte-collection .mini { display: inline-block; margin-top: 1rem; font-size: .68rem; letter-spacing: .25em; text-transform: uppercase; color: var(--or); }

  /* Pièces à la carte */
  .pieces { background: var(--blanc); }
  .pieces h2 { text-align: center; }
  .pieces .sur-titre { text-align: center; }
  .pieces .chapeau { margin: 1rem auto 0; text-align: center; }
  .grille-pieces {
    display: grid; gap: 1.5rem; margin-top: 2.5rem;
    grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
  }
  .produit { border: 1px solid #e7dfcb; background: var(--ivoire); transition: transform .3s, border-color .3s; }
  .produit:hover { transform: translateY(-5px); border-color: var(--or); }
  .produit .visuel { aspect-ratio: 4/3; position: relative; }
  .produit .visuel.a { background: repeating-linear-gradient(90deg, #d9cfb6 0 2px, #f0e9d8 2px 9px); }
  .produit .visuel.b { background: repeating-linear-gradient(45deg, #b9c0b0 0 2px, #dde2d3 2px 9px); }
  .produit .visuel.c { background: repeating-linear-gradient(0deg, #cdb394 0 2px, #eadac2 2px 9px); }
  .produit .visuel.d { background: repeating-linear-gradient(90deg, #c6b8cc 0 2px, #e6dcea 2px 9px); }
  .produit .etiquette {
    position: absolute; top: .8rem; left: .8rem;
    background: var(--noir); color: var(--or-clair);
    font-size: .6rem; letter-spacing: .2em; text-transform: uppercase;
    padding: .3rem .6rem;
  }
  .produit .infos { padding: 1.2rem 1.2rem 1.4rem; text-align: center; }
  .produit h4 { font-size: 1.1rem; letter-spacing: .04em; }
  .produit .prix { font-size: .78rem; letter-spacing: .15em; color: var(--or); margin-top: .3rem; text-transform: uppercase; }
  .produit .matiere-fil { font-size: .75rem; color: var(--gris); margin-top: .5rem; }
  .centre { text-align: center; margin-top: 2.2rem; }

  /* Témoignage */
  .temoignage {
    background: var(--noir); color: var(--blanc); text-align: center;
  }
  .temoignage .guillemet { font-family: var(--serif); font-size: 4rem; color: var(--or); line-height: 1; }
  .temoignage blockquote { font-family: var(--serif); font-style: italic; font-size: clamp(1.15rem, 3vw, 1.7rem); max-width: 780px; margin: 1rem auto 1.6rem; font-weight: 400; }
  .temoignage .auteur { letter-spacing: .25em; text-transform: uppercase; font-size: .72rem; color: var(--or-clair); }
  .temoignage .role { font-size: .75rem; color: #8f887a; margin-top: .3rem; }

  /* Atelier */
  .atelier .conteneur { display: grid; grid-template-columns: 1fr 1fr; gap: 3rem; align-items: center; }
  .atelier .vignette {
    aspect-ratio: 4/5;
    background:
      repeating-linear-gradient(90deg, #d6cbae 0 3px, transparent 3px 15px),
      repeating-linear-gradient(0deg, #c4b795 0 2px, transparent 2px 17px),
      #efe7d4;
    border: 1px solid #ddd3ba;
  }
  .atelier h2 em { font-style: italic; color: var(--or); }
  .atelier .signature { font-family: var(--serif); font-style: italic; font-size: 1.25rem; color: var(--or); margin-top: 1.4rem; }

  /* Suivez-nous */
  .suivez { background: var(--blanc); text-align: center; }
  .suivez h2 { text-align: center; }
  .suivez .sur-titre { text-align: center; }
  .suivez .chapeau { margin: 1rem auto 0; }
  .insta {
    display: grid; gap: 1rem; margin-top: 2.2rem;
    grid-template-columns: repeat(auto-fit, minmax(150px, 1fr)); max-width: 700px; margin-left: auto; margin-right: auto;
  }
  .insta .tuile { aspect-ratio: 1; border: 1px solid #e7dfcb; }
  .insta .t1 { background: repeating-linear-gradient(90deg, #d9cfb6 0 3px, #f0e9d8 3px 11px); }
  .insta .t2 { background: repeating-linear-gradient(0deg, #b9c0b0 0 3px, #dde2d3 3px 11px); }
  .insta .t3 { background: repeating-linear-gradient(45deg, #cdb394 0 3px, #eadac2 3px 11px); }
  .insta .t4 { background: repeating-linear-gradient(90deg, #c6b8cc 0 3px, #e6dcea 3px 11px); }
  .insta .t5 { background: repeating-linear-gradient(0deg, #d9cfb6 0 3px, #efe7d4 3px 11px); }
  .insta .t6 { background: repeating-linear-gradient(90deg, #cdb394 0 3px, #eadac2 3px 11px); }

  /* Devis */
  .devis {
    background:
      linear-gradient(rgba(13,13,13,.87), rgba(13,13,13,.92)),
      repeating-linear-gradient(-45deg, #131313 0 2px, #0d0d0d 2px 10px);
    color: var(--blanc); text-align: center;
  }
  .devis h2 { color: var(--blanc); }
  .devis .sur-titre { color: var(--or-clair); }
  .devis .chapeau { color: #cfc8b8; margin: 1.2rem auto 2.2rem; }
  .devis .coordonnees { display: flex; gap: 2.5rem; justify-content: center; flex-wrap: wrap; margin-top: 2.5rem; font-size: .85rem; color: #8f887a; letter-spacing: .05em; }
  .devis .coordonnees a { color: var(--or-clair); text-decoration: none; }
  .devis .coordonnees a:hover { text-decoration: underline; }

  footer { background: var(--noir); color: #7d766a; text-align: center; padding: 1.5rem; font-size: .7rem; letter-spacing: .18em; text-transform: uppercase; border-top: 1px solid #222; }
  footer span { color: var(--or); }

  /* Réactif */
  @media (max-width: 860px) {
    .accueil { grid-template-columns: 1fr; }
    .accueil-vitrine { padding-left: 1.5rem; }
    .atelier .conteneur { grid-template-columns: 1fr; }
    .atelier .vignette { max-width: 380px; margin: 0 auto; order: -1; }
    nav a.lien:not(.nav-devis) { display: none; }
  }
</style>
</head>
<body>

<header>
  <nav>
    <div style="display:flex;align-items:center;gap:.9rem;">
      <a class="monogramme" href="#accueil" aria-label="Nuances Création — retour en haut">N</a>
      <a class="marque" href="#accueil">Nuances Création<small>Atelier de tissage d'art</small></a>
    </div>
    <ul>
      <li><a class="lien" href="#collections">Collections</a></li>
      <li><a class="lien" href="#pieces">Pièces</a></li>
      <li><a class="lien" href="#atelier">L'atelier</a></li>
      <li><a class="lien nav-devis" href="#devis">Demander un devis</a></li>
    </ul>
  </nav>
</header>

<section class="accueil" id="accueil">
  <div class="accueil-texte">
    <p class="sur-titre">Nouvelle collection tissée main</p>
    <h1>Tissages d'art<br /><em>en pièces uniques</em></h1>
    <p class="chapeau">Nuances Création tisse pour vous des étoffes et créations textiles sur mesure — pour les maisons de couture, les décorateurs et les boutiques de créateurs.</p>
    <div class="boutons">
      <a class="bouton bouton-or" href="#devis">Demander un devis gratuit</a>
      <a class="bouton bouton-contour" href="#collections">Découvrir les collections</a>
    </div>
  </div>
  <div class="accueil-vitrine">
    <div class="piece-vitrine"><div class="echevette"></div><h4>Étoffe de soie naturelle</h4><p>Pièce unique</p></div>
    <div class="piece-vitrine"><div class="echevette"></div><h4>Panneau en laine tissée</h4><p>Sur mesure</p></div>
    <div class="piece-vitrine"><div class="echevette"></div><h4>Tenture d'ameublement</h4><p>Série limitée</p></div>
    <div class="piece-vitrine"><div class="echevette"></div><h4>Écharpe de lin doré</h4><p>Création d'atelier</p></div>
  </div>
</section>

<div class="avantages">
  <div class="conteneur">
    <div class="avantage"><strong>Pièces uniques</strong><span>Tissées main, à votre image</span></div>
    <div class="avantage"><strong>Devis gratuit</strong><span>Réponse sous 48 heures</span></div>
    <div class="avantage"><strong>Matières nobles</strong><span>Soie, laine, lin</span></div>
    <div class="avantage"><strong>Suivi dédié</strong><span>De l'échantillon à la livraison</span></div>
  </div>
</div>

<section class="collections" id="collections">
  <div class="conteneur">
    <p class="sur-titre">Nos collections</p>
    <h2>Des créations pour chaque univers</h2>
    <div class="grille-collections">
      <a class="carte-collection" href="#devis">
        <div class="monogramme-lettre">C</div>
        <h3>Couture</h3>
        <p>Étoffes d'exception et tissages précieux pour les collections des maisons de couture.</p>
        <span class="mini">En savoir plus</span>
      </a>
      <a class="carte-collection" href="#devis">
        <div class="monogramme-lettre">D</div>
        <h3>Décoration</h3>
        <p>Tentures, panneaux et pièces d'ameublement pour décorateurs et architectes d'intérieur.</p>
        <span class="mini">En savoir plus</span>
      </a>
      <a class="carte-collection" href="#devis">
        <div class="monogramme-lettre">B</div>
        <h3>Boutiques</h3>
        <p>Créations signature en petites séries pour les boutiques de créateurs exigeantes.</p>
        <span class="mini">En savoir plus</span>
      </a>
      <a class="carte-collection" href="#devis">
        <div class="monogramme-lettre">S</div>
        <h3>Sur mesure</h3>
        <p>Un projet précis ? Nous tissons la pièce exacte que vous imaginez, du nuancier à la livraison.</p>
        <span class="mini">En savoir plus</span>
      </a>
    </div>
  </div>
</section>

<section class="pieces" id="pieces">
  <div class="conteneur">
    <p class="sur-titre">Sélection de l'atelier</p>
    <h2>Quelques pièces signature</h2>
    <p class="chapeau">Chaque création est tissée à la main dans l'atelier. D'autres pièces vous attendent sur demande.</p>
    <div class="grille-pieces">
      <article class="produit">
        <div class="visuel a"><span class="etiquette">Pièce unique</span></div>
        <div class="infos">
          <h4>Étoffe « Lumière d'or »</h4>
          <p class="prix">Sur devis</p>
          <p class="matiere-fil">Soie et fils métalliques dorés</p>
        </div>
      </article>
      <article class="produit">
        <div class="visuel b"><span class="etiquette">Série limitée</span></div>
        <div class="infos">
          <h4>Panneau « Herbier »</h4>
          <p class="prix">Sur devis</p>
          <p class="matiere-fil">Laine et lin naturel</p>
        </div>
      </article>
      <article class="produit">
        <div class="visuel c"><span class="etiquette">Sur mesure</span></div>
        <div class="infos">
          <h4>Tenture « Terre brûlée »</h4>
          <p class="prix">Sur devis</p>
          <p class="matiere-fil">Laine et coton bio</p>
        </div>
      </article>
      <article class="produit">
        <div class="visuel d"><span class="etiquette">Création</span></div>
        <div class="infos">
          <h4>Écharpe « Brume »</h4>
          <p class="prix">Sur devis</p>
          <p class="matiere-fil">Lin lavé et soie</p>
        </div>
      </article>
    </div>
    <p class="centre"><a class="bouton bouton-contour" style="color:var(--noir);border-color:#b9ad92;" href="#devis">Voir davantage — sur demande</a></p>
  </div>
</section>

<section class="temoignage">
  <div class="conteneur">
    <div class="guillemet">“</div>
    <blockquote>Nuances Création a tissé pour notre maison un tissage qui a sublimé toute la collection. Écoute rare, main d'une grande finesse, délais parfaitement tenus.</blockquote>
    <p class="auteur">— Diretrice de création</p>
    <p class="role">Maison de couture, Paris <em>(texte provisoire)</em></p>
  </div>
</section>

<section class="atelier" id="atelier">
  <div class="conteneur">
    <div class="vignette" role="img" aria-label="Évocation d'un tissage de l'atelier"></div>
    <div>
      <p class="sur-titre">L'atelier</p>
      <h2>Créons ensemble <em>quelque chose d'unique</em></h2>
      <div class="filet"></div>
      <p class="chapeau">Tisserande passionnée, je façonne à la main des pièces où chaque fil compte. Les techniques traditionnelles du tissage sont mises au service des créateurs, des maisons et des lieux qui recherchent l'irremplaçable.</p>
      <p class="chapeau">Ma démarche : des matières nobles, des colorations fines, une exigence absolue de finition — et l'écoute de vos désirs avant tout.</p>
      <p class="signature">— Lili, fondatrice de Nuances Création</p>
    </div>
  </div>
</section>

<section class="suivez" id="suivez">
  <div class="conteneur">
    <p class="sur-titre">Soyons inspirées</p>
    <h2>Suivez les créations de l'atelier</h2>
    <p class="chapeau">Échantillons, travaux en cours, coulisses du métier : les nuances de l'atelier au fil des saisons.</p>
    <div class="insta">
      <div class="tuile t1" role="img" aria-label="Échantillon de tissage"></div>
      <div class="tuile t2" role="img" aria-label="Fils de laine"></div>
      <div class="tuile t3" role="img" aria-label="Métier à tisser"></div>
      <div class="tuile t4" role="img" aria-label="Tenture en cours"></div>
      <div class="tuile t5" role="img" aria-label="Nuancier"></div>
      <div class="tuile t6" role="img" aria-label="Pièce achevée"></div>
    </div>
  </div>
</section>

<section class="devis" id="devis">
  <div class="conteneur">
    <p class="sur-titre">Devis gratuit et sans engagement</p>
    <h2>Donnons vie à votre projet</h2>
    <p class="chapeau">Racontez-nous votre pièce rêvée : dimensions, matières, ambiance. Nous vous répondons avec un chiffrage précis sous 48 heures.</p>
    <div class="boutons" style="justify-content:center;">
      <a class="bouton bouton-or" href="mailto:contact@nuances-creation.fr?subject=Demande%20de%20devis">Demander mon devis gratuit</a>
    </div>
    <div class="coordonnees">
      <span>Atelier — Région de Bordeaux <em>(à préciser)</em></span>
      <a href="mailto:contact@nuances-creation.fr">contact@nuances-creation.fr</a>
      <a href="tel:+33600000000">+33 6 00 00 00 00</a>
    </div>
  </div>
</section>

<footer>
  © 2026 Nuances Création — Atelier de tissage d'art · <span>L'exception, fil après fil</span>
</footer>

</body>
</html>
