Nome do Plugin: A1 formulário

Descrição:
O plugin "A1 formulário" oferece uma solução simples e eficaz para adicionar um formulário de contato personalizado ao seu site WordPress. Com este plugin, os administradores do site podem criar um formulário de contato com campos para nome, e-mail e número de telefone (WhatsApp).
Os dados submetidos através do formulário são armazenados de forma segura no banco de dados do WordPress, permitindo que os administradores acessem e gerenciem os dados que foram enviados pelos visitantes do site.

Recursos Principais:

Formulário de Contato Personalizado: Adiciona um formulário de contato com campos para nome, e-mail e número de telefone (WhatsApp) ao site WordPress.
Armazenamento Seguro de Dados: Os dados submetidos através do formulário são armazenados de forma segura no banco de dados do WordPress, garantindo a integridade e a privacidade das informações dos visitantes.
Notificação via WhatsApp: Após o envio do formulário, os visitantes são redirecionados para o WhatsApp com uma mensagem predefinida, permitindo uma interação rápida e direta com os administradores do site.
Autor: Rafael Richer

Versão: 1.0

Ícone no Menu: O plugin é identificado por um ícone de envelope na área de administração do WordPress, facilitando o acesso ao formulário de contato.

Público-Alvo: O plugin "A1 formulário" é ideal para sites WordPress que desejam oferecer uma maneira fácil e conveniente para os visitantes entrarem em contato com os administradores do site. É especialmente útil para empresas, profissionais autônomos e qualquer pessoa que queira receber feedback ou solicitações de contato dos visitantes do site.


Form de exemplo:

<form id="formulario-contato" method="post">
            <label for="nome">Nome:</label>
            <input type="text" id="nome" name="nome" required><br>

            <label for="email">E-mail:</label>
            <input type="email" id="email" name="email" required><br>

            <label for="whatsapp">WhatsApp:</label>
            <input type="text" id="whatsapp" name="whatsapp" required><br>

            <button class="button button3" type="submit" name="enviar_formulario">Enviar</button>
  </form>

CSS Exemplo:

input[type="email"] {
    width: 100%;
}
input[type="text"] {
    width: 100%;
}
button.button.button3 {
    width: 100%;
    background-color: #18499d;
    color: white;
    box-shadow: 0 12px 16px 0 rgba(0,0,0,0.24), 0 17px 50px 0 rgba(0,0,0,0.19);
    border-radius: 5px;
}


