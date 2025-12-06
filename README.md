# Finanças PRO

Projeto de gestão financeira pessoal desenvolvido em HTML, CSS e JavaScript. O repositório contém duas versões do aplicativo, cada uma com diferentes níveis de funcionalidades e complexidade.

## 📁 Versões do Projeto

### 1. Finanças PRO (index.html) - Versão Básica

A versão inicial do projeto, focada em simplicidade e facilidade de uso.

**Características:**
- Interface minimalista e intuitiva
- Controle básico de entradas e saídas
- Tabela de transações com edição e exclusão
- Cálculo automático de totais (entradas, saídas e saldo)
- Design responsivo com Bootstrap

**Funcionalidades:**
- Adicionar transações (entradas e saídas)
- Editar transações existentes
- Excluir transações
- Visualização de resumo financeiro em tempo real

**Tecnologias:**
- HTML5
- CSS3 (estilos personalizados + Bootstrap 5.3.0)
- JavaScript (jQuery 3.6.0)
- Bootstrap 5.3.0

### 2. Finanças PRO V2 (financas-pro-v2.html) - Versão Completa

Versão avançada com recursos adicionais para uma gestão financeira mais completa e profissional.

**Características:**
- Interface moderna com gradientes e animações
- Sistema completo de categorias personalizáveis
- Gráficos interativos para análise visual
- Sistema de metas mensais de economia
- Filtros avançados (período, categoria, tipo)
- Persistência de dados com localStorage
- Exportação de dados em JSON

**Funcionalidades:**

#### 📋 Transações
- Adicionar, editar e excluir transações
- Categorização automática
- Filtros por período, categoria e tipo
- Visualização em tabela ordenada por data

#### 📊 Gráficos
- Gráfico de pizza (Entradas vs Saídas)
- Gráfico de categorias (distribuição de gastos)
- Gráfico de tendência temporal

#### 🏷️ Categorias
- Criar categorias personalizadas
- Definir cores para cada categoria
- Gerenciar categorias existentes
- Categorias pré-configuradas: Salário, Alimentação, Transporte, Lazer, Saúde, Educação

#### 🎯 Metas
- Definir metas mensais de economia
- Acompanhamento de progresso com barra visual
- Histórico de metas

#### 💾 Dados
- Persistência automática no navegador (localStorage)
- Exportação de backup em JSON
- Opção de limpar todos os dados

**Tecnologias:**
- HTML5
- CSS3 (design moderno com gradientes e animações)
- JavaScript (jQuery 3.6.0)
- Bootstrap 5.3.0
- Chart.js (gráficos interativos)

## 🚀 Como Usar

### Versão Básica (index.html)

1. Clone o repositório ou baixe o arquivo `index.html`.
2. Abra o arquivo `index.html` em seu navegador.
3. Ou acesse o [link](https://douglasbarcellos.github.io/financaspro/) para testar.

**Adicionar uma Nova Transação:**
1. Clique no botão "Nova Transação".
2. Preencha os campos:
   - Descrição: Uma breve descrição da transação
   - Valor: O valor da transação (use sinal negativo para despesas)
   - Data: A data da transação
3. Clique em "Salvar".

**Editar/Excluir:**
- Use os botões "Editar" ou "Excluir" na tabela de transações.

### Versão Completa (financas-pro-v2.html)

1. Abra o arquivo `financas-pro-v2.html` em seu navegador.
2. Os dados são salvos automaticamente no navegador.

**Fluxo de Uso:**
1. **Configurar Categorias** (opcional): Acesse a aba "Categorias" para personalizar.
2. **Adicionar Transações**: Clique em "+ Nova Transação" e preencha os dados.
3. **Visualizar Gráficos**: Acesse a aba "Gráficos" para análises visuais.
4. **Definir Metas**: Na aba "Metas", configure suas metas mensais.
5. **Filtrar Dados**: Use os filtros na parte superior para visualizações específicas.
6. **Exportar Backup**: Use o botão "📊 Exportar" para fazer backup dos dados.

## 📊 Comparação das Versões

| Funcionalidade | Versão Básica | Versão V2 |
|----------------|---------------|-----------|
| Adicionar/Editar/Excluir Transações | ✅ | ✅ |
| Categorias | ❌ | ✅ |
| Gráficos | ❌ | ✅ |
| Filtros | ❌ | ✅ |
| Metas Mensais | ❌ | ✅ |
| Persistência (localStorage) | ❌ | ✅ |
| Exportação de Dados | ❌ | ✅ |
| Design Moderno | ⚠️ Básico | ✅ Avançado |

## 🔧 Detalhes de Implementação

### HTML
- Estrutura semântica HTML5
- Componentes Bootstrap para layout responsivo
- Modais para formulários
- Sistema de tabs (V2)

### CSS
- Estilos personalizados
- Gradientes e animações (V2)
- Design responsivo
- Paleta de cores consistente

### JavaScript/jQuery
- Gerenciamento de estado com arrays
- Manipulação do DOM com jQuery
- Cálculos automáticos de totais
- Validação de formulários
- Integração com Chart.js (V2)
- Persistência com localStorage (V2)

## 🎯 Melhorias Futuras

### Para ambas as versões:
- Autenticação de usuários para múltiplas contas
- Sincronização em nuvem
- Relatórios em PDF
- Notificações e lembretes
- Suporte a múltiplas moedas
- Modo escuro/claro

### Específicas para V2:
- Gráficos de tendência temporal mais detalhados
- Comparação entre períodos
- Orçamento por categoria
- Alertas de gastos excessivos
- Importação de dados de planilhas

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para fazer um fork do projeto, criar uma branch, commit suas alterações e abrir um Pull Request.

## Licença

Este projeto está sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.

## Autor

BArcellos ↟

---

© 2025 BArcellos ↟ - Todos os direitos reservados.