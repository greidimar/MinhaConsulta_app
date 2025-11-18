MinhaConsulta App
<p align="center"> <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript"> <img src="https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React Native"> <img src="https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white" alt="Expo"> </p>
Um aplicativo móvel desenvolvido em React Native com TypeScript para agendamento e gerenciamento de consultas médicas.

📋 Sobre o Projeto
O MinhaConsulta é um aplicativo que facilita o agendamento e acompanhamento de consultas médicas, proporcionando uma experiência intuitiva para pacientes gerenciarem seus compromissos de saúde.

🚀 Funcionalidades
<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 1rem; margin: 1rem 0;"> <div style="background: #f5f5f5; padding: 1rem; border-radius: 8px;"> <h4>🎯 Agendamento de Consultas</h4> <p>Marque consultas com diferentes especialistas</p> </div> <div style="background: #f5f5f5; padding: 1rem; border-radius: 8px;"> <h4>👤 Gerenciamento de Perfil</h4> <p>Cadastro e edição de informações do paciente</p> </div> <div style="background: #f5f5f5; padding: 1rem; border-radius: 8px;"> <h4>📊 Histórico de Consultas</h4> <p>Acompanhamento do histórico médico</p> </div> <div style="background: #f5f5f5; padding: 1rem; border-radius: 8px;"> <h4>🔔 Lembretes e Notificações</h4> <p>Alertas para próximas consultas</p> </div> <div style="background: #f5f5f5; padding: 1rem; border-radius: 8px;"> <h4>🔍 Busca de Profissionais</h4> <p>Encontre médicos por especialidade</p> </div> </div>
🛠️ Tecnologias Utilizadas
<table> <tr> <td><strong>Tecnologia</strong></td> <td><strong>Descrição</strong></td> </tr> <tr> <td>React Native</td> <td>Framework para desenvolvimento mobile</td> </tr> <tr> <td>TypeScript</td> <td>Linguagem de programação</td> </tr> <tr> <td>Expo</td> <td>Plataforma para desenvolvimento React Native</td> </tr> <tr> <td>React Navigation</td> <td>Navegação entre telas</td> </tr> <tr> <td>Styled Components</td> <td>Estilização de componentes</td> </tr> <tr> <td>Context API</td> <td>Gerenciamento de estado global</td> </tr> </table>
📦 Instalação
Pré-requisitos
Node.js (versão 14 ou superior)

npm ou yarn

Expo CLI

Android Studio / Xcode (para emuladores) ou dispositivo físico

Passos para instalação
<h4>1. Clone o repositório</h4>
bash
git clone https://github.com/greidimar/MinhaConsulta_app.git
cd MinhaConsulta_app
<h4>2. Instale as dependências</h4>
bash
npm install
# ou
yarn install
<h4>3. Execute o projeto</h4>
bash
npx expo start
# ou
npm start
<h4>4. Teste o aplicativo</h4><ul> <li>Use o aplicativo Expo Go no seu dispositivo móvel</li> <li>Escaneie o QR code gerado no terminal</li> <li>Ou execute em um emulador Android/iOS</li> </ul>
🏗️ Estrutura do Projeto
<pre> MinhaConsulta_app/ ├── src/ │ ├── components/ # Componentes reutilizáveis │ ├── screens/ # Telas do aplicativo │ ├── navigation/ # Configuração de navegação │ ├── services/ # Serviços e APIs │ ├── contexts/ # Contextos do React │ ├── types/ # Definições de tipos TypeScript │ └── utils/ # Utilitários e helpers ├── assets/ # Imagens, ícones e fontes └── App.tsx # Componente principal </pre>
🔧 Desenvolvimento
Scripts disponíveis
<table> <tr> <td><code>npm start</code></td> <td>Inicia o servidor de desenvolvimento</td> </tr> <tr> <td><code>npm run android</code></td> <td>Executa no Android</td> </tr> <tr> <td><code>npm run ios</code></td> <td>Executa no iOS</td> </tr> <tr> <td><code>npm run web</code></td> <td>Executa na web</td> </tr> <tr> <td><code>npm test</code></td> <td>Executa os testes</td> </tr> <tr> <td><code>npm run build</code></td> <td>Gera build de produção</td> </tr> </table>
Configuração do Ambiente
<h4>1. Variáveis de Ambiente</h4> <ul> <li>Crie um arquivo <code>.env</code> na raiz do projeto</li> <li>Configure as variáveis necessárias (API URLs, chaves, etc.)</li> </ul><h4>2. Configuração do Firebase (se aplicável)</h4> <ul> <li>Adicione as configurações do Firebase no projeto</li> <li>Configure o arquivo de configuração apropriado</li> </ul>
🤝 Contribuição
Contribuições são sempre bem-vindas! Para contribuir:

<ol> <li>Faça um fork do projeto</li> <li>Crie uma branch para sua feature (<code>git checkout -b feature/AmazingFeature</code>)</li> <li>Commit suas mudanças (<code>git commit -m 'Add some AmazingFeature'</code>)</li> <li>Push para a branch (<code>git push origin feature/AmazingFeature</code>)</li> <li>Abra um Pull Request</li> </ol>
📄 Licença
Este projeto está sob a licença MIT. Veja o arquivo <a href="LICENSE">LICENSE</a> para mais detalhes.

👨‍💻 Autor
Desenvolvido por <strong>Greidimar</strong> - <a href="https://github.com/greidimar">GitHub</a>

📞 Suporte
Se você encontrar algum problema ou tiver sugestões, por favor abra uma <a href="https://github.com/greidimar/MinhaConsulta_app/issues">issue</a> no repositório.

<div align="center"> <em>Este projeto está em desenvolvimento. Novas funcionalidades e melhorias estão sendo implementadas continuamente.</em> </div>
html
<!-- Este é o conteúdo HTML que você pode usar diretamente no README.md -->
<!-- Basta copiar e colar no seu arquivo README.md no GitHub -->
O código HTML acima está formatado para ser usado diretamente no arquivo README.md do GitHub. O GitHub suporta HTML limitado em arquivos Markdown, então as tags mais complexas foram substituídas por equivalente em Markdown onde necessário, mantendo uma aparência profissional e organizada.
