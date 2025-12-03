<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Lista de Presentes — Matheus</title>

<style>
    body {
        font-family: Arial, sans-serif;
        background: #f4f6f9;
        margin: 0;
        padding: 0;
        display: flex;
        justify-content: center;
        align-items: flex-start;
        min-height: 100vh;
    }

    .container {
        background: #fff;
        margin-top: 40px;
        padding: 30px;
        border-radius: 16px;
        box-shadow: 0 4px 18px rgba(0,0,0,0.08);
        width: 95%;
        max-width: 520px;
    }

    h1 {
        text-align: center;
        margin-bottom: 25px;
        font-size: 1.6rem;
        color: #333;
        font-weight: 700;
    }

    .short-link {
        background: #eef2ff;
        border: 1px solid #cdd5ff;
        padding: 12px;
        border-radius: 10px;
        text-align: center;
        margin-bottom: 25px;
        font-weight: bold;
        cursor: pointer;
        word-break: break-all;
        transition: 0.2s;
    }

    .short-link:hover {
        background: #e0e6ff;
    }

    .card {
        background: #fafafa;
        border: 1px solid #e6e6e6;
        padding: 20px;
        border-radius: 12px;
        margin-bottom: 20px;
        word-break: break-word;
    }

    .card-title {
        font-size: 1.1rem;
        font-weight: bold;
        margin-bottom: 10px;
    }

    .buttons {
        display: flex;
        justify-content: space-between;
        gap: 10px;
        margin-top: 15px;
    }

    button {
        flex: 1;
        padding: 10px;
        border: none;
        border-radius: 8px;
        cursor: pointer;
        font-weight: bold;
        transition: 0.2s;
    }

    .open-btn {
        background: #4f46e5;
        color: white;
    }
    .open-btn:hover {
        background: #4338ca;
    }

    .copy-btn {
        background: #e5e7eb;
    }
    .copy-btn:hover {
        background: #d1d5db;
    }
</style>

<script>
function copyToClipboard(text) {
    navigator.clipboard.writeText(text);
    alert("Link copiado!");
}
</script>

</head>
<body>

<div class="container">
    <h1>Lista de Presentes — Matheus</h1>

    <!-- Link curto fake -->
    <div class="short-link" onclick="copyToClipboard('https://l.pm/matheus')">
        https://l.pm/matheus
    </div>

    <!-- Item 1 -->
    <div class="card">
        <div class="card-title">Body Spray Arbo Botanic — O Boticário</div>
        <div class="buttons">
            <button class="open-btn" onclick="window.open('https://www.boticario.com.br/body-spray-desodorante-arbo-botanic-100ml-v2/?gclsrc=aw.ds&&sku=B79417&utm_source=google&utm_medium=cpc&utm_campaign=G:BOT:Smart-Shopping:Padrao:Cuidados&gad_source=1&gad_campaignid=23098163458&gbraid=0AAAAA90O9wvU27G7R5tjpMrwSOK6pxw51&gclid=CjwKCAiA3L_JBhAlEiwAlcWO52_8HFKO6aNCDlusinHh8-i-PY-hl_Iq58M--sAAvY8r8Kefgw1ScBoCv8wQAvD_BwE', '_blank')">Abrir</button>

            <button class="copy-btn" onclick="copyToClipboard('https://www.boticario.com.br/body-spray-desodorante-arbo-botanic-100ml-v2/?gclsrc=aw.ds&&sku=B79417&utm_source=google&utm_medium=cpc&utm_campaign=G:BOT:Smart-Shopping:Padrao:Cuidados&gad_source=1&gad_campaignid=23098163458&gbraid=0AAAAA90O9wvU27G7R5tjpMrwSOK6pxw51&gclid=CjwKCAiA3L_JBhAlEiwAlcWO52_8HFKO6aNCDlusinHh8-i-PY-hl_Iq58M--sAAvY8r8Kefgw1ScBoCv8wQAvD_BwE')">Copiar</button>
        </div>
    </div>

    <!-- Item 2 -->
    <div class="card">
        <div class="card-title">Bolsa Isotérmica 14L — Mercado Livre</div>
        <div class="buttons">
            <button class="open-btn" onclick="window.open('https://www.mercadolivre.com.br/bolsa-isotermica-termica-lancheira-14l-porta-marmita-alca-transversal-removivel-de-ombro-academia-trabalho-passeio-2-compartimentos-elegante-premium-cor-preto-tche-amo/p/MLB28726333?pdp_filters=item_id:MLB3966563925#polycard_client=recommendations_pdp-pads-reviews&reco_backend=recos-pads-retrieval-4stars&wid=MLB3966563925&reco_model=rk_ent_v2_retsys_4stars&reco_client=pdp-pads-reviews&reco_item_pos=1&reco_backend_type=low_level&reco_id=acf9966b-9273-458d-80de-caadbab79b2c&sid=recos&is_advertising=true&ad_domain=PDPDESKTOP_RECOMMENDED&ad_position=2&ad_click_id=YTA2ZDc1YjUtYzEyMi00MGY3LWJjM2ItODIwYzVkODdkMDFj', '_blank')">Abrir</button>

            <button class="copy-btn" onclick="copyToClipboard('https://www.mercadolivre.com.br/bolsa-isotermica-termica-lancheira-14l-porta-marmita-alca-transversal-removivel-de-ombro-academia-trabalho-passeio-2-compartimentos-elegante-premium-cor-preto-tche-amo/p/MLB28726333?pdp_filters=item_id:MLB3966563925#polycard_client=recommendations_pdp-pads-reviews&reco_backend=recos-pads-retrieval-4stars&wid=MLB3966563925&reco_model=rk_ent_v2_retsys_4stars&reco_client=pdp-pads-reviews&reco_item_pos=1&reco_backend_type=low_level&reco_id=acf9966b-9273-458d-80de-caadbab79b2c&sid=recos&is_advertising=true&ad_domain=PDPDESKTOP_RECOMMENDED&ad_position=2&ad_click_id=YTA2ZDc1YjUtYzEyMi00MGY3LWJjM2ItODIwYzVkODdkMDFj')">Copiar</button>
        </div>
    </div>

</div>

</body>
</html>
