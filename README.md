# postes-cemig-wfs-bbox
<img width="115" height="118" alt="icon" src="https://github.com/user-attachments/assets/c2bec2ac-9b3f-4c17-837a-c6eaf9e421f9" /><br />
<u><b>INSTALAÇÃO DO PLUGIN</b></u>:<br />
1º - Baixe o arquivo (ZIP), abra seu (QGIS), no menu, clique em [Complementos], na guia clique em [Gerenciar e Instalar Complementos...].<br />
2º - No formulário aberto, na aba esquerda cinza escura, clique em [Instalar a partir do ZIP].<br />
3º - Clique no botão no extro direito [...], indique onde está este arquivo {cemig_wfs}, feito isso ativará o botão abaixo [Instalar Complemento], clique nele.<br />
4º - Após a instalação ele será exibido no menu [Complementos], com o título (CEMIG WFS)... Antes de usar modifique seu {EPSG}, ele deverá mostrar {EPSG:3857}, são critérios para coleta de dados que estão em um site WEB.<br />
5º - Gerado está ultima alteração, clique no botão do menu que abrirá um sub-botão {CEMIG - Coletar Postes (WFS)}, o algoritmo irá proceder a busca, gerar um alerta na tela em caixa de dialogo, e criar uma cópia com data, informando você o local, faça bom uso, deixe seus comentários, sugestões ou críticas, são bem vindas.<br />
<hr />
<b>FUNCIONAMENTO</b>(<I>Meta & Objetivo Idealizado</I>):<br /></b>A Cemig disponibiliza um endpoint WFS no (Site CIWEB) para delimitar áreas (BBOX) no mapa de compartilhamento de postes. <br />
O meu algoritmo extrai dados em GeoJSON (padrão JSON) via QGIS, capturando o campo visual do ecrã com o minimo recomendado de (500m a 500m) e o máximo de (1km a 1km). <br />
Em seguida, insere os pontos no QGIS aberto e guarda automaticamente o ficheiro GeoJSON em uma pasta específica do seu computador.<br />
A finalidade é gerar estudos de estruturas de ancoragem, usando o QGIS, e gerar projetos que serão apresentados a própria Cemig, para regularização de uso de postes.<br />
<a href="https://script.google.com/macros/s/AKfycbzpFUFCbgLbc0mi-i_NxDAvpjRHcDao0VI2_0sNm9aJy3Vj72f108Mrbe7NAy5tJvbp/exec" target="_blank"><button>Apoio de Acesso a Dados Abertos - Vetoriais</button></a>
