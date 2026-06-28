# postes-cemig-wfs-bbox
A Cemig disponibiliza um endpoint WFS no CIWEB para delimitar áreas (BBOX) no mapa de partilha de postes. O meu algoritmo extrai dados em GeoJSON (padrão JSON) via QGIS, capturando o campo visual do ecrã (500m a 1km). Em seguida, insere os pontos no QGIS aberto e guarda automaticamente o ficheiro GeoJSON em uma pasta específica do seu computador.
