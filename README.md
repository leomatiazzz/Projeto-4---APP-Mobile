# 📌 Flet Front-end para Cadastro de Alunos

Este projeto é um aplicativo front-end desenvolvido com **Flet** e **Requests**, responsável por interagir com o back-end de cadastro de alunos, permitindo a criação, listagem, atualização e acompanhamento do progresso dos alunos.

## 🚀 Requisitos

Antes de executar este projeto, certifique-se de ter:

- O **back-end de cadastro de alunos** configurado e rodando.
- Python 3.x ou superior instalado na máquina.
- A biblioteca **Flet** instalada.

## 📦 Instalação

1. Clone o repositório do projeto:

    ```bash
    git clone https://github.com/seu-usuario/seu-repositorio.git
    cd seu-repositorio
    ```

2. Instale as dependências necessárias:

    ```bash
    pip install flet
    pip install requests
    ```

3. **Submódulo do Back-end**:
   - A pasta do back-end foi adicionada como **submódulo** ao projeto.
   - Caso haja problemas na instalação ou ao clonar o projeto, você pode clonar o back-end separadamente utilizando o seguinte comando:

    ```bash
    git clone https://github.com/leomatiazzz/Projeto-3---Rest-API.git
    ```

   Ou, caso você já tenha clonado o repositório principal, pode atualizar o submódulo com:

    ```bash
    git submodule update --init --recursive
    ```

   Certifique-se de que o back-end está configurado corretamente e em execução.

## ▶️ Como Rodar o Aplicativo

Após instalar as dependências, execute o aplicativo com um dos seguintes comandos:

### Windows:

    ```bash
    python app.py
    ```

### Linux/macOS:

    ```bash
    python3 app.py
    ```

### Usando o Flet CLI:

    ```bash
    flet run app.py
    ```

## 🔧 Funcionalidades

- **Criar um novo aluno**: Permite adicionar um novo aluno ao sistema.
- **Listar alunos cadastrados**: Visualiza a lista de todos os alunos cadastrados.
- **Marcar aulas realizadas**: Registra as aulas que o aluno já completou.
- **Consultar progresso do aluno**: Verifica o progresso do aluno em suas atividades.
- **Atualizar informações de um aluno**: Permite editar os dados de um aluno existente.

O aplicativo se comunica com o **back-end** através de requisições HTTP usando a biblioteca `requests`.

## 🌐 Como o Sistema Funciona

- O front-end, desenvolvido com **Flet**, interage com o back-end via API RESTful.
- Certifique-se de que o back-end está rodando no endereço correto (por padrão: `http://localhost:8000/api`).
- Se você estiver usando um endereço diferente, altere a configuração no código para apontar para a URL correta.

## 🧪 Testando a Aplicação

- Para testar as funcionalidades, basta garantir que o back-end está em funcionamento.
- O aplicativo permitirá realizar operações de CRUD (Criar, Ler, Atualizar, Excluir) sobre os alunos cadastrados.

## ⚙️ Estrutura do Projeto

```plaintext
/seu-repositorio
    ├── app.py             # Código principal do front-end
    ├── backend/           # Submódulo com o repositório do back-end
    ├── requirements.txt   # Arquivo com as dependências do projeto
    ├── README.md          # Este arquivo
```

## 📌 Observações
Pasta do back-end: A pasta do back-end foi adicionada como submódulo ao repositório. Caso haja problemas ao clonar o projeto ou ao instalar as dependências, siga estas orientações:

Se o submódulo não for clonado automaticamente, basta executar o comando:

```bash
git submodule update --init --recursive
Se continuar tendo problemas, clone o repositório do back-end separadamente:
```

```bash
git clone https://github.com/leomatiazzz/Projeto-3---Rest-API.git
```
Certifique-se de que o back-end está rodando antes de iniciar este app.

O back-end precisa estar disponível em http://localhost:8000/api ou no endereço configurado no código.

## 💡 Contribuições
Contribuições são bem-vindas! Se você encontrar algum bug ou tiver uma ideia para uma melhoria, fique à vontade para abrir uma issue ou enviar um pull request.

Como contribuir:
1. Faça um fork do repositório.
2. Crie uma nova branch (git checkout -b feature/alguma-nova-funcionalidade).
3. Faça as modificações desejadas.
4. Envie um pull request explicando as mudanças feitas.

## 📜 Licença
Este projeto é de uso livre e pode ser modificado conforme necessário.

Desenvolvido por Léo Matias, usando Flet e Python 🚀
