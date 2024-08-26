# Hello World Dinâmico

Esta é uma aplicação web simples que exibe uma saudação em diferentes idiomas e permite personalizar a saudação com seu nome. A aplicação também oferece um modo noturno e salva as preferências do usuário usando `localStorage`.

## Funcionalidades

- **Saudação Multilíngue:** Exibe a saudação "Olá, Mundo!" em cinco idiomas diferentes: Português, Inglês, Espanhol, Francês e Italiano.
- **Personalização da Saudação:** Permite ao usuário personalizar a saudação com seu nome.
- **Modo Noturno:** Alterna entre modo claro e modo noturno.
- **Salvamento de Preferências:** As preferências de idioma, saudação personalizada e tema são salvas no `localStorage` do navegador, sendo mantidas mesmo após o fechamento da página.

## Tecnologias Utilizadas

- **HTML5:** Estrutura básica da aplicação.
- **CSS3:** Estilização da aplicação, com suporte a animações e temas.
- **JavaScript (ES6+):** Lógica da aplicação para manipulação do DOM, mudança de temas, e personalização da saudação.
- **Google Fonts:** Uso da fonte "Roboto" para a tipografia.

## Estrutura do Projeto

```bash
├── index.html         # Estrutura HTML da aplicação
├── styles.css         # Estilos CSS para a aparência e tema da aplicação
└── script.js          # Lógica JavaScript para interatividade e salvamento de preferências
```

## Como Usar

1. Clone ou faça o download do repositório.
2. Abra o arquivo `index.html` em seu navegador preferido.
3. Use o campo de texto para digitar seu nome e personalize a saudação.
4. Selecione o idioma desejado no menu suspenso.
5. Use o botão "Modo Noturno" para alternar entre o modo claro e noturno.
6. Suas preferências serão automaticamente salvas e carregadas na próxima vez que você visitar a página.

## Personalização

- **Temas:** A aplicação suporta tanto tema claro quanto tema escuro, que podem ser facilmente personalizados alterando as variáveis de CSS no início do arquivo `styles.css`.
- **Idiomas:** Você pode adicionar mais idiomas ao modificar o objeto `greetings` e a função `getGreetingPrefix` no arquivo `script.js`.

## Requisitos

- Navegador moderno com suporte a ES6+ para total compatibilidade.
  
## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir uma issue ou enviar um pull request com melhorias.
