# Mapa de Objetivos

> O mapa de objetivos representa os principais objetivos dos usuários ao interagir com o sistema, organizando-os de forma hierárquica e facilitando a compreensão das necessidades apoiadas pela aplicação.

---

## Mapa de Objetivos — Persona Ana (Estudante)

### Objetivo Principal

```text
Compreender os impactos ambientais da computação em nuvem
```

### Estrutura Hierárquica

```text
Compreender os impactos ambientais da computação em nuvem

├── Visualizar indicadores ambientais
│   ├── Consumo de energia
│   ├── Emissão de CO₂
│   └── Uso de água
│
├── Filtrar informações
│   ├── Selecionar período
│   └── Aplicar filtros
│
├── Comparar provedores cloud
│   ├── AWS
│   ├── Google Cloud
│   └── Microsoft Azure
│
└── Interpretar dados
    ├── Analisar gráficos
    └── Identificar tendências
```

---

## Mapa de Objetivos — Persona Mariana (Analista de Sustentabilidade)

### Objetivo Principal

```text
Analisar dados ambientais para tomada de decisão
```

### Estrutura Hierárquica

```text
Analisar dados ambientais para tomada de decisão

├── Consultar indicadores ambientais
│   ├── Energia
│   ├── Carbono
│   └── Água
│
├── Comparar desempenho ambiental
│   ├── Comparar provedores
│   ├── Comparar períodos
│   └── Identificar impactos
│
├── Gerar análises
│   ├── Identificar tendências
│   ├── Interpretar dados históricos
│   └── Apoiar decisões
│
└── Otimizar tempo de análise
    ├── Centralizar informações
    └── Facilitar visualização
```

---

## Mapa de Objetivos — Persona Pesquisador

### Objetivo Principal

```text
Realizar pesquisas sobre sustentabilidade em cloud computing
```

### Estrutura Hierárquica

```text
Realizar pesquisas sobre sustentabilidade em cloud computing

├── Obter dados confiáveis
│   ├── Consultar indicadores
│   ├── Comparar dados históricos
│   └── Validar informações
│
├── Explorar impactos ambientais
│   ├── Energia
│   ├── Água
│   └── Emissões
│
├── Produzir análises acadêmicas
│   ├── Interpretar tendências
│   ├── Comparar provedores
│   └── Gerar conclusões
│
└── Facilitar pesquisas
    ├── Navegação intuitiva
    └── Dados centralizados
```

---

# Diagrama de Consolidação

## Objetivo Consolidado do Sistema

```text
Facilitar a compreensão e análise dos impactos ambientais da computação em nuvem

├── Visualizar indicadores ambientais
│   ├── Consumo de energia
│   ├── Emissão de CO₂
│   └── Uso de água
│
├── Filtrar e comparar dados
│   ├── Comparar provedores
│   ├── Comparar períodos
│   └── Identificar tendências
│
├── Apoiar tomada de decisão
│   ├── Interpretar gráficos
│   ├── Produzir análises
│   └── Gerar conhecimento
│
└── Melhorar experiência do usuário
    ├── Navegação intuitiva
    ├── Dados centralizados
    └── Visualização interativa
```

---

# Esquema Conceitual de Signos

> O esquema conceitual de signos representa os principais elementos de comunicação da interface, considerando conteúdo, restrições, prevenção e recuperação de rupturas comunicativas.

---

## Esquema Conceitual Consolidado

| signo | origem | observações | tipo de conteúdo | restrição sobre o conteúdo | valor default | prevenção | recuperação |
| :---- | :---- | :---- | :---- | :---- | :---- | :---- | :---- |
| indicador ambiental | domínio | representa os indicadores ambientais | texto | não pode ser nulo | — | PP: campo obrigatório | RA |
| gráfico | interface | utilizado para análise visual | visual | deve possuir dados válidos | gráfico padrão | PP+PA: impedir renderização sem dados | RM |
| filtro de período | domínio | utilizado para análise temporal | número/data | intervalo válido | todos os anos | PP: validar intervalo | RA |
| provedor cloud | domínio | utilizado em comparações | texto | não pode ser vazio | AWS | PA: ao menos uma opção selecionada | RA |
| emissão de CO₂ | domínio | indicador ambiental | número | valor positivo | 0 | PP: validação numérica | RM |
| consumo de energia | domínio | indicador ambiental | número | valor positivo | 0 | PP: validação numérica | RM |
| uso de água | domínio | indicador ambiental | número | valor positivo | 0 | PP: validação numérica | RM |
| dashboard | interface | principal área da aplicação | visual | deve carregar corretamente | tela inicial | PP: loading e tratamento de erro | RM |
| comparação de provedores | aplicação | permite análise comparativa | seleção | deve possuir ao menos dois provedores | comparação padrão | PA: impedir comparação inválida | RA |
| tendência histórica | domínio | análise temporal | gráfico temporal | requer período selecionado | últimos 5 anos | PP: seleção automática de período | RM |
| usuário | domínio | representa usuário do sistema | texto | nome válido | visitante | PP: autenticação opcional | CE |
| pesquisa | aplicação | busca de indicadores | texto | mínimo de caracteres | vazio | PP: impedir busca vazia | RA |

---

## Legenda

| Sigla | Significado |
| :---- | :---- |
| PP | Prevenção Passiva |
| PA | Prevenção Ativa |
| AL | Alerta |
| RA | Recuperação Apoiada |
| RM | Recuperação Manual |
| CE | Captura de Erro |
