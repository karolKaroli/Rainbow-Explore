# Componentes
- **Temos alguns componentes em nosso sistema, tais como:**
- Parâmetro de Autenticação;
- Parâmetro de Gerenciamento de Usuários;
- Parâmetro de Gerenciamento de Voos;
- Parâmetro de Gerenciamento de Hotelaria;
- Parâmetro de Gerenciamento de Cidade/Países;
- Parâmetro de Banco de Dados;
- Parâmetro de Processamento de Pagamentos;
- Parâmetro de Segurança;
- Parâmetro de Notificações.

A interação entre eles é assegurada por meio de chamadas diretas, em que os componentes se comunicam diretamente uns com os outros, invocando funções ou métodos expostos pelas interfaces dos demais componentes. 

# Protocolos e Interfaces de Programação de Aplicações (APIs)

- **Os protocolos escolhidos para nossa utilização são o HTTP , o TCP/IP, e SMTP pelas seguintes razões:**

O TCP/IP oferece uma base rígida para a comunicação em redes, assegurando a entrega ordenada e confiável de dados. O HTTP, construído sobre o TCP, herda essas propriedades, garantindo uma comunicação eficaz e robusta. Utilizar o TCP/IP como alicerce para o HTTP possibilita o compartilhamento eficiente de recursos web, e  SMTP para enviar confirmações de reservas e outras comunicações por e-mail.

- **Quanto à APIs,  optamos pelas seguintes devido às características específicas:**

- Reservas de Voos e Hotéis:  REST API é  baseada no protocolo HTTP e na arquitetura REST (Representational State° Transfer). Esse tipo de aplicação é amplamente utilizada na comunicação entre sistemas e aplicativos, permitindo a troca de informações de forma flexível e eficiente.Além disso, também podemos dizer que a arquitetura REST é um conjunto de diretrizes para a criação de serviços web que sejam escaláveis, flexíveis, seguros e fáceis de manter. Assim, esses serviços são projetados para serem acessados pela internet e interagir com aplicativos de diferentes plataformas, como web, mobile e desktop.
- Pagamentos: Stripe API é organizada em torno de REST. Essa API tem URLs previsíveis orientadas a recursos, aceita corpos de solicitação codificados em formulário, e usa códigos de resposta HTTP padrão, autenticação e verbos.
