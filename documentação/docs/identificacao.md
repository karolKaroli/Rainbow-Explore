# Identificação do Projeto

|Projeto | Requisitante | Gerente de Projetos|
| -------| ------------ | -------------------|
|   Eng. de Software - III   | Prof: Cleber da S. Araujo |     Assunção       |

# Brainstorming 
- Explique e coloque imagens de todas as reuniões do grupo, incluindo explicação de como ocorreu, datas, colaboraçoes, o que foi excluido e acatado na reuinão.  Esta apresentação deve incluir todos os esboços iniciais, ideias e as contribuições de cada membro do grupo, além da lista de frequência e votação.

# Técnicas de Elicatação de Requisitos
- Para levantarmos os requisitos do sistema **Rainbow - X** utilizamos a técnica de entrevista com nosso cliente, dessa forma conseguimos extrair o maximo do que o sistema do nosso cliente realmente precia na implementação.
# Requisitos Funcionais
![Logo de RF](img/RF.jpg) 

|Código |Identificação |Classificação |Ator |Objetivo|
|------ |--------------|--------------|-----|--------|
|[RF01] | Fazer Cadastro/Atualização | Importante |Usuário| Este caso de uso serve para o usuário fazer login|
|[RF02] | Efetuar Login | Importante |Usuário| Este caso de uso serve para o usuário entrar no sistema|
|[RF03] | Verificar Senha | Importante |Sistema| Este caso de uso serve para o sistema verificar senha do usuário|
|[RF04] | Pesquisar Voos | Importante |Usuário| Este caso de uso serve para o usuário fazer busca por voos com detalhes específicos|
|[RF05] | Pesquisar Hotéis | Importante |Usuário| Este caso de uso serve para o usuário fazer busca por hotéis|
|[RF06] | Escolher Escalas | Importante |Usuário| Este caso de uso serve para o usuário fazer escolha das escalas na viagem|
|[RF07] | Escolher Produtos | Importante |Usuário| Este caso de uso serve para o usuário fazer escolha dos produtos para consumir na viagem|
|[RF08] | Reservar Voos | Importante |Usuário| Este caso de uso serve para o usuário fazer reserva de voos|
|[RF09] | Fazer Check-in | Importante |Usuário| Este caso de uso serve para o usuário fazer check-in do voo|
|[RF10] | Reservar Hotéis | Importante |Usuário| Este caso de uso serve para o usuário fazer reserva hotél/tipo de quarto (luxo,super luxo)|
|[RF11] | Busca Detalhada Por Hotéis | Importante |Usuário| Este caso de uso serve para o usuário fazer busca por hotíes/quartos pelas catategorias|
|[RF12] | Verificar Hóspedes | Importante |Sistema| Este caso de uso serve para o sistema solicitar dados pessoais e quantidade de hóspedes no ato da reserva|
|[RF13] | Cancelar Reserva | Importante |Usuário| Este caso de uso serve para o usuário solicitar cancelamento de reservas voos/hotéis|
|[RF14] | Comprar Pacotes | Importante |Usuário| Este caso de uso serve para permitir que o usuário compre pacotes de voos/hotéis|
|[RF15] | Notificar Cliente | Importante |Sistema| Este caso de uso serve para o sistema fazer notificações para o cliente relacionadas a reserva|
|[RF16] | Compartilhar Nas Redes Sociais | Importante |Usuário| Este caso de uso serve para o usuário fazer compartilhamento de suas reservas nas redes sociais|
|[RF17] | Sugerir Viagens | Importante |Sistema| Este caso de uso serve para o sistema fazer notificações para o cliente com sugestões de viagens/pacotes|
|[RF18] | Recuperar Senha | Importante |Usuário| Este caso de uso serve para o usuário solicitar nova senha|
|[RF19] | Alertar Cliente | Importante |Sistema| Este caso de uso serve para o sistema fazer alerta ao cliente quanto as restrições do país o qual ele deseja viajar|
|[RF20] | Adicionar Companhia | Importante |Administração| Este caso de uso serve para a administração adicionar novas companhias aereas/horários de voos|
|[RF21] | Cadastrar Pacote | Importante |Administração| Este caso de uso serve para a administração adicionar pacotes por Cidade/País|
|[RF22] | Excluir Companhia/Cidade | Importante |Administração| Este caso de uso serve para a administração excluir Companhias/Cidades|
|[RF23] | Gerar Relatório | Importante |Administração| Este caso de uso serve para a administração gerar relatórios|
|[RF24] | Fazer Backup | Importante |Administração| Este caso de uso serve para a administração fazer backup|
|[RF25] | Verificar Regulamentação | Importante |Administração| Este caso de uso serve para a administração fazer verificações de regulamentações dos países|
|[RF26] | Espaço para feedback | Importante |Usuário| Este caso de uso serve para a usuário dá um feedback quanto a satisfação do atendimento|
|[RF27] | Verificar Histórico | Importante |Usuário| Este caso de uso serve para a usuário ver seus históricos de viagens/hotéis reservados|
|[RF28] | Escolher Data | Importante |Usuário| Este caso de uso serve para a usuário fazer escolha de datas no ato da reservas|
|[RF29] | Fazer Pagamento | Importante |Usuário| Este caso de uso serve para o usuário fazer pagamento com multiplas opções|
|[RF30] | Rastrear Bagagem | Importante |Sistema| Este caso de uso serve para a sistema fazer rastreamento das bagagens|
|[RF31] | Acento Reservado | Importante |Usuário| Este caso de uso serve para o usuário ver as opções para passageiros especiais|
|[RF32] | Sobre Clima | Importante |Usuário| Este caso de uso serve para o usuário ver como estão as condições climáticas|

# Requisitos Não Funcionais 
![Logo de RNF](img/RNF.jpg)

|Código |Identificação |Classificação |Ator |Objetivo|
|------ |--------------|--------------|-----|--------|
|[RNF01] | Usabilidade |Importante |Sistema| Este caso de uso serve para o sistema oferta ao usuário fácio acesso ao mesmo|
|[RNF02] | Responsividade |Importante |Sistema| Este caso de uso serve para o sistema se adptar a diversas plataformas|
|[RNF03] | Rapidez |Importante |Sistema| Este caso de uso serve para o sistema ter agilidade na execução|
|[RNF04] | Disponibilidade |Importante |Sistema| Este caso de uso serve para que o sistema esteja disponível na escala de 24x7|
|[RNF05] | Sistema Operacional |Importante |Sistema| Este caso de uso serve para que o sistema seja acessado por todos os sistemas operacionais|
|[RNF06] | Hardware a Ser Utiliadzo |Importante |Sistema| Este caso de uso serve para que o sistema seja acessado por todos os aparelhos eletrônicos|
|[RNF07] | Capacidade de Acesso |Importante |Sistema| Este caso de uso serve para que o sistema tenha alta capacidade de acessos simultâneos|
|[RNF07] | Time p/ Concluir Reserva |Importante |Sistema| Este caso de uso serve para que o sistema aborte reservas não concluídas em 15 min|
