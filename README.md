# Layout Responsivo em React Native

Esse projeto é um exemplo de como montar uma tela simples no **React Native**.  
A tela foi dividida em 3 partes:

- **Cabeçalho** (em azul claro)
- **Conteúdo principal** (em branco)
- **Rodapé** (em cinza claro)

---

## Como o código funciona

O componente `LayoutResponsivo` tem uma estrutura básica de `View`:


<img width="1124" height="863" alt="image" src="https://github.com/user-attachments/assets/be81802f-c9c0-4410-9179-3d309f346c52" />

A View principal (container) ocupa a tela inteira.

Dentro dela, temos três partes: header, content e footer.

Cada parte tem uma cor diferente e o texto fica centralizado.

**Flexbox**:

flex determina quanto espaço cada parte ocupa.

justifyContent centraliza verticalmente.

alignItems centraliza horizontalmente.

## Como funciona o estilo

Foi criado um objeto chamado styles onde coloca todos os estilos que queremos usar. Cada estilo recebe um nome e suas propriedades, cor, tamanho de fonte, espaçamento etc. Depois, aplicamos esses estilos nos componentes usando style={styles.nomeDoEstilo}. 

Resultado: 


![Imagem do WhatsApp de 2025-09-10 à(s) 21 03 28_d1500635](https://github.com/user-attachments/assets/f17bea25-52f9-4209-b61e-0c9aa413407a)
