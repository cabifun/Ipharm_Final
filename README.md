# Ipharm_Final

iPharm: Farmácia Virtual

iPharm é um aplicativo que simula uma farmácia virtual, projetado para oferecer uma experiência simples e eficiente ao usuário. O aplicativo foi desenvolvido como parte de um projeto acadêmico, utilizando Android Studio, Jetpack Compose, Firebase e MVVM. O objetivo é criar uma interface funcional e visualmente atraente, simulando um sistema real para a compra de medicamentos e serviços relacionados.

Principais Funcionalidades:

1. Login e Cadastro

    Tela de Login: Permite que usuários existentes acessem suas contas.
    Tela de Cadastro: Facilita o registro de novos usuários com validação de dados.

2. Catálogo de Medicamentos

    Apresenta uma lista de medicamentos disponíveis.
    Informações detalhadas sobre os produtos, incluindo preços e descrições.

3. Carrinho de Compras

    Adicionar e remover itens no carrinho.
    Visualização de todos os produtos selecionados antes da compra.

Decisões de Design:

1. Arquitetura

    MVVM (Model-View-ViewModel): Garantiu uma separação clara entre lógica de negócios e interface do usuário, facilitando manutenção e expansão.
    Room: Gerenciou a persistência de dados localmente de forma eficiente.

2. Interface do Usuário

    Jetpack Compose: Escolha pela flexibilidade e modernidade para criar interfaces reativas e elegantes.
    Navegação Simplificada: O uso de Navigation-Compose garantiu transições suaves entre as telas.

3. Usabilidade

    Foco na simplicidade e acessibilidade, garantindo que o usuário consiga realizar todas as tarefas com facilidade.

Tecnologias Utilizadas

    Linguagem: Kotlin
    Interface: Jetpack Compose
    Banco de Dados: Firebase
    Arquitetura: MVVM
    Ferramentas: Android Studio

Como Rodar o Projeto

    Clone o repositório:

git clone <URL_DO_REPOSITORIO>

Abra o projeto no Android Studio.
Configure o emulador ou conecte um dispositivo físico.
Clique em Run para iniciar o aplicativo.
