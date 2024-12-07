<!DOCTYPE html>
<html>
<body>
  <h1>CI/CD Pipeline for Node.js Application 🚀</h1>
  <h2>📋 Fonctionnalités principales</h2>
  <ul>
    <li><strong>Tests automatisés</strong> pour chaque PR et push vers staging/main.</li>
    <li><strong>Création d'images Docker</strong> et stockage sur Docker Hub.</li>
    <li><strong>Déploiement avec Google Cloud Run</strong> (staging et production).</li>
    <li><strong>Gestion des secrets</strong> via GitHub.</li>
  </ul>
  <h2>📂 Structure du pipeline</h2>
  <h3>1️⃣ Continuous Integration (CI)</h3>
  <p><strong>Déclenchement :</strong> PR vers staging/main.</p>
  <ul>
    <li>Checkout du code</li>
    <li>Installation des dépendances</li>
    <li>Exécution des tests</li>
    <li>Build de l'application</li>
  </ul>
  <h3>2️⃣ Continuous Delivery (CD)</h3>
  <p><strong>Déclenchement :</strong> Push vers staging ou publication d'une release depuis main.</p>
  <ul>
    <li>Reprise des tests CI</li>
    <li>Création et push d'image Docker</li>
    <li>Déploiement sur Google Cloud Run</li>
  </ul>
  <h2>🛠️ Prérequis</h2>
  <p>Technologies utilisées : GitHub Actions, Docker, Google Cloud Run, Node.js.</p>
</body>
</html>
