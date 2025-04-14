>[!NOTE]
>Projeto desenvolvido como parte das atividades da NI da matéria de **Programação Mobile** do terceiro semestre do curso de Análise e Desenvolvimento de Sistemas.

# Questão 3 - NI

<details>
  <summary>Enunciado</summary>
  
Desenvolva um app no Android Studio para o registro de clientes de uma loja virtual **(Tem de Tudo)**, no qual tem domínio *www.temdetudo.com.br*. A loja virtual deseja criar um aplicativo para registrar novos clientes. O aplicativo será utilizado em eventos ou em lojas físicas para facilitar o processo de cadastro, capturando apenas o nome do cliente inicialmente, com uma interface amigável e intuitiva. O app permitirá que o usuário insira seu nome e faça um cadastro inicial, que será exibido ao final do processo. O fluxo de navegação será desde uma tela de boas-vindas até o registro completo do cliente:

- **Activity 1** *(Tela de Boas-Vindas)*: Uma tela com a logomarca da loja e um botão que levará o usuário para o cadastro.
- **Activity 2** *(Formulário de Cadastro)*: Tela onde o cliente insere seu nome em um campo de texto e, ao clicar em um botão, será redirecionado para a última tela.
- **Activity 3** *(Confirmação de Cadastro)*: Exibe uma mensagem de boas-vindas personalizada com o nome inserido pelo cliente e uma imagem de "cadastro completo", além de um botão para voltar à tela inicial.

### REQUISITO DO PROJETO:
- Como requisito do projeto, deve ser utilizado obrigatoriamente `1 Button`, `1 TextView`, `1 TextInputLayout`, `1 ImageView` e `3 Activity` pelo menos.
- **Navegação entre Activities:** O app deve conter 3 activities com navegação via **botões**. A primeira activity será a tela inicial com uma imagem da logomarca da loja e um botão para iniciar o cadastro. A segunda activity conterá o formulário, e a terceira exibirá a confirmação do cadastro.
- **Formulário com TextInputLayout:** Na segunda activity, deve haver um TextInputLayout para que o usuário insira seu nome. Ao clicar no botão de envio, o app deve capturar esse nome e passá-lo para a terceira activity.
- **Exibição de Texto Dinâmico:** A terceira activity deve conter um TextView que exibirá uma mensagem de confirmação personalizada, como *"Bem-vindo, [nome do cliente]!"*.
- **Uso de ImageView:** Cada activity deve conter uma ImageView:
  - *Activity 1:* Imagem com a logomarca da loja.
  - *Activity 2:* Uma imagem decorativa ou relacionada ao cadastro.
  - *Activity 3:* Uma imagem de "Cadastro Completo" para confirmar a finalização do registro.
- Botão de Retorno: Na terceira activity, deve haver um botão que permita retornar à primeira
activity, possibilitando o cadastro de novos clientes.

</details>


## 👤Informações: 

- **Nome:** Felipe Oluwaseun Santos Ojo
- **RA:** 24026245
- **Disciplina:** Programação Mobile


## Clonando o repositório:

Para ter acesso ao repositório na sua máquina, basta digitar o seguinte comando dentro do **terminal**:

```
git clone https://github.com/lipeoe/QuestaoTresNI
```

