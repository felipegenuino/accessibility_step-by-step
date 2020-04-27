# Accessibility step-by-step

 

1. [leitor de tela](#1)
    1.2. [Instalação e configuração ](#1-1)
    1.3. [Navegação](#1.3)


## <a name="1-1">#</a> 1.1 Leitor de tela
 - [Windows](https://www.nvaccess.org/download/) 
 - Linux: 
 - MacOS:  

 Atualizar NVDA:  ![Atualizar NVDA](src/atualizar.jpg) 
 Realçar foco:  ![Tela de configuração do NVDA](src/ativar-realce.jpg) 

## <a name="1-2">#</a> 1.2 Como funciona a navegação com leitor de telas 
Lorem ipsum dolor sit amet, consectetur adipisicing elit. Molestias necessitatibus autem, doloremque rerum possimus eaque dolorem mollitia hic quae nisi molestiae ab odit quibusdam commodi sint quo nesciunt enim! Ipsa?

- Navegação [Guia NVDA](https://www.nvaccess.org/files/nvda/documentation/userGuide.html?)
    - h: navegação por títulos
    - d: navegação por áreas 
    - f: navegação por formulários 
    - t: navegação por tabelas

 

## <a name="1-3">#</a> 1.3 Identificar blocos/áreas da aplicação 
Lorem ipsum dolor sit amet, consectetur adipisicing elit. Molestias necessitatibus autem, doloremque rerum possimus eaque dolorem mollitia hic quae nisi molestiae ab odit quibusdam commodi sint quo nesciunt enim! Ipsa?

## <a name="1-4">#</a> 1.4 Adicionar role="region" aria-label="nome-da-regiao"   
Lorem ipsum dolor sit amet, consectetur adipisicing elit. Molestias necessitatibus autem, doloremque rerum possimus eaque dolorem mollitia hic quae nisi molestiae ab odit quibusdam commodi sint quo nesciunt enim! Ipsa?

## <a name="1-5">#</a> 1.5 Implementar skip to 
Lorem ipsum dolor sit amet, consectetur adipisicing elit. Molestias necessitatibus autem, doloremque rerum possimus eaque dolorem mollitia hic quae nisi molestiae ab odit quibusdam commodi sint quo nesciunt enim! Ipsa?

```css
 .sr-only {
    position: absolute !important;
    left: -10000px !important;
    width: 1px !important;
    height: 1px !important;
    overflow: hidden !important;
}
```

```html
 <h3 class="sr-only"> ${tarjas} ${partes} ${numeroDoProcesso} </h3>
```




## <a name="1-6">#</a> 1.6 Teste automatizado 
Lorem ipsum dolor sit amet, consectetur adipisicing elit. Molestias necessitatibus autem, doloremque rerum possimus eaque dolorem mollitia hic quae nisi molestiae ab odit quibusdam commodi sint quo nesciunt enim! Ipsa?
 
 Falha ao inserir o disco óptico virtual C:\Program Files\Oracle\VirtualBox\VBoxGuestAdditions.iso na máquina ubuntu 18.

- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item


First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column


~~this~~


