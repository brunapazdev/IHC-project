# Avaliação Heurística

# Heurísticas de Nielsen

| Nº | Heurística | Descrição |
|---|---|---|
| 1 | Visibilidade do status do sistema | O sistema deve manter o usuário informado sobre o que está acontecendo |
| 2 | Compatibilidade entre sistema e mundo real | A interface deve utilizar linguagem familiar ao usuário |
| 3 | Controle e liberdade do usuário | O usuário deve conseguir desfazer ações facilmente |
| 4 | Consistência e padrões | Elementos semelhantes devem manter comportamento consistente |
| 5 | Prevenção de erros | O sistema deve evitar erros antes que aconteçam |
| 6 | Reconhecimento em vez de memorização | O usuário não deve precisar memorizar informações |
| 7 | Flexibilidade e eficiência de uso | A interface deve atender usuários iniciantes e avançados |
| 8 | Estética e design minimalista | A interface deve evitar excesso de informação |
| 9 | Ajudar usuários a reconhecer e recuperar erros | O sistema deve explicar erros claramente |
| 10 | Ajuda e documentação | O sistema deve oferecer suporte e orientação |

---

# Avaliação da Interface

## 1. Visibilidade do Status do Sistema

| Aspecto Avaliado | Resultado |
|---|---|
| Carregamento de gráficos | O sistema apresenta feedback visual durante carregamentos |
| Aplicação de filtros | O usuário consegue perceber quando os dados foram atualizados |
| Navegação | A interface informa claramente em qual área o usuário está |

### Problemas identificados
- Possível demora no carregamento de gráficos grandes sem indicação detalhada de progresso.

### Recomendações
- Adicionar indicadores de carregamento mais claros.
- Exibir mensagens de atualização dos dados.

---

## 2. Compatibilidade entre Sistema e Mundo Real

| Aspecto Avaliado | Resultado |
|---|---|
| Linguagem utilizada | Termos relacionados a sustentabilidade e cloud computing são compreensíveis |
| Organização das informações | Dados apresentados em formato visual familiar |
| Gráficos e indicadores | Facilita entendimento mesmo para usuários não técnicos |

### Problemas identificados
- Alguns termos técnicos podem gerar dúvidas para usuários iniciantes.

### Recomendações
- Adicionar descrições simples e tooltips explicativos.
- Utilizar linguagem mais acessível em alguns indicadores.

---

## 3. Controle e Liberdade do Usuário

| Aspecto Avaliado | Resultado |
|---|---|
| Aplicação de filtros | Usuário consegue alterar filtros facilmente |
| Navegação | Usuário pode retornar às telas anteriores |
| Comparações | Usuário pode modificar comparações sem reiniciar fluxo |

### Problemas identificados
- Falta de botão claro para redefinir filtros.

### Recomendações
- Adicionar opção “Limpar filtros”.
- Melhorar navegação entre dashboards.

---

## 4. Consistência e Padrões

| Aspecto Avaliado | Resultado |
|---|---|
| Componentes visuais | Elementos seguem padrão visual consistente |
| Ícones e cores | Mantêm significado semelhante em toda interface |
| Navegação | Estrutura semelhante entre telas |

### Problemas identificados
- Alguns gráficos podem apresentar estilos diferentes.

### Recomendações
- Padronizar componentes visuais.
- Definir guia visual da aplicação.

---

## 5. Prevenção de Erros

| Aspecto Avaliado | Resultado |
|---|---|
| Filtros inválidos | Sistema impede seleções incorretas |
| Campos obrigatórios | Interface valida entradas antes da ação |
| Comparações | Sistema evita comparações incompletas |

### Problemas identificados
- Possibilidade de selecionar períodos sem dados disponíveis.

### Recomendações
- Validar disponibilidade de dados antes da seleção.
- Informar ao usuário quando não houver dados.

---

## 6. Reconhecimento em vez de Memorização

| Aspecto Avaliado | Resultado |
|---|---|
| Navegação | Informações importantes ficam visíveis |
| Indicadores | Elementos possuem identificação clara |
| Uso de filtros | Usuário consegue reconhecer opções rapidamente |

### Problemas identificados
- Alguns indicadores ambientais podem não ser autoexplicativos.

### Recomendações
- Adicionar legendas e explicações contextuais.
- Utilizar descrições visuais mais claras.

---

## 7. Flexibilidade e Eficiência de Uso

| Aspecto Avaliado | Resultado |
|---|---|
| Usuários iniciantes | Interface simples facilita aprendizado |
| Usuários avançados | Possibilidade de análises mais detalhadas |
| Interatividade | Filtros e comparações tornam análise mais eficiente |

### Problemas identificados
- Usuários avançados podem precisar de filtros mais específicos.

### Recomendações
- Adicionar filtros avançados.
- Permitir exportação de dados.

---

## 8. Estética e Design Minimalista

| Aspecto Avaliado | Resultado |
|---|---|
| Organização visual | Interface limpa e organizada |
| Quantidade de informação | Dados apresentados de forma objetiva |
| Uso de cores | Auxilia interpretação visual |

### Problemas identificados
- Excesso de gráficos em uma única tela pode causar sobrecarga visual.

### Recomendações
- Separar indicadores em categorias.
- Reduzir excesso de elementos simultâneos.

---

## 9. Reconhecimento e Recuperação de Erros

| Aspecto Avaliado | Resultado |
|---|---|
| Mensagens de erro | Sistema informa problemas encontrados |
| Recuperação | Usuário consegue corrigir ações facilmente |
| Feedback | Interface orienta o usuário após erros |

### Problemas identificados
- Algumas mensagens podem ser muito técnicas.

### Recomendações
- Utilizar mensagens mais claras e objetivas.
- Explicar como resolver o erro.

---

## 10. Ajuda e Documentação

| Aspecto Avaliado | Resultado |
|---|---|
| Ajuda contextual | Sistema pode apresentar explicações rápidas |
| Documentação | Usuário pode acessar informações adicionais |
| Orientação | Interface auxilia navegação inicial |

### Problemas identificados
- Falta de tutorial inicial para novos usuários.

### Recomendações
- Adicionar onboarding simples.
- Criar seção de ajuda e FAQ.

---

# Consolidação dos Problemas Encontrados

| Heurística | Problema Principal | Severidade |
|---|---|---|
| Visibilidade do status do sistema | Falta de feedback detalhado em carregamentos | Média |
| Compatibilidade com mundo real | Termos técnicos complexos | Média |
| Controle e liberdade do usuário | Ausência de limpar filtros | Baixa |
| Consistência e padrões | Diferença visual entre gráficos | Baixa |
| Prevenção de erros | Seleção de períodos sem dados | Média |
| Reconhecimento em vez de memorização | Indicadores pouco intuitivos | Média |
| Flexibilidade e eficiência | Poucos filtros avançados | Baixa |
| Estética e design minimalista | Excesso de informação em algumas telas | Média |
| Recuperação de erros | Mensagens técnicas demais | Média |
| Ajuda e documentação | Ausência de tutorial inicial | Baixa |
