<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu de Power BI</title>
    <style>
      
         .container {
            max-width: 800px;
            margin: 50px auto;
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h1 {
            color: #140588;
        }
        .section {
            margin-bottom: 30px;
            padding: 20px;
            border-bottom: 2px solid #ddd;
        }
        .section h3 {
            background: #140588;
            color: white;
            padding: 10px;
            border-radius: 8px;
        }
        .menu {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 15px;
            padding: 0;
        }
     .menu a {
            display: block;
            padding: 15px;
            background: #005a9e;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            font-size: 16px;
            font-weight: bold;
            transition: 0.1s;
        }
		
        .menu a:hover {
            background: #004080;
            transform: scale(1.05);
        }
        .logo {
            max-width: 100%;
            height: auto;
            margin-bottom: 1px;
        }
		
		     .footer {
            background: #00264d;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 30px;
            position: relative;
            border-top: 2px solid #004080;
        }
        .footer img {
            height: 40px;
            opacity: 0.7;
        }
		
				
		  body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(135deg, #005a9e, #00264d);
            color: white;
            text-align: center;
            margin: 0;
            padding: 0;
        }
        
        header {
            background: #333;
            color: white;
            padding: 20px;
            font-size: 24px;
            font-weight: bold;
            animation: fadeIn 1s ease-in-out;
        }
        
        .container {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background: white;
            box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
            animation: slideUp 1s ease-in-out;
        }
        
        button {
            background: #008CBA;
            color: white;
            border: none;
            padding: 10px 20px;
            font-size: 16px;
            cursor: pointer;
            border-radius: 5px;
            transition: background 0.3s, transform 0.2s;
        }
        
        button:hover {
            background: #005f73;
            transform: scale(1.05);
        }

        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }

        @keyframes slideUp {
            from { transform: translateY(20px); opacity: 0; }
            to { transform: translateY(0); opacity: 1; }
        }

    </style>
	
