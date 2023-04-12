# responsivenavbar
Uma barra de navegação responsiva de acordo com o tamanho da tela, altamente customizável
## como usa-la em seu projeto?
- o primeiro passo é importar o css desta barra, para isto insira está linha no html: 
```<link rel="stylesheet" href="https://raw.githubusercontent.com/nukhes/responsivenavbar/main/style.css?token=GHSAT0AAAAAACBD3KOS5JPOC7FWGASM5OYAZBWPOCA">```
- com o css importado com sucesso, escreva a estrutura da barra: 
```    
<!-- Barra de navegação -->
    <nav>
        <input type="checkbox" id="check">
        <label for="check" id="navbtt">
                <i class="fas fa-bars"></i>
        </label>
        <span id="logo">Logo</span>
        <ul>
            <li><a href="#">Início</a></li>
            <li><a href="#">Serviços</a></li>
            <li><a href="#">Sobre</a></li>
        </ul>
    </nav>
```
- agora é só editar sua barra de acordo com suas preferências.
