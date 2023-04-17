# Responsivenavbar
A responsive navigation bar according to screen size, highly customizable.

## Requirements 
- Import "Font Awesome" to your website.

## How to use it in your project?
- The first step is to import the CSS for this navigation bar. To do so, insert this line of code in your HTML file: 
```<link rel="stylesheet" href="https://raw.githubusercontent.com/nukhes/responsivenavbar/main/style.css?token=GHSAT0AAAAAACBD3KOS5JPOC7FWGASM5OYAZBWPOCA">```
- With the CSS successfully imported, write the structure of the navigation bar:
```    
<!-- Navigation bar -->
    <nav>
        <input type="checkbox" id="check">
        <label for="check" id="navbtt">
                <i class="fas fa-bars"></i>
        </label>
        <span id="logo">Logo</span>
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">Services</a></li>
            <li><a href="#">About</a></li>
        </ul>
    </nav>
```
- Now you just need to customize your navigation bar according to your preferences.
