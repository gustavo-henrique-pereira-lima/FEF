# FRONT END FRAMEWORK (FEF)
> Diosne Marlon Furtado dos Santos - 04109634

> Gustavo Henrique Pereira Lima - 04098527

> Kauan Leandro Gonçalves de Araújo Moreira - 04113076

> Paulo Sérgio Barros Teixeira - 04147128

> Status: This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 16.2.7.
<h1>Introdução ao Projeto:</h1>
Este projeto demonstra a criação de uma aplicação web utilizando o framework Angular. O Angular é amplamente utilizado para o desenvolvimento front-end, sendo uma das principais opções comumente usuais para a criação de interfaces de usuário interativas e dinâmicas disponíveis atualmente.

O Angular é mantido pelo Google e é uma evolução do AngularJS. Ele é uma poderosa ferramenta para o desenvolvimento de aplicativos web modernos e tem uma comunidade ativa de desenvolvedores em todo o mundo.

O framework utilizado oferece uma estrutura robusta e uma ampla gama de recursos que tornam o desenvolvimento de interfaces de usuário agradáveis e eficientes.

## Projeto de Tela de Login e Cadastro com Angular.

Descrição do Projeto: 
Este projeto consiste em um exemplo simples de uma aplicação web desenvolvida com o framework Angular. Ele demonstra a criação de duas telas interativas: uma tela de login e uma tela de cadastro. O objetivo é mostrar como o Angular pode ser usado para criar interfaces de usuário funcionais e interativas.

Recursos Principais: 

• Tela de login com campos para nome de usuário e senha.

• Tela de cadastro que permite ao usuário criar uma nova conta.

• Validação de formulários para garantir a entrada de dados corretos.

• Roteamento para navegar entre telas de login e cadastro.

### Objetivos do Projeto: 

• Aprender a usar o Angular para desenvolver interfaces de usuário. 

• Demonstrar a capacidade de criar telas interativas e funcionais. 

• Fornecer um exemplo de boas práticas de desenvolvimento com Angular.

## Finalidade:

A escolha do Angular como framework para este projeto foi feita com base em considerações específicas relacionadas à finalidade e ao escopo deste trabalho.
### Razões para a Escolha do Angular:

1. Desempenho e Escalabilidade: O Angular é conhecido por seu desempenho sólido, o que o torna adequado para a criação de aplicativos web reativos e escaláveis, especialmente importante para as telas de login e cadastro que podem receber um grande número de interações dos usuários.

2. Facilidade de Uso: O Angular oferece uma estrutura de desenvolvimento bem estruturada e muitos recursos que facilitam a criação de interfaces de usuário interativas, fundamental para o objetivo deste projeto.

3. Comunidade e Recursos Disponíveis: O Angular possui uma grande comunidade de desenvolvedores, documentação extensiva e uma variedade de recursos disponíveis, incluindo bibliotecas e plugins.

4. Integração com Roteamento: O Angular oferece um sistema de roteamento poderoso e flexível, essencial para a navegação entre as telas de login e cadastro.

5. Consistência com o Escopo do Projeto: O Angular atende diretamente ao escopo deste projeto, que é criar uma aplicação web interativa com telas de login e cadastro, devido à sua estrutura modular e arquitetura de componentes.

Instruções de uso

## Para executar este projeto localmente, siga as etapas a seguir:
1. Clone o repositório em sua máquina;

2. Abra um terminal na pasta do projeto e execute `npm install` para instalar as dependências;

3. Execute `ng serve` para iniciar o servidor de desenvolvimento;

4. Abra um navegador e acesse `http://localhost:4200` para visualizar o aplicativo, neste caso a página web que aparecerá no navegador.

5. É importante ter instalado no seu computador o Node.js e o Git, para que não haja nenhum problema ao utilizar o terminal para executar os comandos necessários. Ambos podem ser encontrados em suas plataformas oficiais, sendo, respectivamente, `nodejs.org` e `https://git-scm.com/`. 

