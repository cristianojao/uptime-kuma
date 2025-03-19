<div align="center" width="100%">
    <img src="./public/icon.svg" width="128" alt="" />
</div>

# Uptime Kuma



<img src="https://user-images.githubusercontent.com/1336778/212262296-e6205815-ad62-488c-83ec-a5b0d0689f7c.jpg" width="700" alt="" />



## 🔧 Como Instalar


  - ✅ Windows 10 (x64), Windows Server 2012 R2 (x64) or higher
  - 
    
- [Node.js](https://nodejs.org/en/download/) 18 / 20.4
- [Git](https://git-scm.com/downloads)


```bash
------------------------------------------------------------------------------------
-Instalar o Uptime Kuma
------------------------------------------------------------------------------------
  01. Faça login no dispositivo Windows
  02. Baixe o Git https://git-scm.com/download/win
  03. Baixe o NodeJS https://nodejs.org/en/download/current/
  04. Instale o Git, aceitando todos os padrões
  05. Instale o NodeJS, aceitando todos os padrões
  06. Clique no botão Iniciar ≫ Pesquisar no PowerShell
  07. Clique com o botão direito do mouse no Windows PowerShell ≫ Executar como administrador
  08. Execute os seguintes comandos na janela do PowerShell
	# altere o diretório para a raiz de c:\
	cd \
	# clone do git
	git clone https://github.com/cristianojao/uptime-kuma .\uptime-kuma
	# altere o diretório para uptime-kuma
	cd .\uptime-kuma\
	# instale dependências
	npm install npm
	# execute setup
	npm run setup
	# execute uptime kuma
	node server\server.js
  09. Abra um navegador da web e navegue até http://DNSorIP:3001
  10. Selecione um idioma e crie um nome de usuário e senha de administrador ≫ Clique em Criar
  11. Bem-vindo ao Uptime Kuma

-----------------------------------------------------------------------------------
-Execute o Uptime Kuma como um serviço (opcional, mas recomendado)
-----------------------------------------------------------------------------------
  01. Pressione CTRL + C para encerrar o processo do Uptime Kuma em execução
  02. Clique no botão Iniciar ≫ Digite task ≫ Iniciar o Agendador de Tarefas
  03. Clique com o botão direito na pasta Biblioteca do Agendador de Tarefas no painel esquerdo ≫ Criar Tarefa Básica...
  04. Defina o nome como Uptime Kuma e, opcionalmente, defina uma Descrição ≫ Clique em Avançar
  05. Para o Gatilho, selecione Quando o computador inicia ≫ Clique em Avançar
  06. Para a Ação, selecione Iniciar um programa ≫ Clique em Avançar
  07. Preencha os campos do formulário da seguinte forma:
	Programa/script: "%ProgramFiles%\nodejs\node.exe"
	Adicione argumentos: C:\uptime-kuma\server\server.js
	Comece em: C:\uptime-kuma
  08. Clique em Avançar
  09. Marque a caixa de seleção Abrir a caixa de diálogo Propriedades ≫ Clique em Concluir
  10. Na caixa de diálogo Propriedades, clique no botão Alterar usuário ou grupo...
  11. Digite Sistema no campo Nome do objeto ≫ Clique em OK
  12. Marque a caixa Executar com os maiores privilégios
  13. Clique em OK para criar a tarefa agendada
  14. Clique com o botão direito do mouse na tarefa Uptime Kuma ≫ Executar
  15. Atualize o navegador da Web aberto para verificar se o Uptime Kuma agora está em execução a partir da tarefa agendada
```

