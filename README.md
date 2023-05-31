# Kata - Site Básico  
  
Um site com três páginas (Início, Sobre e Contato) em três arquivos HTML (index.html, sobre.html e contato.html).
  
Passos:  

1. Abrir o Terminal (PowerShell, no Windows)
2. ```cd Desktop```
3. ```mkdir novoProjeto```
4. ```cd novoProjeto```
5. ```code .```

6. Em um arquivo index.html, criar a estrutura básica   
```html:5```   
```header+main+footer``` (dentro do body)  
  
  
7. Criar um menu no header  
```nav>(a*3)``` (e preencher com o nome das páginas - Início, sobre, contato)   
    
7.1 Usar o atributo ```href``` da tag ```<a>``` para apontar para os arquivos correspondentes:  
- ```index.html```  
- e os que ainda não criamos: ```sobre.html``` e ```contato.html```  

8. Criar algum conteúdo fictício dentro do main  
```(p>lorem)*12```    

9. Criar as outras páginas (sobre.html e contato.html)  
9.1 Já podemos aproveitar e copiar o menu de navegação (tag ```<nav>```) da página inicial nas outras duas páginas.  

10. Dentro da uma pasta styles, criar um arquivo style.css e copiar/colar os seguintes estilos:   
```
body {
    font-family: sans-serif;
    margin: auto;
    width: 70%;
}

header {
    background-color: aquamarine;
    padding: 2rem;
}
```

11. Inserir no ```<head>``` (não confundir com o ```<header>```) de cada página o link para o CSS:   
```
    <link rel="stylesheet" href="style.css">
```


