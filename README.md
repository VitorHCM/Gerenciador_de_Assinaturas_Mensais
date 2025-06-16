# Atividade Prática: Gerenciador de Assinaturas Mensais
- Repositório criado para a realização da atividade em sala de Programação ´para Dispositivos Móveis

## Integrantes:
- Arthur Brito: 2312130001
- Lucas Faria: 2312130040
- Vinicius Von:2312130010
- Vitor Hugo Campos: 2312130182

## Funcionalidades:

### Pagina Inicial

- O aplicativo inicia em sua página inicial, onde é mostrado o total gasto por mês em assinaturas, assim como as 3 a 5 próximas assinaturas que irão vencer;
- A partir do menu inferior, é possível acessar as páginas de adição de assinaturas e lista de assinaturas;

### Página Adicionar Assinatura

- O formulário da página de adicionar assinaturas permite a adição de assinaturas junto de seus valores e data de vencimento mensal, assim como sua categoria; 
- Cada assinatura adicionada é salva com a implementação do Firebase e em seguida puxada da data base para a página de lista de assinaturas;

### Página Lista de Assinaturas

- Na página da lista de assinaturas, através da leitura em tempo real da Firestore, as assinaturas são exibidas mostrando seus atributos;
- Cada assinatura possui um botão para atualizar os dados inseridos, assim como um outro botão para excluir a assinatura completamente;

## Execução do Código:

- Importe este repositorio do git hub;
- Abra a pasta Gerenciador_de_Assinaturas_Mensais/PDM-trabalho-feature-db-and-form;
- Abra o terminal do VS Code e rode:
### npm install
- Isso instala todas as bibliotecas que estão listadas no package.json.
- Instale o Expo CLI (se ainda não tiver):
-- npm install -g expo-cli
- Em seguida rode o app:
-- npx expo start
- Um navegador abrirá com o Expo Developer Tools.
- Escaneie o QR Code com o app Expo Go no seu celular (Android/iOS). Alternativamente o codigo pode ser rodado em emuladores de android no computador também.
