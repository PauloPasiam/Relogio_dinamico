# Relógio Dinâmico

Este repositório contém um exemplo simples de um relógio digital em tempo real, utilizando HTML, CSS e JavaScript. O projeto exibe a hora atual, atualizando automaticamente a cada segundo.

## Estrutura do Projeto

- **index.html**: O arquivo principal que contém a estrutura HTML do relógio.
- **assets/css/style.css**: Estilos para o relógio.
- **assets/js/script.js**: Lógica JavaScript para atualizar a hora.

## Como Funciona

O relógio é construído com uma estrutura simples em HTML. Utiliza-se JavaScript para capturar a hora atual e exibi-la em três partes: horas, minutos e segundos. O código JavaScript é responsável por atualizar os valores a cada segundo.

### Exemplo do código HTML:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="assets/css/style.css">
    <title>Relógio Digital</title>
</head>
<body>
    <div class="relogio">
        <div>
            <span id="horas">00</span>
            <span class="tempo">Horas</span>
        </div>
        <div>
            <span id="minutos">00</span>
            <span class="tempo">Minutos</span>
        </div>
        <div>
            <span id="segundos">00</span>
            <span class="tempo">Segundos</span>
        </div>
    </div>
    <script src="assets/js/script.js"></script>
</body>
</html>
```

## Como Usar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu_usuario/relogio-dinamico.git
   ```
2. Navegue até a pasta do projeto:
   ```bash
   cd relogio-dinamico
   ```
3. Abra o `index.html` em seu navegador.

## Contribuições

Sinta-se à vontade para contribuir com melhorias, correções ou novas funcionalidades. Para isso, crie uma nova branch, faça suas alterações e envie um pull request.

## Licença

Este projeto está licenciado sob a MIT License. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

Sinta-se à vontade para personalizar o estilo e a funcionalidade do relógio! Divirta-se codificando! ⏰
