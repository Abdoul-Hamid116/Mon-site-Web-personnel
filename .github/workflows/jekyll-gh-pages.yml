<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Michaou Issa Abdoul Hamidou — Comptable & Analyste Financier</title>
<style>
  * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Segoe UI', Arial, sans-serif; }

  :root {
    --bleu: #1a73e8;
    --bleu-fonce: #0d47a1;
    --accent: #ff6d00;
    --fond: #f5f7fa;
    --texte: #212121;
  }

  html { scroll-behavior: smooth; }
  body { background: var(--fond); color: var(--texte); line-height: 1.6; }

  /* ===== NAVIGATION ===== */
  nav {
    background: rgba(13, 71, 161, .97);
    position: sticky;
    top: 0;
    z-index: 100;
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 14px 5%;
    box-shadow: 0 2px 10px rgba(0,0,0,.25);
  }
  nav .logo { color: #fff; font-weight: 800; font-size: 1.2rem; }
  nav .logo span { color: var(--accent); }
  nav .liens { display: flex; gap: 22px; }
  nav .liens a { color: #e3f2fd; text-decoration: none; font-weight: 600; font-size: .95rem; }
  nav .liens a:hover { color: var(--accent); }
  nav .menu-mobile { display: none; background: none; border: none; color: #fff; font-size: 1.6rem; cursor: pointer; }

  @media (max-width: 720px) {
    nav .liens {
      display: none;
      position: absolute;
      top: 100%;
      left: 0; right: 0;
      background: var(--bleu-fonce);
      flex-direction: column;
      padding: 16px;
      gap: 14px;
    }
    nav .liens.ouvert { display: flex; }
    nav .menu-mobile { display: block; }
  }

  /* ===== HERO ===== */
  .hero {
    background: linear-gradient(135deg, var(--bleu-fonce), var(--bleu));
    color: #fff;
    text-align: center;
    padding: 90px 20px 70px;
  }
  .hero .avatar {
    width: 120px; height: 120px;
    border-radius: 50%;
    background: #fff;
    margin: 0 auto 20px;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 3.4rem;
    box-shadow: 0 0 0 6px rgba(255,255,255,.25);
  }
  .hero h1 { font-size: 2.4rem; margin-bottom: 8px; }
  .hero h1 span { color: var(--accent); }
  .hero .sous-titre { font-size: 1.15rem; opacity: .92; margin-bottom: 10px; }
  .hero .badges { display: flex; gap: 10px; justify-content: center; flex-wrap: wrap; margin: 22px 0 30px; }
  .hero .badge {
    background: rgba(255,255,255,.15);
    border: 1px solid rgba(255,255,255,.4);
    padding: 7px 16px;
    border-radius: 20px;
    font-size: .88rem;
  }
  .btn-blanc {
    display: inline-block;
    background: var(--accent);
    color: #fff;
    padding: 13px 32px;
    border-radius: 30px;
    text-decoration: none;
    font-weight: 700;
    transition: transform .2s;
  }
  .btn-blanc:hover { transform: scale(1.06); }
  .btn-ligne {
    display: inline-block;
    margin-left: 10px;
    color: #fff;
    border: 2px solid #fff;
    padding: 11px 30px;
    border-radius: 30px;
    text-decoration: none;
    font-weight: 700;
    transition: background .2s;
  }
  .btn-ligne:hover { background: rgba(255,255,255,.15); }

  /* ===== SECTIONS ===== */
  section { padding: 60px 5%; max-width: 1100px; margin: 0 auto; }
  h2.titre { text-align: center; font-size: 1.9rem; color: var(--bleu-fonce); margin-bottom: 8px; }
  .sous-titre-section { text-align: center; color: #78909c; margin-bottom: 40px; }

  /* ===== À PROPOS ===== */
  .apropos { display: flex; gap: 30px; align-items: center; flex-wrap: wrap; }
  .apropos .carte-texte {
    flex: 1;
    min-width: 280px;
    background: #fff;
    border-radius: 14px;
    padding: 30px;
    box-shadow: 0 3px 14px rgba(0,0,0,.07);
  }
  .apropos .carte-texte h3 { color: var(--bleu-fonce); margin-bottom: 12px; }
  .apropos .chiffres { flex: 1; min-width: 260px; display: grid; grid-template-columns: 1fr 1fr; gap: 16px; }
  .apropos .chiffre {
    background: #fff;
    border-radius: 14px;
    padding: 22px 12px;
    text-align: center;
    box-shadow: 0 3px 14px rgba(0,0,0,.07);
  }
  .apropos .chiffre .valeur { font-size: 1.7rem; font-weight: 800; color: var(--bleu); }
  .apropos .chiffre .libelle { font-size: .85rem; color: #78909c; }

  /* ===== DIPLÔMES ===== */
  .diplomes { display: flex; flex-direction: column; gap: 18px; }
  .diplome {
    background: #fff;
    border-radius: 12px;
    padding: 22px 26px;
    border-left: 6px solid var(--bleu);
    box-shadow: 0 2px 10px rgba(0,0,0,.06);
    display: flex;
    align-items: center;
    gap: 20px;
  }
  .diplome .icone { font-size: 2.2rem; }
  .diplome h3 { font-size: 1.1rem; }
  .diplome .mention {
    display: inline-block;
    background: #e8f5e9;
    color: #2e7d32;
    font-size: .8rem;
    font-weight: 700;
    padding: 3px 12px;
    border-radius: 12px;
    margin-top: 6px;
  }

  /* ===== COMPÉTENCES ===== */
  .competences { display: grid; grid-template-columns: repeat(auto-fill, minmax(240px, 1fr)); gap: 18px; }
  .competence {
    background: #fff;
    border-radius: 12px;
    padding: 22px;
    box-shadow: 0 2px 10px rgba(0,0,0,.06);
    display: flex;
    gap: 14px;
    align-items: flex-start;
    transition: transform .2s;
  }
  .competence:hover { transform: translateY(-4px); }
  .competence .icone { font-size: 1.9rem; }
  .competence h3 { font-size: 1rem; margin-bottom: 4px; color: var(--bleu-fonce); }
  .competence p { font-size: .88rem; color: #616161; }

  /* ===== SERVICES ===== */
  .services { display: grid; grid-template-columns: repeat(auto-fill, minmax(260px, 1fr)); gap: 22px; }
  .service {
    background: #fff;
    border-radius: 14px;
    padding: 28px 24px;
    box-shadow: 0 3px 14px rgba(0,0,0,.07);
    text-align: center;
    position: relative;
    transition: transform .2s;
  }
  .service:hover { transform: translateY(-5px); }
  .service .icone { font-size: 2.4rem; margin-bottom: 10px; }
  .service h3 { color: var(--bleu-fonce); margin-bottom: 8px; }
  .service .prix { font-size: 1.4rem; font-weight: 800; color: var(--accent); margin: 10px 0; }
  .service ul { list-style: none; text-align: left; margin-bottom: 18px; }
  .service li { font-size: .88rem; padding: 4px 0; color: #555; }
  .service li::before { content: "✅ "; }
  .service .btn-service {
    background: var(--bleu);
    color: #fff;
    border: none;
    padding: 11px 24px;
    border-radius: 8px;
    font-weight: 700;
    cursor: pointer;
    text-decoration: none;
    display: inline-block;
  }
  .service .btn-service:hover { background: var(--bleu-fonce); }
  .service.populaire { border: 2px solid var(--accent); }
  .service .etiquette {
    position: absolute;
    top: -12px;
    left: 50%;
    transform: translateX(-50%);
    background: var(--accent);
    color: #fff;
    font-size: .75rem;
    font-weight: 700;
    padding: 4px 14px;
    border-radius: 12px;
    white-space: nowrap;
  }

  /* ===== CONTACT ===== */
  .contact-boite {
    background: linear-gradient(135deg, var(--bleu-fonce), var(--bleu));
    color: #fff;
    border-radius: 16px;
    padding: 44px 30px;
    text-align: center;
  }
  .contact-boite h2 { margin-bottom: 10px; }
  .contact-boite p { opacity: .9; margin-bottom: 26px; }
  .contact-boite .moyens { display: flex; gap: 14px; justify-content: center; flex-wrap: wrap; }
  .contact-boite a.moyen {
    background: rgba(255,255,255,.15);
    border: 1px solid rgba(255,255,255,.4);
    color: #fff;
    text-decoration: none;
    padding: 12px 26px;
    border-radius: 10px;
    font-weight: 600;
  }
  .contact-boite a.moyen:hover { background: rgba(255,255,255,.28); }

  footer { background: #102027; color: #b0bec5; text-align: center; padding: 26px; font-size: .9rem; }
  footer strong { color: #fff; }
</style>
</head>
<body>

<!-- NAVIGATION -->
<nav>
  <div class="logo">Michaou <span>Hamidou</span></div>
  <button class="menu-mobile" onclick="document.querySelector('.liens').classList.toggle('ouvert')">☰</button>
  <div class="liens">
    <a href="#apropos">À propos</a>
    <a href="#diplomes">Diplômes</a>
    <a href="#competences">Compétences</a>
    <a href="#services">Services</a>
    <a href="#contact">Contact</a>
  </div>
</nav>

<!-- HERO -->
<div class="hero">
  <div class="avatar">👨‍💼</div>
  <h1>Michaou Issa Abdoul <span>Hamidou</span></h1>
  <p class="sous-titre">Étudiant à l'ENCG Béni Mellal — Comptable & Analyste Financier</p>
  <div class="badges">
    <span class="badge">🎓 Excellence académique</span>
    <span class="badge">📋 Comptabilité & Bilans</span>
    <span class="badge">📊 Analyse financière</span>
    <span class="badge">💰 Évaluation d'entreprise</span>
  </div>
  <a href="#services" class="btn-blanc">Découvrir mes services</a>
  <a href="#contact" class="btn-ligne">Me contacter</a>
</div>

<!-- À PROPOS -->
<section id="apropos">
  <h2 class="titre">À propos de moi</h2>
  <p class="sous-titre-section">Qui suis-je et ce que je peux apporter</p>
  <div class="apropos">
    <div class="carte-texte">
      <h3>👋 Bonjour !</h3>
      <p>
        Je suis étudiant à l'<strong>ENCG Béni Mellal</strong>, admis grâce à mon excellence académique.
        Passionné par la comptabilité et la finance, j'aide les petits commerces, auto-entrepreneurs
        et particuliers à <strong>maîtriser leurs chiffres</strong> : factures, journaux, bilans,
        résultats, stocks et suivi de rentabilité.
      </p>
      <p style="margin-top:12px">
        Ma mission : rendre la comptabilité <strong>simple, claire et utile</strong> pour chacun —
        avec des outils modernes et des explications que tout le monde peut comprendre.
      </p>
    </div>
    <div class="chiffres">
      <div class="chiffre"><div class="valeur">3</div><div class="libelle">Diplômes avec mention</div></div>
      <div class="chiffre"><div class="valeur">10+</div><div class="libelle">Compétences maîtrisées</div></div>
      <div class="chiffre"><div class="valeur">100%</div><div class="libelle">Rigueur & confidentialité</div></div>
      <div class="chiffre"><div class="valeur">24h</div><div class="libelle">Délai de réponse</div></div>
    </div>
  </div>
</section>

<!-- DIPLÔMES -->
<section id="diplomes">
  <h2 class="titre">🎓 Mes Diplômes & Attestations</h2>
  <p class="sous-titre-section">Un parcours bâti sur l'excellence</p>
  <div class="diplomes">
    <div class="diplome">
      <div class="icone">🏫</div>
      <div>
        <h3>BEP Comptable</h3>
        <span class="mention">🏅 Mention Bien</span>
      </div>
    </div>
    <div class="diplome">
      <div class="icone">📝</div>
      <div>
        <h3>CAP Aide / Assistant Comptable</h3>
        <span class="mention">🏅 Mention Très Bien</span>
      </div>
    </div>
    <div class="diplome">
      <div class="icone">🎯</div>
      <div>
        <h3>Bac Technique Quantitative de Gestion</h3>
        <span class="mention">🏅 Mention Très Bien</span>
      </div>
    </div>
    <div class="diplome">
      <div class="icone">🏛️</div>
      <div>
        <h3>Étudiant à l'ENCG Béni Mellal</h3>
        <span class="mention">📍 En cours — admission sur excellence académique</span>
      </div>
    </div>
  </div>
</section>

<!-- COMPÉTENCES -->
<section id="competences">
  <h2 class="titre">💼 Mes Compétences</h2>
  <p class="sous-titre-section">Ce que je sais faire — et que je fais bien</p>
  <div class="competences">
    <div class="competence"><div class="icone">🧾</div><div><h3>Factures & Journaux comptables</h3><p>Établissement de factures, journaux, grands livres et balances conformes.</p></div></div>
    <div class="competence"><div class="icone">⚖️</div><div><h3>Bilans & États financiers</h3><p>Préparation et lecture de bilans clairs pour une vision exacte de l'activité.</p></div></div>
    <div class="competence"><div class="icone">🏭</div><div><h3>Calcul des coûts de production</h3><p>Coûts industriels et commerciaux, quelle que soit leur complexité.</p></div></div>
    <div class="competence"><div class="icone">📈</div><div><h3>Analyse financière & conseils</h3><p>Analyse des chiffres et recommandations concrètes pour améliorer la rentabilité.</p></div></div>
    <div class="competence"><div class="icone">🏢</div><div><h3>Évaluation d'entreprise</h3><p>Évaluation de la valeur d'une entreprise, quelle que soit sa taille ou sa croissance.</p></div></div>
    <div class="competence"><div class="icone">💡</div><div><h3>Résultats expliqués en détail</h3><p>Calcul précis des profits et pertes — avec les raisons qui les expliquent.</p></div></div>
    <div class="competence"><div class="icone">📅</div><div><h3>Amortissements</h3><p>Calcul des amortissements et autres opérations comptables courantes.</p></div></div>
    <div class="competence"><div class="icone">🤖</div><div><h3>Maîtrise des IA & outils numériques</h3><p>Utilisation avancée de l'intelligence artificielle pour un travail rapide et fiable.</p></div></div>
  </div>
</section>

<!-- SERVICES -->
<section id="services">
  <h2 class="titre">🛠️ Mes Services</h2>
  <p class="sous-titre-section">Des offres claires, adaptées aux petits budgets</p>
  <div class="services">
    <div class="service">
      <div class="icone">🧾</div>
      <h3>Factures & Documents</h3>
      <div class="prix">Dès 30 DH</div>
      <ul>
        <li>Facture professionnelle</li>
        <li>Journal comptable mensuel</li>
        <li>Grand livre & balance</li>
        <li>Livraison rapide</li>
      </ul>
      <a class="btn-service" href="#contact">Commander</a>
    </div>
    <div class="service populaire">
      <span class="etiquette">⭐ Populaire</span>
      <div class="icone">📊</div>
      <h3>Tableau de bord complet</h3>
      <div class="prix">Dès 250 DH</div>
      <ul>
        <li>Fichier de gestion personnalisé</li>
        <li>Ventes, charges & résultat automatiques</li>
        <li>Suivi des stocks + alertes</li>
        <li>1 heure de formation incluse</li>
      </ul>
      <a class="btn-service" href="#contact">Commander</a>
    </div>
    <div class="service">
      <div class="icone">🧠</div>
      <h3>Analyse & Conseils</h3>
      <div class="prix">Dès 100 DH</div>
      <ul>
        <li>Calcul du résultat détaillé</li>
        <li>Explication des pertes/profits</li>
        <li>Conseils pour améliorer la marge</li>
        <li>Rapport simple et clair</li>
      </ul>
      <a class="btn-service" href="#contact">Commander</a>
    </div>
  </div>
</section>

<!-- CONTACT -->
<section id="contact">
  <div class="contact-boite">
    <h2>📬 Parlons de vos chiffres !</h2>
    <p>Première question gratuite — je réponds en moins de 24h.</p>
    <div class="moyens">
      <a class="moyen" href="https://wa.me/212785216184">📱 WhatsApp : 0785 216 184</a>
      <a class="moyen" href="mailto:michaouissaabdoulhamidou@gmail.com">✉️ Email</a>
      <a class="moyen" href="tel:+212785216184">📞 Appeler : 0785 216 184</a>
    </div>
  </div>
</section>

<footer>
  <p><strong>Michaou Issa Abdoul Hamidou</strong> — Comptable & Analyste Financier | ENCG Béni Mellal</p>
  <p>© 2026 — Tous droits réservés</p>
</footer>

</body>
</html>