6. Quanto a configuração do projeto, atente-se às seguintes instruções:
* Clone este repositório em sua máquina local usando o seguinte comando: `git clone https://github.com/gustavo-henrique-pereira-lima/FEF.git`. 

* Navegue até o diretório do projeto, neste caso, usando o comando `cd nome-do projeto` (nesse caso, pode modificar para `cd-FEF`, por exemplo). 

* Instale as dependências do projeto executando o comando `npm install`.

* Quanto à execução do projeto, é necessário utilizar o comando `ng serve` para iniciar o servidor de desenvolvimento. Posteriormente, isso iniciará o servidor de desenvolvimento do Angular e tornará o aplicativo acessível no link fornecido na etapa 4 do tópico "Instruções de Uso", permitindo, assim, a visualização do projeto em execução.

7. Soluções de Problemas Comuns: Se você encontrar problemas ao executar o projeto, verifique a documentação do Angular (`https://angular.io/docs`) ou recursos de suporte online para soluções comuns.

8. Ambiente de Desenvolvimento Recomendado: Recomendamos o uso de ambiente de desenvolvimento integrado (IDE) para uma experiência de desenvolvimento mais eficiente. Alguns IDEs populares para o desenvolvimento Angular incluem Visual Studio Code (utilizado neste projeto) e WebStorm. (`Visual Studio Code - https://code.visualstudio.com/`, WebStorm - `https://www.jetbrains.com/webstorm/`) 

Obs.: É essencial realizar a leitura das documentações oficiais fornecidas por meio dos links na descrição das etapas, com o objetivo de compreender as funcionalidades desses recursos utilizados para a criação desse projeto, a fim de aprimorar o desenvolvimento caso haja esse desejo. Além disso, deve-se ressaltar que foram utilizadas as linguagens `HTML` (Hypertext Markup Language) e `CSS` (Cascading Style Sheets) em junção com o framework Angular na construção do código que permeia a Tela de Login e Tela de Cadastro.

## Código documentado (Detalhamento):

### HTML DO LOGIN

    <form>    
    
      <!-- Essa div é um contêiner geral que agrupa todo o conteúdo do formulário. -->
      <div class="container">
      
        <div>
          <p class="login">Login</p>
        </div>
        
        <!-- Uma quebra de linha (espaço em branco) para adicionar espaço vertical. -->
        
        <br>
        
        <!-- Esta div cria um grupo para o campo de entrada de e-mail. -->
        <div class="form">
          <label for="exampleInputEmail1" class="form-label"></label>
          <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp" placeholder="Digite seu E-mail">
        </div> 
        <br>
        
        <div class="form">
          <label for="exampleInputPassword1" class="form-label"></label>
          <input type="password" class="form-control" id="exampleInputPassword1" placeholder="Digite sua senha">
        </div>
        <br>
        
        <!--<button type="submit" class="btn btn-primary">Submit</button>-->
        <div class="botao">
          <div class="entrar">
            <a class="seta" href="#"><img src="/assets/seta.png" alt=""></a>
          </div>
          
          <div class="renovarSenha">
            <a href="">Esqueci minha senha</a>
          </div>
        </div>
        <br>
    
        <!-- Esta div contém um link "Cadastre-se," 
          que provavelmente leva os usuários para a página de cadastro quando clicado. -->

        <div class="cadastrar">
          <a href="/cadastro">Cadastre-se</a>
        </div>
        
      </div>
    </form>


