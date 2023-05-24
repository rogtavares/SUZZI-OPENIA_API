# OpenAI API SUZZI  - Node.js example app

Este é um ( aula) aplicativo gerador de nome de animal de estimação usado no tutorial de início rápido da API OpenAI . 
Ele usa a estrutura Next.js com React . 
Confira o tutorial ou siga as instruções abaixo para configurar.



[quickstart tutorial](https://platform.openai.com/docs/quickstart). It uses the [Next.js](https://nextjs.org/) framework with [React](https://reactjs.org/). Check out the tutorial or follow the instructions below to get set up.

![Text box that says name my pet with an icon of a dog](https://user-images.githubusercontent.com/10623307/213887080-b2bc4645-7fdb-4dbd-ae42-efce00d0dc29.png)


## configurar 

Se você não tiver o Node.js instalado, instale-o aqui (versão do Node.js >= 14.6.0 necessária)


Navegue até o diretório do projeto

   ```bash
   $ cd openai-quickstart-node
   ```

Instale os requisitos

   ```bash
   $ npm install
   ```

Faça uma cópia do arquivo de variáveis ​​de ambiente de exemplo

   On Linux systems: 
   ```bash
   $ cp .env.example .env
   ```
   On Windows:
   ```powershell
   $ copy .env.example .env
   ```
Adicione sua chave de API ao .envarquivo recém-criado [API key](https://platform.openai.com/account/api-keys) to the newly created `.env` file

7. Execute o aplicativo ..

   ```bash
   $ npm run dev
   ```

Agora você deve conseguir acessar o aplicativo em [http://localhost:3000](http://localhost:3000)! Para obter o contexto completo por trás deste aplicativo de exemplo, confira o tutorial .  [tutorial](https://platform.openai.com/docs/quickstart).
