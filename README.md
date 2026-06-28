# postes-cemig-wfs-bbox
<img width="115" height="118" alt="icon" src="https://github.com/user-attachments/assets/c2bec2ac-9b3f-4c17-837a-c6eaf9e421f9" />
A Cemig disponibiliza um endpoint WFS no (Site CIWEB) para delimitar áreas (BBOX) no mapa de compartilhamento de postes. 
O meu algoritmo extrai dados em GeoJSON (padrão JSON) via QGIS, capturando o campo visual do ecrã com o minimo recomendado de (500m a 500m) e o máximo de (1km a 1km). 
Em seguida, insere os pontos no QGIS aberto e guarda automaticamente o ficheiro GeoJSON em uma pasta específica do seu computador.
A finalidade é gerar estudos de estruturas de ancoragem, usando o QGIS, e gerar projetos que serão apresentados a própria Cemig, para regularização de uso de postes.
<a href="https://script.google.com/macros/s/AKfycbzpFUFCbgLbc0mi-i_NxDAvpjRHcDao0VI2_0sNm9aJy3Vj72f108Mrbe7NAy5tJvbp/exec" target="_blank"><button>Apoio de Acesso a Dados Abertos - Vetoriais</button></a>