</head>
<body>
    <div class="container">
        <img src="https://howbetec.sharepoint.com/sites/ambientepowerbi/shared%20documents/general/layout/logos/logos.png?web=1" alt="Logo da Empresa" class="logo">
        <h1>Menu de Painéis</h1>

        <div class="section">
          <h3>FATURAMENTO</h3>
            <div class="menu">
                <a href="https://app.powerbi.com/groups/ee43e07e-68e1-4d2e-bf6c-f06c7303513d/reports/8cfa47e1-99df-4fed-8b14-ebdbac3eb3eb/ReportSectionc49fbe2cc000b42c9900?experience=power-bi">Faturamento</a>
                <a href="https://app.powerbi.com/groups/ee43e07e-68e1-4d2e-bf6c-f06c7303513d/reports/8cfa47e1-99df-4fed-8b14-ebdbac3eb3eb/ReportSectionc49fbe2cc000b42c9900?experience=power-bi">Provisionamento</a>
                <a href="https://app.powerbi.com/groups/ee43e07e-68e1-4d2e-bf6c-f06c7303513d/reports/8cfa47e1-99df-4fed-8b14-ebdbac3eb3eb/ReportSection30faca59dc039eace079?experience=power-bi">Descontos</a>
                <a href="https://app.powerbi.com/groups/ee43e07e-68e1-4d2e-bf6c-f06c7303513d/reports/8cfa47e1-99df-4fed-8b14-ebdbac3eb3eb/ReportSectiond83037c1242830ca48cb?experience=power-bi">Histórico cliente</a>
            </div>
        </div>

        <div class="section">
            <h3>TESOURARIA</h3>
            <div class="menu">
                <a href="https://app.powerbi.com/groups/26025e2a-eb1c-435b-9451-779e59b42450/reports/8824c90b-538f-41d1-941a-a4c46036c3d2/c16e529660236c674872?experience=power-bi">Contas a Pagar</a>
                <a href="https://app.powerbi.com/groups/26025e2a-eb1c-435b-9451-779e59b42450/reports/8824c90b-538f-41d1-941a-a4c46036c3d2/054b8f1ab52d8729e252?experience=power-bi">Contas Pagas</a>
                <a href="https://app.powerbi.com/groups/26025e2a-eb1c-435b-9451-779e59b42450/reports/8824c90b-538f-41d1-941a-a4c46036c3d2/dcb476d5d630ebbd16c0?experience=power-bi">Contas a Receber</a>
                <a href="https://app.powerbi.com/groups/26025e2a-eb1c-435b-9451-779e59b42450/reports/8824c90b-538f-41d1-941a-a4c46036c3d2/dcb476d5d630ebbd16c0?experience=power-bi">Contas Recebidas</a>
            </div>
        </div>

        <div class="section">
   <h3>CONTROLADORIA</h3>
            <div class="menu">
                <a href="https://app.powerbi.com/reportEmbed?reportId=a25d9102-9f9e-49db-9940-bf5ae1171279&autoAuth=true&ctid=d36ff69d-da0a-44bb-921b-912b9b558ab2">Orçado vs Realizado</a>
                <a href="https://app.powerbi.com/groups/c6eeac1c-b7d9-42f2-9198-fc5580b6c040/reports/a25d9102-9f9e-49db-9940-bf5ae1171279/1c63e53fdfec3637d15b?experience=power-bi">Balancete</a>
                <a href="https://app.powerbi.com/groups/c6eeac1c-b7d9-42f2-9198-fc5580b6c040/reports/a25d9102-9f9e-49db-9940-bf5ae1171279/e45a4cd6b170029c3950?experience=power-bi">Indicadores BP</a>
                <a href="https://app.powerbi.com/groups/c6eeac1c-b7d9-42f2-9198-fc5580b6c040/reports/161b5fe1-0159-4498-afa6-5e6051a648f3/57cd1439c703090ac396?experience=power-bi">Tributos a pagar</a>
		 <a href="https://app.powerbi.com/reportEmbed?reportId=d4ef2dc4-8b3d-458d-ad50-823106f6d473&autoAuth=true&ctid=d36ff69d-da0a-44bb-921b-912b9b558ab2">GLPI - Fiscal</a>
		 <a href="https://app.powerbi.com/groups/c6eeac1c-b7d9-42f2-9198-fc5580b6c040/reports/d4ef2dc4-8b3d-458d-ad50-823106f6d473/5545c6ce845ce5325a93?experience=power-bi">Auditoria vencimento</a>
 		<a href="https://app.powerbi.com/groups/c6eeac1c-b7d9-42f2-9198-fc5580b6c040/reports/161b5fe1-0159-4498-afa6-5e6051a648f3/89b78957f5afa957ff49?experience=power-bi">Pedido de Compras</a>
 		<a href="https://app.powerbi.com/reportEmbed?reportId=d384e3dd-ace1-4479-ad93-5cce68239d58&autoAuth=true&ctid=d36ff69d-da0a-44bb-921b-912b9b558ab2">Certidão Negativa Débito</a>
		 <a href="https://app.powerbi.com/groups/c6eeac1c-b7d9-42f2-9198-fc5580b6c040/reports/161b5fe1-0159-4498-afa6-5e6051a648f3/60b285a25674865b6869?experience=power-bi">Cronograma de Fechamento</a>
            </div>
        </div>
    <div class="section">
	<a href="https://app.powerbi.com/reportEmbed?reportId=4412ac65-6afe-4bc6-b361-bb60b3cc6e60&autoAuth=true&ctid=d36ff69d-da0a-44bb-921b-912b9b558ab2">
            <h3>LOGÍSTICA</h3>
			</a>
            <div class="menu">
                <a href="https://app.powerbi.com/groups/80568f8f-517a-4131-ae34-2eed32fb60f5/reports/4412ac65-6afe-4bc6-b361-bb60b3cc6e60/ReportSectionb1e89d53f2139a16854b?experience=power-bi">Saldo de estoque</a>
                <a href="https://app.powerbi.com/reportEmbed?reportId=4412ac65-6afe-4bc6-b361-bb60b3cc6e60&autoAuth=true&ctid=d36ff69d-da0a-44bb-921b-912b9b558ab2">Movimentação de estoque</a>
                <a href="https://app.powerbi.com/groups/80568f8f-517a-4131-ae34-2eed32fb60f5/reports/4412ac65-6afe-4bc6-b361-bb60b3cc6e60/ReportSection9543108cc5c23be4ea34?experience=power-bi">Aplicação de materiais</a>
                <a href=" https://app.powerbi.com/groups/80568f8f-517a-4131-ae34-2eed32fb60f5/reports/4412ac65-6afe-4bc6-b361-bb60b3cc6e60/ReportSection991a5cc9ec66402a9b9c?experience=power-bi">Compras aprovadas</a>
				<a href="https://app.powerbi.com/groups/80568f8f-517a-4131-ae34-2eed32fb60f5/reports/4412ac65-6afe-4bc6-b361-bb60b3cc6e60/c0725ada92ea6cf6cd99?experience=power-bi">PMP</a>
				<a href="https://app.powerbi.com/groups/80568f8f-517a-4131-ae34-2eed32fb60f5/reports/4412ac65-6afe-4bc6-b361-bb60b3cc6e60/d6757090f913ef8ed043?experience=power-bi">Giro de estoque</a>
            </div>
        </div>
		    <div class="section">
                      <h3>TI</h3>
            <div class="menu">
                <a href="https://app.powerbi.com/reportEmbed?reportId=8df8e049-719d-4132-9ab1-49fbf816a9b8&autoAuth=true&ctid=d36ff69d-da0a-44bb-921b-912b9b558ab2">Chamados GLPI</a>
                <a href="https://app.powerbi.com/reportEmbed?reportId=a3271208-c106-409d-a4f8-31161ff8b4a1&autoAuth=true&ctid=d36ff69d-da0a-44bb-921b-912b9b558ab2">GLPI Geral</a>
                <a href="https://app.powerbi.com/reportEmbed?reportId=4e7d721a-30f4-4cc2-9be1-c834cb1ba76e&autoAuth=true&ctid=d36ff69d-da0a-44bb-921b-912b9b558ab2">EPP</a>
            </div>
        </div>
		    <div class="section">
            <h3>RH - GENTE E GESTÃO</h3>
            <div class="menu">
                <a href="https://app.powerbi.com/reportEmbed?reportId=113b76dc-eb4b-47a9-9857-8a3ee9bcaa87&autoAuth=true&ctid=d36ff69d-da0a-44bb-921b-912b9b558ab2">Recrutamento</a>
				<a href="https://app.powerbi.com/reportEmbed?reportId=cfb00ac2-1fff-40db-82a9-7b7a2b20ab3f&autoAuth=true&ctid=d36ff69d-da0a-44bb-921b-912b9b558ab2">Folha de Pagamento</a>
                <a href="https://app.powerbi.com/reportEmbed?reportId=07dd2a25-7ab3-4dd8-8886-43bba5d94141&autoAuth=true&ctid=d36ff69d-da0a-44bb-921b-912b9b558ab2">Folha PJ</a>
                <a href="https://app.powerbi.com/reportEmbed?reportId=eaa91039-e217-48d2-a5ac-9c5f94cf5c67&autoAuth=true&ctid=d36ff69d-da0a-44bb-921b-912b9b558ab2">Beneficios</a>
                <a href="https://app.powerbi.com/reportEmbed?reportId=3c2e93b6-e799-48ee-98d1-a80766e2fb49&autoAuth=true&ctid=d36ff69d-da0a-44bb-921b-912b9b558ab2">ASO</a>
               <a href="https://app.powerbi.com/reportEmbed?reportId=07c4b5f7-654a-40bb-a3ac-37fbb8c23fb9&autoAuth=true&ctid=d36ff69d-da0a-44bb-921b-912b9b558ab2">Entrevista de Desligamento</a>
            </div>
        </div>
		    <div class="section">
       <h3>SUPORTE</h3>
            <div class="menu">
                <a href="https://app.powerbi.com/groups/9c10d6d5-a2f9-4b89-9e79-53e04f656dc8/reports/5947cdd8-5204-4803-9dee-a2bf68a3592c/b3961f7ac6db5d38e098?experience=power-bi">Tempo Primeiro Contato</a>
                <a href="https://app.powerbi.com/reportEmbed?reportId=5947cdd8-5204-4803-9dee-a2bf68a3592c&autoAuth=true&ctid=d36ff69d-da0a-44bb-921b-912b9b558ab2">Entrantes</a>
                <a href="https://app.powerbi.com/groups/9c10d6d5-a2f9-4b89-9e79-53e04f656dc8/reports/5947cdd8-5204-4803-9dee-a2bf68a3592c/ReportSectiond464a5716b12dfe49e68?experience=power-bi">Chamados Fechados</a>
                <a href="https://app.powerbi.com/groups/9c10d6d5-a2f9-4b89-9e79-53e04f656dc8/reports/5947cdd8-5204-4803-9dee-a2bf68a3592c/d62a0c9acee4cf4723b9?experience=power-bi">Chamados Abertos</a>
            </div>
        </div>
		  <div class="section">
         <a href="https://app.powerbi.com/reportEmbed?reportId=3cd2ebad-5c0d-4400-acde-cccbcd363eed&autoAuth=true&ctid=d36ff69d-da0a-44bb-921b-912b9b558ab2" target="_blank">
    <h3>COMERCIAL</h3>
