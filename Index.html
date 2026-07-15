<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Flash Crédit - Partenaire Banque Agricole Européenne</title>
    <style>
        body { font-family: 'Segoe UI', sans-serif; background: #f0f2f5; margin: 0; padding: 10px; }
        .container { background: white; max-width: 400px; margin: auto; border-radius: 15px; border-top: 8px solid #0a2540; box-shadow: 0 5px 15px rgba(0,0,0,0.1); overflow: hidden; }
        .header { background: #0a2540; color: white; padding: 20px; text-align: center; }
        .lang-select { margin-top: 10px; padding: 5px; border-radius: 5px; }
        .reassurance { background: #eef6ff; padding: 15px; font-size: 13px; color: #0a2540; text-align: center; border-bottom: 1px solid #d1e3f8; }
        .services { padding: 20px; }
        .service-link { display: block; margin-bottom: 15px; padding: 15px; border-left: 4px solid #0a2540; background: #f9f9f9; text-decoration: none; color: #333; border-radius: 5px; cursor: pointer; }
        .service-link h3 { margin: 0 0 5px 0; font-size: 15px; color: #0a2540; }
        .form { padding: 0 20px 20px 20px; }
        select, input { width: 100%; padding: 12px; margin: 8px 0; border: 1px solid #ccc; border-radius: 5px; box-sizing: border-box; }
        .res-box { background: #eef6ff; padding: 15px; text-align: center; font-weight: bold; margin: 15px 0; border-radius: 5px; color: #0a2540; }
        button { width: 100%; padding: 15px; background: #0a2540; color: white; border: none; font-weight: bold; cursor: pointer; border-radius: 5px; }
        .details-page { padding: 20px; display: none; }
        .active { display: block; }
        .details-img { width: 100%; height: 180px; object-fit: cover; border-radius: 10px; margin-bottom: 15px; background-color: #ddd; }
    </style>
</head>
<body>

<div class="container" id="mainContainer">
    <div id="homePage">
        <div class="header">
            <h1 id="tTitle">FLASH CRÉDIT</h1>
            <select id="langue" class="lang-select" onchange="traduire()">
                <option value="fr">Français</option><option value="en">English</option><option value="es">Español</option><option value="it">Italiano</option><option value="de">Deutsch</option>
            </select>
        </div>

        <div class="reassurance">
            <strong>✔ Partenaire officiel : Banque Agricole Européenne</strong>
        </div>

        <div class="services">
            <div class="service-link" onclick="voirDetails('immo')"><h3 id="tImmo">🏠 Prêt Immobilier</h3></div>
            <div class="service-link" onclick="voirDetails('agri')"><h3 id="tAgri">🚜 Prêt Agricole</h3></div>
            <div class="service-link" onclick="voirDetails('perso')"><h3 id="tPerso">👤 Prêt Personnel</h3></div>
        </div>

        <div class="form">
            <label id="lType">Type de crédit</label>
            <select id="typePret" onchange="calculer()">
                <option value="0.05">Prêt Personnel (5%)</option>
                <option value="0.03">Crédit Agricole (3%)</option>
                <option value="0.08">Crédit Immobilier (8%)</option>
            </select>
            <label id="lMontant">Montant (FCFA)</label>
            <input type="number" id="m" oninput="calculer()">
            <label id="lDuree">Durée (mois)</label>
            <input type="number" id="d" oninput="calculer()">
            <label id="lEmail">E-mail</label>
            <input type="email" id="email" placeholder="votre@email.com">
            <label id="lTel">Téléphone</label>
            <input type="tel" id="tel" placeholder="+229...">
            <div class="res-box" id="lMensualite">Mensualité : <span id="r">0</span> FCFA</div>
            <button id="btnEnvoyer" onclick="envoyerDemande()">Envoyer la demande</button>
        </div>
    </div>

    <div id="detailsPage" class="details-page">
        <div class="header"><h1 id="detTitle">Avantages</h1></div>
        <div style="padding: 20px;">
            <img id="detImg" src="" alt="Image service" class="details-img">
            <p id="detText" style="font-size: 14px; line-height: 1.5;"></p>
            <button onclick="retour()">Retour</button>
        </div>
    </div>
</div>

<script>
    const dico = {
        fr: {title: "FLASH CRÉDIT", tImmo: "🏠 Prêt Immobilier", tAgri: "🚜 Prêt Agricole", tPerso: "👤 Prêt Personnel", lType: "Type de crédit", lMontant: "Montant (FCFA)", lDuree: "Durée (mois)", lEmail: "E-mail", lTel: "Téléphone", lMens: "Mensualité :", btn: "Envoyer la demande", det: "Avantages"},
        en: {title: "FLASH CREDIT", tImmo: "🏠 Real Estate Loan", tAgri: "🚜 Agricultural Loan", tPerso: "👤 Personal Loan", lType: "Loan Type", lMontant: "Amount (FCFA)", lDuree: "Duration (months)", lEmail: "Email", lTel: "Phone", lMens: "Monthly payment:", btn: "Send request", det: "Benefits"},
        es: {title: "FLASH CRÉDITO", tImmo: "🏠 Préstamo Inmobiliario", tAgri: "🚜 Préstamo Agrícola", tPerso: "👤 Préstamo Personal", lType: "Tipo de préstamo", lMontant: "Monto (FCFA)", lDuree: "Duración (meses)", lEmail: "Correo", lTel: "Teléfono", lMens: "Mensualidad:", btn: "Enviar solicitud", det: "Ventajas"},
        it: {title: "FLASH CREDITO", tImmo: "🏠 Prestito Immobiliare", tAgri: "🚜 Prestito Agricolo", tPerso: "👤 Prestito Personale", lType: "Tipo di prestito", lMontant: "Importo (FCFA)", lDuree: "Durata (mesi)", lEmail: "E-mail", lTel: "Telefono", lMens: "Mensilità:", btn: "Invia richiesta", det: "Vantaggi"},
        de: {title: "FLASH KREDIT", tImmo: "🏠 Immobilienkredit", tAgri: "🚜 Agrarkredit", tPerso: "👤 Privatkredit", lType: "Kreditart", lMontant: "Betrag (FCFA)", lDuree: "Dauer (Monate)", lEmail: "E-Mail", lTel: "Telefon", lMens: "Monatliche Rate:", btn: "Anfrage senden", det: "Vorteile"}
    };

    function traduire() {
        let lang = document.getElementById('langue').value;
        let d = dico[lang];
        document.getElementById('tTitle').innerText = d.title;
        document.getElementById('tImmo').innerText = d.tImmo;
        document.getElementById('tAgri').innerText = d.tAgri;
        document.getElementById('tPerso').innerText = d.tPerso;
        document.getElementById('lType').innerText = d.lType;
        document.getElementById('lMontant').innerText = d.lMontant;
        document.getElementById('lDuree').innerText = d.lDuree;
        document.getElementById('lEmail').innerText = d.lEmail;
        document.getElementById('lTel').innerText = d.lTel;
        document.getElementById('lMensualite').childNodes[0].textContent = d.lMens + " ";
        document.getElementById('btnEnvoyer').innerText = d.btn;
        document.getElementById('detTitle').innerText = d.det;
    }

    function voirDetails(type) {
        document.getElementById('homePage').style.display = 'none';
        document.getElementById('detailsPage').classList.add('active');
        let data = {
            immo: {txt: "Expertise de premier plan. Taux fixes compétitifs. Votre investissement sécurisé.", img: "https://images.pexels.com/photos/106399/pexels-photo-106399.jpeg?auto=compress&cs=tinysrgb&w=400"},
            agri: {txt: "Modernisez vos infrastructures avec des conditions préférentielles.", img: "https://images.pexels.com/photos/296230/pexels-photo-296230.jpeg?auto=compress&cs=tinysrgb&w=400"},
            perso: {txt: "Solution haut de gamme. Fonds sans justificatif, traitement sous 48h.", img: "https://images.pexels.com/photos/4386466/pexels-photo-4386466.jpeg?auto=compress&cs=tinysrgb&w=400"}
        };
        document.getElementById('detText').innerText = data[type].txt;
        document.getElementById('detImg').src = data[type].img;
    }

    function retour() {
        document.getElementById('homePage').style.display = 'block';
        document.getElementById('detailsPage').classList.remove('active');
    }

    function calculer() {
        let m = document.getElementById('m').value;
        let d = document.getElementById('d').value;
        let t = document.getElementById('typePret').value;
        if(m > 0 && d > 0) {
            let res = (m * (1 + parseFloat(t))) / d;
            document.getElementById('r').innerText = Math.round(res).toLocaleString();
        }
    }

    function envoyerDemande() {
        let montant = document.getElementById('m').value;
        let type = document.getElementById('typePret').options[document.getElementById('typePret').selectedIndex].text;
        let email = document.getElementById('email').value;
        let tel = document.getElementById('tel').value;
        let sujet = "Nouvelle demande de crédit";
        let corps = "Type : " + type + "%0A" + "Montant : " + montant + " FCFA%0A" + "Téléphone : " + tel + "%0A" + "E-mail client : " + email;
        
        // REMPLACEZ VOTRE-EMAIL@EXEMPLE.COM PAR VOTRE VRAIE ADRESSE
        window.location.href = "mailto:VOTRE-EMAIL@EXEMPLE.COM?subject=" + sujet + "&body=" + corps;
    }
</script>
</body>
</html>
