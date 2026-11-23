# OrganizaFatec — Gerenciador de Tarefas Acadêmicas

Aplicação web simples para estudantes registrarem atividades, acompanharem prazos, definirem prioridades e controlarem o andamento das tarefas.

## 1. Objetivo

Desenvolver uma ferramenta leve e acessível para centralizar a organização das tarefas acadêmicas, permitindo que o estudante visualize o que precisa fazer, identifique prioridades e acompanhe suas entregas.

## 2. Problema

Atividades e datas de entrega podem ficar espalhadas em anotações, mensagens e plataformas diferentes. Isso dificulta acompanhar prazos e identificar tarefas atrasadas ou ainda não concluídas. O OrganizaFatec reúne essas informações em uma única tela.

## 3. Escopo

**Incluído**
- Cadastro, edição e exclusão de tarefas.
- Registro de disciplina, prazo, prioridade e status.
- Filtro por status e prioridade.
- Busca por nome da atividade ou disciplina.
- Indicadores de total, pendentes, em andamento e concluídas.
- Persistência local dos dados no navegador.

**Fora do escopo da versão atual**
- Login, perfis e sincronização entre dispositivos.
- Compartilhamento de tarefas entre estudantes.
- Notificações por e-mail ou push.
- Backend, API própria e banco de dados remoto.

## 4. Requisitos funcionais

| ID | Requisito |
|---|---|
| RF01 | O sistema deve permitir cadastrar uma tarefa com título, disciplina, prazo, prioridade e status. |
| RF02 | O sistema deve permitir editar uma tarefa cadastrada. |
| RF03 | O sistema deve permitir excluir uma tarefa após confirmação. |
| RF04 | O sistema deve permitir alterar o status da tarefa. |
| RF05 | O sistema deve filtrar tarefas por status. |
| RF06 | O sistema deve filtrar tarefas por prioridade. |
| RF07 | O sistema deve permitir buscar tarefas por título ou disciplina. |
| RF08 | O sistema deve apresentar indicadores quantitativos das tarefas. |
| RF09 | O sistema deve manter os dados salvos no navegador após atualizar a página. |

## 5. Requisitos não funcionais

| ID | Requisito |
|---|---|
| RNF01 | A aplicação deve funcionar em navegadores modernos com suporte a JavaScript e localStorage. |
| RNF02 | A interface deve se adaptar a telas de computadores e dispositivos móveis. |
| RNF03 | Os dados devem ser armazenados localmente no navegador do usuário. |
| RNF04 | Os campos obrigatórios devem ser validados antes do cadastro. |
| RNF05 | A interface deve utilizar linguagem clara e controles identificáveis. |
| RNF06 | A aplicação não deve depender de servidor ou conexão com banco de dados para as funções principais. |

## 6. Tecnologias

- **HTML5:** estrutura semântica e formulários.
- **CSS3:** layout, responsividade e identidade visual.
- **JavaScript (ES6+):** regras de negócio, eventos, filtros e manipulação das tarefas.
- **localStorage:** persistência local no navegador.
- **Git e GitHub:** versionamento e hospedagem do código.

Não são utilizados frameworks, bibliotecas JavaScript, APIs externas ou banco de dados nesta versão.

## 7. Arquitetura e componentes

A aplicação utiliza arquitetura cliente-side (front-end estático). O navegador carrega o HTML, aplica os estilos CSS e executa o JavaScript. O módulo JavaScript lê e grava os dados no localStorage.

```text
Navegador
   |
   +-- index.html       Estrutura e componentes da interface
   |
   +-- css/styles.css   Estilos e responsividade
   |
   +-- js/app.js        Regras, eventos, filtros e persistência
                            |
                            +-- localStorage do navegador
```

### Organização dos diretórios

```text
organiza-fatec/
├── index.html
├── README.md
├── css/
│   └── styles.css
└── js/
    └── app.js
```

### Principais componentes
- **Painel de indicadores:** mostra os totais por status.
- **Formulário de tarefas:** cadastra e edita atividades.
- **Lista de tarefas:** apresenta os registros existentes.
- **Filtros e busca:** refinam a visualização.
- **Camada de persistência:** salva e recupera dados com localStorage.

## 8. Pré-requisitos

- Navegador atualizado (Chrome, Firefox, Edge ou Safari).
- Git, caso deseje clonar o repositório.
- Editor de código, como Visual Studio Code (opcional).

Não é necessário instalar Node.js, banco de dados ou dependências externas.

## 9. Instalação

### Opção A — Clonar pelo Git

```bash
git clone https://github.com/SEU-USUARIO/SEU-REPOSITORIO.git
cd organiza-fatec
```

Substitua a URL pelo endereço do repositório que receberá o projeto.

### Opção B — Baixar os arquivos

Baixe o ZIP do projeto e extraia a pasta `organiza-fatec` em seu computador.

## 10. Configuração e execução

Não há arquivo `.env` nem configuração de servidor.

**Execução simples:** abra o arquivo `index.html` diretamente no navegador.

**Execução recomendada no VS Code:** abra a pasta do projeto e utilize a extensão Live Server para iniciar um servidor local. A aplicação será aberta em um endereço local, normalmente semelhante a `http://127.0.0.1:5500`.

## 11. APIs, banco de dados e variáveis de ambiente

- **API:** não aplicável. A versão atual não consome nem disponibiliza endpoints.
- **Banco de dados:** não utiliza banco de dados. Os registros são guardados no `localStorage` do navegador.
- **Variáveis de ambiente:** não são necessárias.
- **Limitação:** os dados ficam vinculados ao navegador e à origem utilizada. Limpar os dados do navegador pode apagá-los; não existe sincronização automática entre dispositivos.

## 12. Testes

A versão atual não possui suíte automatizada. Os testes funcionais podem ser realizados manualmente:

1. Abrir a aplicação e verificar se o painel carrega sem erros.
2. Cadastrar uma tarefa preenchendo todos os campos.
3. Atualizar a página e confirmar que a tarefa continua visível.
4. Editar título, disciplina, prazo e prioridade.
5. Alterar o status e conferir a atualização dos indicadores.
6. Filtrar por status e prioridade.
7. Pesquisar por parte do título e pelo nome da disciplina.
8. Excluir uma tarefa e confirmar que ela deixa de aparecer.
9. Redimensionar a janela e verificar a adaptação para telas menores.
10. Tentar salvar o formulário sem preencher os campos obrigatórios.

## 13. Deploy

Por ser uma aplicação estática, pode ser publicada no **GitHub Pages**:

1. Envie os arquivos do projeto para um repositório GitHub.
2. No repositório, acesse **Settings → Pages**.
3. Em *Build and deployment*, selecione **Deploy from a branch**.
4. Escolha a branch `main` e a pasta `/ (root)` — ou a pasta correspondente, caso os arquivos estejam em uma subpasta.
5. Salve e aguarde a publicação.
6. Acesse a URL fornecida pelo GitHub Pages.

Não há etapa de build ou instalação de dependências.

## 14. Melhorias futuras

- Criar categorias e matérias personalizadas.
- Adicionar ordenação por prazo.
- Implementar exportação e importação de tarefas.
- Criar autenticação e sincronização com backend.
- Adicionar testes automatizados.

## 15. Licença e finalidade

Projeto acadêmico desenvolvido para fins de estudo e prática de conceitos de desenvolvimento web no curso de Análise e Desenvolvimento de Sistemas. A licença poderá ser definida pelo responsável pelo repositório.

---
**OrganizaFatec — organização, planejamento e acompanhamento da rotina acadêmica.**
