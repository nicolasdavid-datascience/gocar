# 📊 Controle de Combustível para Motoristas de Uber

Um aplicativo web completo para ajudar motoristas de Uber a controlar seus gastos com combustível, faturamento e calcular métricas importantes para melhorar sua rentabilidade.

## ✨ Funcionalidades

- **Registro de abastecimentos** com data, tipo de combustível, valor por litro e valor total
- **Cálculo automático** de litros abastecidos, lucro bruto e médias (R$/KM e R$/Litro)
- **Visualização de dados** em gráficos e relatórios consolidados
- **Modo escuro/claro** com preferência salva
- **Totalmente responsivo** - funciona bem em dispositivos móveis
- **Persistência de dados** - os registros são salvos localmente no navegador
- **Edição e exclusão** de registros existentes

## 📊 Métricas Calculadas

- Litros abastecidos
- Lucro bruto (faturamento - gastos com combustível)
- Média de R$ por KM rodado
- Média de R$ por litro de combustível
- Percentual de lucro bruto sobre faturamento

## 🛠️ Tecnologias Utilizadas

- HTML5
- CSS3 (com variáveis para temas)
- JavaScript Vanilla
- Chart.js (para visualização de gráficos)
- LocalStorage (para persistência de dados)

## 🚀 Como Usar

1. Acesse o aplicativo no navegador (não requer instalação)
2. Preencha os dados do abastecimento:
   - Data
   - Tipo de combustível (etanol/gasolina)
   - Valor do litro
   - Valor total abastecido
3. Opcionalmente, ative o toggle "Inserir Faturamento + KM" para adicionar:
   - Faturamento do dia
   - Quilometragem rodada
4. Clique em "Registrar" para salvar
5. Navegue para a aba "Relatório" para ver gráficos e sumários

## 📱 Responsividade

O aplicativo foi projetado para funcionar bem em:
- Desktop (telas maiores)
- Tablets
- Smartphones (com layout adaptado)

## 🎨 Temas

- **Modo Claro** (padrão)
- **Modo Escuro** (menos cansativo para os olhos à noite)

Alternar entre temas pelo botão no canto superior direito.

## 💾 Armazenamento de Dados

Todos os dados são salvos localmente no navegador usando localStorage, o que significa que:
- Os dados persistem mesmo após fechar o navegador
- Os dados são específicos para cada dispositivo/navegador
- Não há sincronização entre dispositivos

## ⚠️ Limitações

- Os dados não são sincronizados na nuvem
- Não há backup automático
- Funciona apenas em um único navegador/dispositivo

## 📜 Licença

Este projeto é open-source e está disponível para uso livre.

## ✉️ Contato

Para dúvidas ou sugestões, entre em contato com o desenvolvedor.

---

Desenvolvido com ❤️ para ajudar motoristas de Uber a gerenciarem melhor seus negócios!