### CSS DO LOGIN
    
    /* agrupa todo o conteúdo do formulário. */
    
    .container{
        background-image: url(/assets/fundo-tom-roxos.png);
        display: flex;
        flex-direction: column;
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
        padding: 50px;
        width: 400px;
        border-radius: 10px;
        margin-top: 30px;
        box-shadow: 3px 3px 7px;
    }
    
    /* estilo de login*/
    
    .login{
        font-size: 40px;
        color: white;
        display: flex;
        justify-content: center;
    }
    
    .form{
        gap: 10px;
    }
    
    input{
        width: 100%;
        padding: 15px;
        border-radius: 5px;
        border: 0;
        box-shadow: 1px 1px 5px black;
        background-color: #c9c9c9;
    }
    
    /* estilo dos butons*/
    
    .botao{
        display: grid;
        grid-template-columns: 1fr 1fr;
        gap: 10px;
    }
    
        .entrar{
            width: 100%;
            background-color: #B15EFF;
            display: flex;
            justify-content: center;
            border-radius: 10px;
            height: 100%;
            border-radius: 5px;
            box-shadow: 1px 1px 5px;
        }
        
            .seta{
                height: 30px;
            }
            
        .renovarSenha{
            background-color: #FFC436;
            display: flex;
            justify-content: center;
            align-items: center;
            border-radius: 5px;
            font-size: 13px;
            box-shadow: 1px 1px 5px;
        }
        
    .cadastrar{
        background-color: #C70039;
        display: flex;
        justify-content: center;
        font-size: 30px;
        border-radius: 5px;
        box-shadow: 1px 1px 5px;
    }

### HTML DO CADASTRO:
    
    <div class="container">
        <div class="form">
            <form action="#">
            
                <!-- Essa div contém o título "Cadastre-se" que aparece no topo do formulário. -->
                
                <div class="title">
                    <h1>Cadastre-se</h1>
                </div>
                
                <!-- Esta div agrupa várias entradas de informações no formulário, como nome,
                    sobrenome, e-mail, número de celular, senha e confirmação de senha. -->
                    
                <div class="input-group">
                    <div class="input-box">
                        <label for="firstname">Primeiro nome</label>
                        <input id="firstname" type="text" name="firstname" placeholder="Digite seu primeiro nome" required>
                    </div>
    
                    <div class="input-box">
                        <label for="lastname">Sobrenome</label>
                        <input id="lastname" type="text" name="lastname" placeholder="Digite seu sobrenome" required>
                    </div>
    
                    <div class="input-box">
                        <label for="email">E-mail</label>
                        <input id="email" type="email" name="email" placeholder="Digite seu email" required>
                    </div>
    
                    <div class="input-box">
                        <label for="number">Celular</label>
                        <input id="number" type="tel" name="number" placeholder="(xx) xxxxx-xxxx" required>
                    </div>
    
                    <div class="input-box">
                        <label for="password">Senha</label>
                        <input id="password" type="password" name="password" placeholder="Digite sua senha" required>
                    </div>
    
                    <div class="input-box">
                        <label for="Confirmpassword">Confirme sua senha</label>
                        <input id="Confirmpassword" type="password" name="Confirmpassword" placeholder="Confirme sua senha" required>
                    </div>
                </div>
                
                <div class="gender-inputs">
                    <!-- Esta div agrupa as opções de gênero, como "Feminino," "Masculino," "Outros" e "Prefiro não dizer." -->
                    <div class="gender-tittle">
                        <h6>Gênero</h6>
                    </div>
    
                    <div class="gender-group">
                        <div class="gender-input">
                            <input type="radio" id="female" name="gender">
                            <label for="female">Feminino</label>
                        </div>
    
                        <div class="gender-input">
                            <input type="radio" id="male" name="gender">
                            <label for="male">Masculino</label>
                        </div>
    
                        <div class="gender-input">
                            <input type="radio" id="others" name="gender">
                            <label for="others">Outros</label>
                        </div>
    
                        <div class="gender-input">
                            <input type="radio" id="none" name="gender">
                            <label for="none">Prefiro não dizer</label>
                        </div>
                    </div>
                </div>
                
                <!-- Esta div contém um botão "Continuar." Quando clicado, 
                    o botão pode realizar alguma ação no lado do cliente ou redirecionar o usuário 
                    para outra página, embora o link no botão esteja configurado como "#" (um link vazio). -->
                    
                <div class="continue-button">
                    <button><a href="#">Continuar</a></button>
                </div>
                
                <!-- Esta div contém um botão "Voltar" que,
                     quando clicado, redireciona o usuário para a página "/login". -->
                     
                <br>
                <div class="voltar">
                    <button><a href="/login">Voltar</a></button>
                </div>
                
            </form>
        </div>
    </div>

