<h1 align="center"> Agrupador de clientes para campanhas de marketing </h1>
https://img.shields.io/badge/STATUS-concluido-green
Modelo de Machine Learning treinado com o método de clusterização, cujo objetivo é agrupar uma base de clientes em 3 grupos (clusters). Disponibilizado por meio de aplicação web com o Streamlit.

![Captura de tela 2025-05-30 152607](https://github.com/user-attachments/assets/63f33761-a395-4914-98f6-2c809408b071)

Recebe uma base csv que precisa estar no seguinte formato:
#   Column             Non-Null Count  Dtype 
---  ------             --------------  ----- 
 0   sexo               12992 non-null  object
 1   idade              12992 non-null  int64 
 2   numero_de_amigos   12992 non-null  int64 
 3   basquete           12992 non-null  int64 
 4   futebol_americano  12992 non-null  int64 
 5   futebol            12992 non-null  int64 
 6   softbol            12992 non-null  int64 
 7   voleibol           12992 non-null  int64 
 8   natacao            12992 non-null  int64 
 9   animacao           12992 non-null  int64 
 10  beisebol           12992 non-null  int64 
 11  tenis              12992 non-null  int64 
 12  esportes           12992 non-null  int64 
 13  fofo               12992 non-null  int64 
 14  danca              12992 non-null  int64 
 15  banda              12992 non-null  int64 
 16  marcha             12992 non-null  int64 
 17  musica             12992 non-null  int64 
 18  rock               12992 non-null  int64 
 19  cabelo             12992 non-null  int64 
 20  vestido            12992 non-null  int64 
 21  shopping           12992 non-null  int64 
 22  compras            12992 non-null  int64 
 23  roupas             12992 non-null  int64 
 24  nossa_marca        12992 non-null  int64 
 25  marca_concorrente  12992 non-null  int64 
 26  bebidas            12992 non-null  int64 

 Sexo: F, M ou NE
 Outros campos: marcam o número de interações em redes sociais sobre o tópico por parte do cliente
