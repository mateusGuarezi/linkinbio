Página "Link na Bio" para Instagram, Twitter, Tumblr, etc.

Introdução
Como muitos de vocês devem saber, é possível ter apenas um link em suas bios do Instagram e Twitter. Para contornar isso, muitos usuários usam aplicativos de terceiros para links na bio para exibir vários links. No entanto, a desvantagem disso é que você está desviando a atenção das pessoas da sua marca ao redirecioná-las para outro site em vez do seu próprio.

Algumas dessas opções de terceiros permitem o uso de um domínio personalizado, mas isso geralmente é uma opção premium pela qual é necessário pagar.

Dado que muitas dessas páginas de links na bio de terceiros são apenas listas de links, decidi criar a minha própria solução.

Você pode ver um exemplo de como isso se parece aqui: https://alexhyett.com/links.

Você pode ler mais sobre isso no meu blog: Como Criar uma Página de Link na Bio para o Instagram.

Como usar
Primeiro, você precisa atualizar a seção do perfil, alterando a tag h1 para o seu próprio nome, bem como a localização e as informações da bio. Você também vai querer adicionar sua própria foto de perfil. Sua foto de perfil deve ser quadrada.

Em seguida, você precisa adicionar links para todos os seus perfis.

Você pode fazer isso copiando e colando um dos blocos de link e atualizando o texto e os links.

html

```
<a href="https://instagram.com/alexhyettdev" class="block link">
    <div class="image-float instagram">
        <div class="beacon instagram"></div>
        <div class="image">
            <img src="images/instagram.svg" />
        </div>
    </div>
    <div>
        <h2>Instagram</h2>
        <div>@alexhyettdev</div>
    </div>
    <div class="arrow">
        <i class="fas fa-arrow-right"></i>
    </div>
</a>
```

Cores de Mídias Sociais
As seguintes classes CSS foram adicionadas e podem ser usadas para mostrar as cores corretas para o ícone e a sombra da imagem.

amazon
dev
facebook
github
google
instagram
linkedin
medium
paypal
twitter
youtube

Ícone de Destaque (Beacon)
Se você deseja que um ou mais dos links se destaquem, pode aplicar a div de "beacon" logo acima da div da imagem para que ela pulse.

html
Copy code
<div class="beacon instagram"></div>
Imagens
Incluí logotipos para todos os sites mencionados acima na seção de cores de mídias sociais.