### CSS DO CADASTRO
    body {
        width: 100%;
        height: 100vh;
        display: flex;
        justify-content: center;
        align-items: center;
        background: #0cBce94d;
    }
    
    /* agrupa todo o conteúdo do formulário.*/
    
    .container {
        width: 80%;
        height: 100%;
        display: flex;
        box-shadow: 5px 5px rgba(0, 0, 0, .212);
    }
    
    /* representa a área do formulário */
    
    .form {
        width: 50%;
        display: flex;
        justify-content: center;
        align-items: center;
        flex-direction: column;
        background-color: #fff;
        padding: 3rem;
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
        box-shadow: 3px 3px 10px ;
        border-radius: 15px;
    }
    
    .form-header {
        margin-bottom: 3rem;
        display: flex;
        justify-content: space-between;
    }
    
    .login-button {
        display: flex;
        align-items: center;
    }
    
    .login-button button {
        border: none;
        background-color: #6c63ff;
        padding: 0.4rem 1rem;
        border-radius: 5px;
        cursor: pointer;
    }
    
    .login-button button:hover {
        background-color: #6b63fff1;
    }
    
    .login-button button a {
        text-decoration: none;
        font-weight: 500;
        color: #fff;
    }
    
    .form-header h1::after {
        content: '';
        display: block;
        width: 5rem;
        height: 0.3rem;
        background-color: #6c63ff;
        margin: 0 auto;
        position: absolute;
        border-radius: 10px;
    }
    
    .input-group {
        display: flex;
        flex-wrap: wrap;
        justify-content: space-between;
        padding: 1rem 0;
    }
    
    .input-box {
        display: flex;
        flex-direction: column;
        margin-bottom: 1.1rem;
    }
    
    .input-box input {
        margin: 0.6rem 0;
        padding: 0.8rem 1.2rem;
        border: none;
        border-radius: 10px;
        box-shadow: 1px 1px 6px #0000001c
    }
    
    .input-box input:hover {
        background-color: #eeeeee75;
    }
    
    .input-box input:focus-visible {
        outline: 1px solid #6c63ff;
    }
    
    .input-box label,
    .gender-title h6 {
        font-size: 0.75rem;
        font-weight: 600;
        color: #000000c0;
    }
    
    .input-box input::placeholder {
        color: #000000be;
    }
    
    .gender-group {
        display: flex;
        justify-content: space-between;
        margin-top: 0 0.5rem;
    }
    
    .gender-input {
        display: flex;
        align-items: center;
    }
    
    .gender-input input {
        margin-right: 0.35rem;
    }
    
    .gender-input label {
        font-size: 0.81rem;
        font-weight: 600;
        color: #000000c0;
    }
    
    .continue-button button {
        width: 100%;
        margin-top: 2.5rem;
        border: none;
        background-color: #6c63ff;
        padding: 0.62rem;
        border-radius: 5px;
        cursor: pointer;
    }
    
    .continue-button button:hover {
        background-color: #6b63fff1;
    } 
    
    .continue-button button a {
        text-decoration: none;
        font-size: 0.93rem;
        font-weight: 500;
        color: #fff;
    }
    
    .voltar button{
        width: 100%;
        border: none;
        background-color: #6c63ff;
        padding: 0.62rem;
        border-radius: 5px;
        cursor: pointer;
    }
    
    .voltar button:hover {
        background-color: #6b63fff1;
    } 
    
    .voltar button a {
        text-decoration: none;
        font-size: 0.93rem;
        font-weight: 500;
        color: #fff;
    }
    
    @media screen and (max-width: 1330px) {
        .form-image {
            display: none;
        }
        .container {
            width: 50%;
        }
        .form {
            width: 100%;
        }
    }
    
    @media screen and (max-width: 1064px) {
        .container {
            width: 90%;
            height: auto;
        }
        .input-group {
            flex-direction: column;
            overflow-y: scroll;
            flex-wrap: nowrap;
            max-height: 10rem;
            padding-right: 5rem; 
        }
        .gender-inputs {
            margin-top: 2rem;
        }
        .gender-group {
            flex-direction: column;
        }
        .gender-input {
            margin-top: 0.5rem;
        }
    };

