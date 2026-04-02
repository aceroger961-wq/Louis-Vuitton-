<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Redirection</title>
</head>
<body>
  <script>
    const lien = "https://fr.louisvuitton.com/fra-fr/produits/blouson-a-capuche-double-face-reversible-monogram-nvprod7020059v/1AJBXK";

    if (lien) {
      try {
        const url = new URL(lien);
        window.location.href = url.href;
      } catch (e) {
        alert("Lien invalide.");
      }
    } else {
      alert("Aucun lien entré.");
    }
  </script>
</body>
</html>