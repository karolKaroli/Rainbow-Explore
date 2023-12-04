# Visão Lógica

Companhia aerea: 
Tem como principais responsabilidades adicionar voos conforme as necessidades, ela pode estender a tabela de voos seja um novo horário de voo para um destinos já cadastrados ou para um novo destino.  
Além disso, também faz gerenciamento das poltronas por classes onde cada poltrona de acordo com o nível tem suas vantagens.
 Também faz gerenciamento dos voos com cronograma geral de origem e  destino, informações de portões de embarque, horário, tempo de voo e atualizações de imprevistos em caso de atrasos. 

voo: 
Essa classe tem atributos muito importantes que são imprescindíveis para a companhia em relação aos voos como: avião, aeroporto de partida, data de partida, horário da partida, aeroporto de chegada, horário de chegada, lotação, peso da carga de embarque e preço da viagem. 
Além disso, faz relacionamentos importantes com as classes Companhia, Avião, Aeroporto e Passagem.
Admin:
Tem grandes responsabilidades pois só através dela que o usuário admin terá permissões de adicionar novas companhias aéreas no sistema abrindo um leque de opções de viagens para os clientes.
Adicionar novos hotéis ao sistema, Paises e Cidade, além disso ela faz as verificações de regulamentações dos países para informar aos usuários as permissões necessárias para entrar legalmente no país o qual ele deseja viajar.
Gera os relatórios dos voos e pacotes de hospedagens, faz backup dos dados   e também pode excluir Companhias, Países, Cidades…

Hotelaria: 
Possui a responsabilidade de adicionar os quartos serviços disponibilizados por quarto e tem como principais atributos nome do hotel, e-mal, telefone, cnpj e endereço.
Usuario:
Essa classe é de suma importância para o sistema, pois nela temos as permissões de interações do usuário com o sistema tais como: inserir dados cadastrais, fazer login para ter acesso ao sistema e poder fazer busca de voos e pacotes de viagens, reservar e comprar voos. 
Além disso pode fazer check-in ou cancelar voo, também pode reservar hotéis, fazer pagamento, cancelar a reserva de hotéis e   verificar histórico de viagens já realizadas. Também tem como principais atributos nome do usuário, telefone e e-mail .