## Descrições dos componentes da tela de login no código

1. Contêiner Geral:
   - A primeira div é um contêiner geral que agrupa todo o conteúdo do formulário de login.

2. Título "Login":
   - Um elemento p com a classe "login" que exibe o título "Login" na tela.

3. Campo de E-mail:
   - Uma div que cria um grupo para o campo de entrada de e-mail.
   - Um label vazio com a classe "form-label" que fornece uma etiqueta visual para o campo de entrada de e-mail.
   - Um input de tipo "email" com a classe "form-control" que permite que os usuários insiram seu endereço de e-mail. O atributo placeholder fornece um espaço reservado para orientação.

4. Campo de Senha:
   - Outra div  que cria um grupo para o campo de entrada de senha.
   - Um label vazio com a classe "form-label" que atua como uma etiqueta visual para o campo de entrada de senha.
   - Um input de tipo "password" com a classe "form-control" que permite aos usuários inserir sua senha. O atributo placeholder oferece uma dica de inserção.

5. Botões "Entrar" e "Esqueci Minha Senha":
   - Uma div com a classe "botao" que contém duas partes:
     - entrar: Uma div que inclui um link "Seta" que provavelmente é usado para submeter o formulário de login.
     - EsqueciMinharSenha: Uma div que contém um link "Esqueci minha senha," que os usuários podem usar para redefinir a senha.

6. Link "Cadastre-se":
   - Uma div com a classe "cadastrar" que contém um link "Cadastre-se." Ao clicar neste link, os usuários provavelmente serão redirecionados para a página de cadastro.

Descrições dos componentes do cadastro.component.html

1. Título "Cadastre-se":
   - Esta div contém o título "Cadastre-se" que aparece no topo do formulário. Ele fornece um título claro para a seção de cadastro.

2. Agrupamento de Entradas de Informação:
   - Esta div agrupa várias entradas de informações no formulário, incluindo nome, sobrenome, e-mail, número de celular, senha e confirmação de senha. Isso organiza os campos relacionados em uma seção coerente do formulário.

3. Entrada de Primeiro Nome:
   - Um campo de entrada para o primeiro nome, identificado pela etiqueta "Primeiro nome." O atributo required indica que o preenchimento deste campo é obrigatório.

4. Entrada de Sobrenome:
   - Um campo de entrada para o sobrenome, identificado pela etiqueta "Sobrenome". Assim como o campo anterior, este campo também requer preenchimento obrigatório.

5. Entrada de E-mail:
   - Um campo de entrada para o endereço de e-mail, identificado pela etiqueta "E-mail." Também possui a obrigatoriedade de preenchimento.

6. Entrada de Número de Celular:
   - Um campo de entrada para o número de celular, identificado pela etiqueta "Celular." Ele segue o formato "(xx) xxxxx-xxxx" e exige preenchimento obrigatório.

7. Entrada de Senha:
   - Um campo de entrada para a senha, identificado pela etiqueta "Senha." O preenchimento é obrigatório, e este campo é usado para criar uma senha.

8. Confirmação de Senha:
   - Um campo de entrada para a confirmação da senha, identificado pela etiqueta "Confirme sua senha." Isso ajuda a garantir que a senha seja inserida corretamente, com a obrigatoriedade de preenchimento.

9. Opções de Gênero:
   - Esta div agrupa as opções de gênero, incluindo "Feminino," "Masculino," "Outros" e "Prefiro não dizer." Os usuários podem selecionar uma das opções usando botões de rádio.

10. Botão "Continuar":
    - Esta div contém um botão "Continuar" que permite aos usuários prosseguir com o processo de cadastro. No entanto, o link no botão está configurado como "#" (um link vazio), o que significa que a ação real a ser executada pode depender da funcionalidade do aplicativo.

