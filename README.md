# Projeto GAMA - Simulação Multiagente da COVID-19

Projeto GAMA para simulação multiagente da COVID-19.

## Sobre

Este projeto utiliza a plataforma GAMA (GIS Agent-based Modeling Architecture) para criar simulações multiagente relacionadas à propagação e dinâmica da COVID-19.

## Objetivo

Desenvolver modelos de simulação que ajudem a entender:
- Dinâmica de transmissão da COVID-19
- Efeitos de medidas de distanciamento social
- Impacto de políticas de saúde pública
- Comportamento de agentes (indivíduos) em diferentes cenários

## Como Usar

### Pré-requisitos
- [GAMA Platform](https://gama-platform.github.io/) instalado
- Java 8 ou superior
- Conhecimento básico de modelagem multiagente

### Instalação

```bash
# Clonar o repositório
git clone https://github.com/ThiagoMarques/gama.git

# Abrir o projeto no GAMA Platform
# File > Open Project > Selecionar pasta do projeto
```

### Execução

1. Abrir o GAMA Platform
2. Importar o projeto
3. Executar a simulação através da interface gráfica
4. Analisar os resultados

## Estrutura do Projeto

```
gama/
├── models/           # Modelos de simulação
├── data/            # Dados utilizados
├── images/          # Imagens e recursos
├── README.md
└── ...
```

## Tecnologias Utilizadas

- **GAMA Platform**: Plataforma de modelagem e simulação multiagente
- **GAML**: Linguagem de modelagem do GAMA
- **Java**: Base da plataforma GAMA

## Características da Simulação

### Agentes
- **Indivíduos**: Representam pessoas na população
- **Ambiente**: Espaço geográfico ou abstrato
- **Instituições**: Hospitais, escolas, locais de trabalho

### Parâmetros Configuráveis
- Taxa de transmissão
- Período de incubação
- Taxa de recuperação
- Medidas de distanciamento
- Capacidade hospitalar

## Sobre Modelagem Multiagente

A modelagem multiagente permite simular sistemas complexos através de:
- **Agentes autônomos**: Comportamento individual
- **Interações**: Entre agentes e ambiente
- **Emergência**: Propriedades que surgem das interações
- **Espaço**: Representação geográfica ou abstrata

## Aplicações

Este tipo de simulação é útil para:
- Planejamento de políticas de saúde pública
- Análise de cenários epidemiológicos
- Educação e conscientização
- Pesquisa acadêmica

## Recursos de Aprendizado

- [Documentação GAMA](https://gama-platform.github.io/wiki/)
- [Tutoriais GAMA](https://gama-platform.github.io/wiki/Tutorials)
- [Exemplos de Modelos](https://github.com/gama-platform/gama/wiki/Models)

## Contribuindo

Contribuições são bem-vindas! Áreas de interesse:
- Melhorias nos modelos
- Novos cenários de simulação
- Documentação
- Otimização de performance

## Licença

Este projeto é de código aberto e está disponível para fins educacionais e de pesquisa.

## Aviso

Este é um modelo de simulação educacional. Não deve ser usado como única fonte para decisões de saúde pública. Sempre consulte especialistas e dados oficiais.

## Links Úteis

- [GAMA Platform](https://gama-platform.github.io/)
- [Documentação GAMA](https://gama-platform.github.io/wiki/)
- [WHO - COVID-19](https://www.who.int/emergencies/diseases/novel-coronavirus-2019)

---

**Autor**: Thiago Marques  
**Plataforma**: GAMA  
**Aplicação**: Simulação Multiagente da COVID-19
