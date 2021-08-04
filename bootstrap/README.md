# Bootstrap
- Framework ou biblioteca desenvolvimento
- Modular
- Componentes ricos
- Responsivo
- Mobile-first
- Amplamente utilizada

## Biblioteca x Framework
- Biblioteca: oferece objetos / classes prontas para uso
- Framework: oferece um conjunto de bibliotecas
- Biblioteca: recurso para trabalhar
- Framework: metodologia de trabalho
- Biblioteca: te leva ao destino
- Framework: te ensina a chegar

## Desenvolvimento ágil
- Metodologias: Scrum, Kanban, XP
- Entrega de valor para o negócio
- Ciclos evolutivos
- Separar grandes projetos em pequenas entregas
- Estar envolvido x comprometido

## Vantagens
- Uso simples
- Menos código
- Abstração de estilos
- Documentação completa: https://getbootstrap.com/

## Desvantagens
- Uso excessivo
- Override de estilos (sobreposição)
- Abstração de estilos

### Com Bootstrap
```
 <a class="btn btn-lg">Botão</a>
```

### Sem Bootstrap
```
 <a class="botao botao-grande">Botão</a>

 <style>
 html {
     font-size: 62.5% 
 }

 .botao {
    background-color: #ccc; 
    border-radius: 2px; 
    display: block;
    font-family: sans-serif;
    font-size: 1.6rem;
    padding: 1rem 2rem;
    margin: 5px auto;
    ...
 }

 .botao.grande {
    font-size: 2rem;
 }

 .botao:hover { ... }
 .botao:active { ... }
 .botao:visited { ... }
 
 </style>

```