11. Botão "Voltar":
    - Esta div contém um botão "Voltar" que redireciona o usuário para a página "/login" quando clicado. Isso permite que os usuários voltem para a página de login, caso desejem retornar à etapa anterior.

Descrições dos componentes cadastro.component.css

1. Estilo do Corpo (body):
   - O seletor body estiliza o corpo da página. Ele configura a largura e altura como 100% da janela, centralizando o conteúdo vertical e horizontalmente. O plano de fundo é definido com a cor #0cBce94d, criando um fundo semitransparente.

2. Estilo do Contêiner (container):
   - O componente .container envolve todo o conteúdo do formulário. Define a largura como 80% da janela, centraliza o conteúdo vertical e horizontalmente, aplica uma sombra e uma borda arredondada.

3. Estilo da Área do Formulário (form):
   - O seletor .form estiliza a área do formulário. Define a largura como 50%, centraliza o conteúdo vertical e horizontalmente, cria um fundo branco, adiciona preenchimento e uma sombra suave. Ele é posicionado absolutamente no centro da tela.

4. Estilo do Botão de Login (login-button):
   - O .login-button estiliza o botão "Entrar." Define o estilo do botão com uma cor de fundo, preenchimento, borda arredondada e um cursor ao passar o mouse.

5. Estilo dos Campos de Entrada (input-box):
   - Os .input-box estilizam as caixas de entrada e seus rótulos correspondentes. Aplicam margens, preenchimento, borda e sombra suave nas caixas de entrada. Além disso, estilizam os rótulos e definem um estilo de foco quando o usuário interage com os campos.

6. Estilo dos Botões de Gênero (gender-input):
   - Este seletor estiliza as opções de gênero (Feminino, Masculino, Outros, Prefiro não dizer). Alinha horizontalmente as opções, aplica margens e estilos aos rótulos e botões de seleção de gênero.

7. Estilo do Botão de Continuar (continue-button):
   - O botão "Continuar" é estilizado com características semelhantes ao botão de "Entrar". Define a largura, margem superior, estilo do botão e estilo de foco.

8. Estilo do Botão de Voltar (voltar):
   - O botão "Voltar" possui estilos semelhantes aos botões anteriores e é usado para permitir que os usuários retornem à tela de login.

9. Estilos Responsivos (media queries):
   - Esses estilos responsivos se aplicam a diferentes tamanhos de tela. Eles ocultam a imagem em telas menores e ajustam o layout para proporcionar uma experiência de usuário aprimorada.

Essas descrições são fornecidas de acordo com o código CSS no arquivo cadastro.component.css e podem ser incluídas na documentação do projeto para ajudar os usuários a entender como o estilo é aplicado a cada componente.

## Descrições dos componentes login.component.css

1. .container: Esta classe agrupa todo o conteúdo do formulário. Ela define a imagem de fundo do formulário, o posicionamento no centro da tela, a largura, o espaçamento, o raio de borda, a margem e a sombra da caixa.

2. .login: Esta classe estiliza o texto "Login", definindo o tamanho da fonte, a cor e centralizando-o horizontalmente na tela.

3. .form: Define um espaçamento entre os elementos filhos dentro do formulário.

4. input: Estiliza todos os campos de entrada de texto no formulário, definindo a largura, preenchimento, borda arredondada, sombra, fundo e outras propriedades.

5. .botao: Esta classe cria um contêiner de botões de login e "Esqueci minha senha". Usa uma grade CSS para alinhar os botões lado a lado com um espaçamento entre eles.

6. .entrar: Estiliza o botão de "Entrar", definindo a largura, cor de fundo, centralização de conteúdo, raio de borda e sombra.

7. .seta: Estiliza a seta dentro do botão "Entrar", definindo a altura.

8. .EsqueciMinhaSenha: Estiliza o botão "Esqueci minha senha" com cores de fundo, centralização de conteúdo, sombra e tamanho de fonte.

9. .cadastrar: Estiliza o botão "Cadastre-se" com cores de fundo, centralização de conteúdo, tamanho de fonte, raio de borda e sombra.

