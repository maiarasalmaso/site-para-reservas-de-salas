# Room-management-
A herbal system for a Yoga and Meditation school.


A ideia deste projeto foi proposta e aceita por uma escola de yoga e meditação em Londrina, Paraná. Além das aulas normais, há também terapias em outras salas dentro da escola, onde cada terapeuta deveria ir até a secretaria para verificar a disponibilidade de horário, fazer o pagamento da reserva e, assim, efetivá-la, gerando alta demanda para a secretária. 

**Obs:**  _ O css deste site funciona melhor apenas para dispositivos móveis, logo, não é responsiva. _

O projeto contém duas páginas: o index e o sistema em si. 

A **página principal**, ou **index**, é composta por dois QR codes referentes ao pagamento e três botões. O primeiro botão leva o terapeuta para uma agenda compartilhada do Google, onde ele pode ver todos os horários reservados.
Já o segundo botão leva para outra página contendo o sistema em si, onde é possível escolher entre três salas. Quando o terapeuta clica em uma delas, é automaticamente redirecionado para um sistema de reserva de horário do Google Workspace.
O terceiro botão integra uma API do WhatsApp, onde é possível enviar a foto do comprovante de pagamento sem a necessidade de fechar a página e procurar o aplicativo do WhatsApp em seu smartphone ou computador.

![index](https://github.com/maiarasalmaso/Room-management-/assets/91421583/cba143d8-b660-4d6a-81d0-f227352e050e)


Já a página do sistema também é composta por três botões, sendo que cada um deles se destina à reserva de uma sala específica.

![sistema](https://github.com/maiarasalmaso/Room-management-/assets/91421583/851f5149-28a4-43c9-8efd-bf81b40c6a6f)


O sistema de reserva de horário foi feito com a **Reserva de horários do Google Calendar** com disponibilidade de horários a partir das 8 da manhã até ás 22h da noite.

![Horários](https://github.com/maiarasalmaso/Room-management-/assets/91421583/56b4cf29-c7b2-433c-9b9a-7b28cec8cca6)


Ao escolher o horário, o terapeuta deve preencher um formulárop que será utilizado para "coletar" as respostas em uma planilha do Google Sheets feita em Java.

![Formulário](https://github.com/maiarasalmaso/Room-management-/assets/91421583/f457cb88-8570-4681-b368-374612f82104)