</a>
            <div class="menu">
                <a href="https://app.powerbi.com/groups/20ffd11d-7af3-4b32-9895-05214946e3be/reports/3cd2ebad-5c0d-4400-acde-cccbcd363eed/53d900dce2ce509d9802?experience=power-bi">Agenda</a>
                <a href="https://app.powerbi.com/groups/20ffd11d-7af3-4b32-9895-05214946e3be/reports/3cd2ebad-5c0d-4400-acde-cccbcd363eed/ReportSection8c9720a9b384b4175cba?experience=power-bi"> Cotação</a> 
				
            </div>
        </div>
		    <div class="section">
          <h3>PÓS VENDAS</h3>
            <div class="menu">
                <a href="https://app.powerbi.com/groups/fbf111b7-15b4-47ea-883b-ad740a063758/reports/0e73895a-8c4a-4138-97c0-414eac94c6b2/5fbfa8405759a72b1063?experience=power-bi">Atendimento</a>
                <a href="https://app.powerbi.com/groups/fbf111b7-15b4-47ea-883b-ad740a063758/reports/0e73895a-8c4a-4138-97c0-414eac94c6b2/ReportSection8c13146d855101027608?experience=power-bi"> Ordem de Serviço - OS</a> 
				<a href="https://app.powerbi.com/groups/fbf111b7-15b4-47ea-883b-ad740a063758/reports/0e73895a-8c4a-4138-97c0-414eac94c6b2/35d9e26a900b39bc41a0?experience=power-bi">Contratos</a>
				<a href="https://app.powerbi.com/groups/fbf111b7-15b4-47ea-883b-ad740a063758/reports/0e73895a-8c4a-4138-97c0-414eac94c6b2/9e8dd8a00473c43cc254?experience=power-bi">Ativação de login</a>
                <a href="https://app.powerbi.com/reportEmbed?reportId=40ed1e89-569d-4932-91a5-9846646e5522&autoAuth=true&ctid=d36ff69d-da0a-44bb-921b-912b9b558ab2">Portifólio de parceiros</a>
                <a href="https://app.powerbi.com/groups/fbf111b7-15b4-47ea-883b-ad740a063758/reports/03608b6c-42a5-416f-8783-07bd74ebb0a1/ReportSection9bff34ca6b65785060a5?experience=power-bi">Painel Parceiros</a>
                <a href="https://app.powerbi.com/groups/fbf111b7-15b4-47ea-883b-ad740a063758/reports/03608b6c-42a5-416f-8783-07bd74ebb0a1/ReportSection6152fb9c6b8d34cbb385?experience=power-bi">Arvore parceiros</a>
            </div>
        </div>
		    <div class="section">
         <h3>PROJETO SME</h3>
            <div class="menu">
                <a href="https://app.powerbi.com/reportEmbed?reportId=9cb7bfeb-62fc-434e-bf71-3b460191c762&autoAuth=true&ctid=d36ff69d-da0a-44bb-921b-912b9b558ab2">Biometria</a>
                <a href="#" style="background-color: lightcoral; color: white; text-decoration: none; border-radius: 5px; font-weight: bold;"> Painel Frequência <br>(DESENVOLVIMENTO)</a>     </div>
	 </div>
		    <div class="section">
        <h3>USINAS</h3>
            <div class="menu">
                <a href="https://app.powerbi.com/reportEmbed?reportId=f3ae7f2a-08ac-493b-b5d6-0dada5e053f9&autoAuth=true&ctid=d36ff69d-da0a-44bb-921b-912b9b558ab2">Faturamento</a>
                <a href="https://app.powerbi.com/groups/5a138fcf-57f1-4e17-83e1-da4d7b818021/reports/804c900b-725f-4406-8d6d-198f9babff65/ReportSectionf552c40c68fd317b23d3?experience=power-bi">Painel Yellow</a>
             </div>
        </div>
		    <div class="section">
			      <h3>OUTROS</h3>
            <div class="menu">
                <a href="https://app.powerbi.com/groups/ee43e07e-68e1-4d2e-bf6c-f06c7303513d/reports/8cfa47e1-99df-4fed-8b14-ebdbac3eb3eb/ReportSection8e752c5ee165b82218a1?experience=power-bi&bookmarkGuid=Bookmarkf66a9325a200c573f6e4">Contratos e logins </a>
                <a href="https://app.powerbi.com/groups/ee43e07e-68e1-4d2e-bf6c-f06c7303513d/reports/8cfa47e1-99df-4fed-8b14-ebdbac3eb3eb/ReportSection8c9720a9b384b4175cba?experience=power-bi&bookmarkGuid=Bookmarkf66a9325a200c573f6e4">Não gera financeiro </a>
                <a href="https://app.powerbi.com/groups/ee43e07e-68e1-4d2e-bf6c-f06c7303513d/reports/8cfa47e1-99df-4fed-8b14-ebdbac3eb3eb/ReportSection8c13146d855101027608?experience=power-bi&bookmarkGuid=Bookmarkf66a9325a200c573f6e4">Rentabilidade(Planilha) </a>
                <a href="https://app.powerbi.com/groups/ee43e07e-68e1-4d2e-bf6c-f06c7303513d/reports/8cfa47e1-99df-4fed-8b14-ebdbac3eb3eb/ReportSectionf6b49385001870d6da8e?experience=power-bi">Previsão de faturamento (Planiha) </a>
               <a href="https://app.powerbi.com/groups/ee43e07e-68e1-4d2e-bf6c-f06c7303513d/reports/8cfa47e1-99df-4fed-8b14-ebdbac3eb3eb/ReportSection6fd44a05e500140c3800?experience=power-bi">Mapa de serviços (planilha) </a>
                <a href="https://app.powerbi.com/reportEmbed?reportId=b8c7fc7a-d6ea-437c-a0c5-b9ac8e5f5f05&autoAuth=true&ctid=d36ff69d-da0a-44bb-921b-912b9b558ab2">Mercado </a>
              
            </div>
        </div>
	
       <div class="footer">
        <p>&copy; 2025 - Todos os direitos reservados</p>
        <img src="https://howbetec.sharepoint.com/sites/ambientepowerbi/shared%20documents/general/layout/logos/logo%20biex%20branco.png?web=1" alt="Logo Power BI">
    </div>
	
	
</body>
</html>


