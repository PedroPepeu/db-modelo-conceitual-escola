## Trabalho numero 3 - Escola - Pedro Pepeu Duarte de Freitas

#### Legenda:
| Nome no modelo | Nome completo | Significado |
| -------------- | ------------- | ----------- |
|                | esp.          | Especializacao de |
| PERSON         | Person        | Identidade pessoa |
| STUDENT        | Student       | Identidade estudante (esp. Person) |
| WORKER         | Worker        | Identidade trabalhador (esp. Person) |
| TEACHER        | Teacher       | Identidade professor (esp. Worker) |
| SUBJECT        | Subject       | Identidade materia Escolar |
| RESPONSIBLE    | Responsible   | Identidade responsavel |
| CLASSROOM      | Classroom     | Identidade sala de aula |
| WORKS          | Works         | Identidade tarefa escolar |
| JOBS           | Jobs          | Identidade trabalho escolar (esp. Works) |
| COURT          | Court         | Identidade quadra (esp. Classroom) |
| PROJECT        | Project       | Identidade projetos escolares |
| STUDENT_M      | Student Managed | Identidade liderada por estudantes (esp. Project) |
| SCHOOLAR_M     | Schoolar Managed | Identidade liderada pela escola (esp. Project) |
| OLIMP_COMP     | Olimpic Competition | Identidade turma de competicao olimpica (esp. SCHOOLAR_M)
| CLUBS          | Clubs        | Identidade clubes (esp. STUDENT_M) |
| RESEARCHS      | Researchs    | Identidade pesquisas (esp. STUDENT_M) |
| CONCIL         | Concil       | Identidade concelho estudantil (esp. STUDENT_M) |
| DEPARTMENT     | Department   | Identidade departamento |
| AUDITORIUM     | Auditorium   | Identidade auditorio (esp. DEPARTMENT) |
| NURSERY        | Nursery      | Identidade enfermaria (esp. DEPARTMENT) |
| TECHNOLOGY     | Technology   | Identidade tecnologia (esp. DEPARTMENT) |
| LIBRARY        | Library      | Super Identidade livraria (esp. DEPARTMENT) |
| QUEMISTRY      | Quemistry    | Identidade quimica (esp. DEPARTMENT) |
| SPORTS         | Sports       | Identidade esporte (esp. DEPARTMENT) |
| TRANSPORT      | Transport    | Identidade transporte |
| VAN            | Van          | Identidade van (esp. TRANSPORT) |
| CAR            | Car          | Identidade carro (esp. TRANSPORT) |
| BUS            | Bus          | Identidade onibus (esp. TRANSPORT) |
| MECS           | MECS         | Identidade SAMU (esp. VAN) |
| DORMITORY      | Dormitory    | Identidade dormitorio |
| BEDROOM        | Bedroom      | Identidade quarto (esp. DORMITORY) |
| BATHROOM       | Bathroom     | Identidade banheiro (esp. DORMITORY) |
| FEMALE         | Female       | Identidade feminino (esp. BATHROOM) |
| TRAVELS | Travels | Identidade de viagem (esp. DEPARTMENT) |
| emergence_phone | Emergence Phone | Atributo telefone de emergencia |
| dt_birth       | Date Birth   | Atributo data de nascimento |
| sex            | Sex          | Atributo sexo |
| email          | E-mail       | Atributo e-mail |
| picture        | Picture      | Atributo foto de perfil |
| phone          | Phone        | Atributo numero de telefone |
| cpf            | CPF          | Atributo cadastro de pessoa fisica |
| id             | ID           | Atributo identificador |
| name           | Name         | Atributo nome |
| f_name         | First Name   | Atributo primeiro nome (esp. name) |
| l_name         | Last Name    | Atributo ultimo nome (esp. name) |
| adrss          | Address      | Atributo endereco |
| zip_code       | Zip Code     | Atributo codigo de enderecamento postal |
| complement     | Complement   | Atributo complemento |
| city           | City         | Atributo cidade |
| monthly_fee    | Monthly Fee  | Atributo mensalidade |
| pay_mth        | Payment Method | Atributo metodo de pagamento |
| card           | Card         | Atributo cartao (esp. pay_mth) |
| credit         | Credit       | Atributo credito (esp. cartao) |
| debit          | Debit        | Atributo debito (esp. cartao) |
| c_wallet       | Crypto Wallet       | Atributo carteira de criptomoedas (esp. pay_mth) |
| payment_slip   | Payment Slip | Atributo boleto (esp. pay_mth) |
| grade_avr      | Grade Average | Atributo media de notas |
| school_year    | School Year  | Atributo ano escolar |
| s_workload     | Student Workload | Atibuto carga de horario do estudante |
| resume         | Resume       | Atributo curriculo |
| b_analisys     | Behavious Analisys | Atributo analise de comportamento |
| credit_h       | Credit Hours | Atributo de credito de horas |
| obligatoriness | Obligatoriness | Atributo de obrigatoriedade |
| monthly_price  | Monthly Price | Atributo de valor mensal |
| sbj_workload   | Subject Workload | Atributo de carga de horario da materia |
| modality       | Modality     | Atributo de area |
| menu           | Menu         | Atributo de programa da disciplina |
| salary         | Salary       | Atributo de Salario |
| monthly        | Monthly      | Atributo de valor do mes (esp. salary) |
| bonuses        | Bonuses      | Atributo de valor bonus (esp. salary) |
| floor_number   | Floor Number | Atributo de quantidade de andares |
| css            | Community Space Size | Atributo de tamanho da area comum |
| Tampons_number | Tampons Number | Atributo de numero de absorventes |
| room_size      | Room Size    | Atributo de tamanho do quarto |
| floor          | Floor        | Atributo de andar |
| building       | Building     | Atributo de predio |
| time           | Time         | Atributo de horario |
| avaliability   | Avaliability | Atributo de disponibilidade |
| number         | Number       | Atributo de numero |
| activity       | Activity     | Atributo de atividade |
| dt_conclusion  | Date Conclusion | Atriburo de data de conclusao |
| income         | Income       | Atributo de lucro |
| events         | Events       | Atributo de eventos |
| achievements   | Achievements | Atibuto de conquistas |
| quotes         | Quotes       | Atributo de citacoes |
| papers         | Papers       | Atributo de papers publicados |
| r_subject      | Research Subject | Atributo de assunto de pesquisa |
| voting_results | Voting Results | Atributo de resultado dos votos |
| positions      | Positions    | Atributo de posicoes guardadas pelos alunos |
| s_names        | Student Names | Atributo de nome dos estudantes |
| dt             | Date         | Atributo de data |
| start          | Start        | Atributo de comeco (esp. dt) |
| end            | End          | Atributo de fim (esp. dt) |
| medals         | Medals       | Atributo de medalhas |
| student_positions | Student Positions | Atributo de colocacao dos estudantes |
| size           | Size          | Atributo de tamanho |
| local | Local | Atributo de localizacao |
| num_workers | Number of Workers | Atributo de numero de trabalhadores |
| chairs_qnt | Chairs Quantity | Atributo de quantidade de cadeiras |
| stage_size | Stage Size | Atributo de tamanho de palco |
| usage_price | Usage Price | Atributo de preco por uso |
| projector | Projector | Atributo de projetores |
| television | Television | Atributo de televisao |
| speaker | Speaker | Atributo de alto-falante |
| num_balls | Number of Balls | Atributo de numero de bolas |
| num_shirts | Number of Shirts | Atributo de quantidade de camisas |
| trophies | Trophies | Atributo de numero de trofeus |
| blankets | Blackets | Atributo de lencois |
| emergence_number | Emergence Number | Atributo do numero da emergencia |
| p_allergies | Person Allergies | Atributo de alergias |
| medicines | Medicines | Atributo de medicamentos |
| drugs | Drugs | Atributo de remedios |
| h_items | Health Items | Atributo de itens de saude |
| beds | Beds | Atributo de camas |
| pillows | Pillows | Atributo de travesseiros |
| mouses | Mouses | Atributo de mouses |
| monitors | Monitors | Atributo de monitores |
| computer | Computer | Atributo de computadores |
| protoboards | Protoboards | Atributo de protoboards |
| lrk | Lego Robotic Kits | Atributo de kits de lego de robotica |
| logic_gates | Logic Gates | Atributo de portas logicas |
| raspberry | Raspberry | Atributo de raspberry |
| arduino | Arduino | Atributo de arduino |
| cooper_wire | Cooper Wire | Atributo de fio de cobre |
| pliers | Pliers | Atributo de alicates |
| keyboards | Keyboards | Atributo de teclados |
| nurse | Nurse | Atributo de numero de enfermeiras |
| storage_capacity | Storage Capacity | Atributo de capacidade de armazenamento |
| local | Local | Atributo de local |
| garage_adrss | Garage Address | Atributo de local de estacionamento |
| alcohol_burner | Alcohol Burner | Atributo de queima alcool |
| graduated_cylinder | Graduated Cylinder | Atributo de cilindro graduado |
| test_tube | Test Tube | Atributo de tubo de teste |
| test_tube_rack | Test Tube Rack | Atributo de organizador de tubo de teste |
| beaker | Beaker | Atributo de beaker |
| bunsen_burner | Bunsen Burner | Atributo de queimador de bunsen |
| barometer | Barometer | Atributo de barometro |
| cloth_v | Cloth Value | Atributo de valor do fardamento |
| distance | Distance | Atributo de distancia da viagem |
| t_price | Travel Price | Atributo do valor da viagem |
| MANAGE | Manage | Relacionamento de gerencia o que |
| WORK | Work | Relacionamento de trabalha com |
| SUPERVISES | Supervices | Relacionamento de supervisao |
| ATTENDS | Attends | Relacionamento de atende a |
| TEACHED | Teached | Relacionamento de ensinado por |
| TEACHES | Teaches | Relacionamento de ensina o que |
| DEPENDS | Depends | Relacionamento de depender de |
| LEADER | Leader | Relacionamento de lidera algo |
| SLEEP | Sleep | Relacionamento de dormir |
| HAVE | Have | Relacionamento de ter |
| BRACKET | Bracket | Relacionamento de juntar |
| CONTROLS | Controls | Relacionamento de controlar |
| DRIVES | Drives | Relacionamento de dirigir |

#### Detalhamento:
Lucro da instituicao de ensino que usufruir deste banco de dados:
- Mensalidade alunos
- Valor da mensalidade dos clubes
- Valor do uso da quadra
- Valor do uso do auditorio
- Valor do uso da sala de quimica
- Valor do uso dos materiais da sala de quimica
- Valor do uso da sala de informatica
- Valor do uso de qualquer meio de transporte (van, carro, onibus)
- Valor da mensalidade do dormitorio
- Valor da mensalidade da sala de projeto liderada por alunos
- Valor do fardamento comprado
- Valor do motorista do meio de transporte
- Valor do lucro das excursoes
###### Os valores de uso de salas e departamento para aulas como a quadra nao preveem custo adicional para os ALUNOS que usarem nos horarios normais.

#### Plano:
Banco de dados para escola completa integral, que visa o controle de todas as informacoes de necessidade de gerenciamento. Buscando o maximo de detalhes para que nao haja necessidade de custo adicional para o cliente.
