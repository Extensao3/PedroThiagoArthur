# 🌿 Fiel Patrocínio

> **Plataforma de fidelidade coletiva para o comércio local de Patrocínio — MG**

Desenvolvido por estudantes locais como projeto de extensão universitária, o **Fiel Patrocínio** é um sistema de fidelidade unificado que conecta clientes e estabelecimentos comerciais da cidade em uma única rede de pontos compartilhada.

---

## 📌 Sobre o Projeto

O comércio local de Patrocínio compete diariamente com shoppings de Uberlândia, marketplaces online e grandes redes varejistas. O pequeno lojista, sem estrutura e sem dados, não consegue reagir — cartõezinhos de papel se perdem, planilhas ficam desatualizadas e aplicativos de uma única loja não têm apelo suficiente para o cliente instalar.

O **Fiel Patrocínio** resolve isso com um ecossistema digital onde:

- O **cliente** baixa um único app, cadastra-se uma vez e acumula pontos em qualquer estabelecimento parceiro da rede — resgatando onde quiser, sem restrições.
- O **lojista** acessa um painel web completo para configurar campanhas, acompanhar o comportamento dos clientes e tomar decisões baseadas em dados reais.

---

## 🗂️ Estrutura do Projeto

```
fiel-patrocinio/
├── index.html           # Landing page institucional (site principal)
├── app.html             # Simulação do app mobile do cliente
├── painel-lojista.html  # Painel web do lojista (dashboard)
├── proposta_fiel_patrocinio_v3.pdf   # Proposta acadêmica completa
└── fiel_patrocinio.pptx              # Apresentação do projeto
```

---

## ✨ Funcionalidades

### Para o Cliente (app.html)
- Carteira de pontos unificada, válida em toda a rede parceira
- Escaneio de QR Code exclusivo por estabelecimento para registrar compras
- Histórico de transações e extrato de pontos
- Resgate de prêmios e descontos em qualquer loja parceira
- Notificações push personalizadas com ofertas e promoções

### Para o Lojista (painel-lojista.html)
- Dashboard com métricas em tempo real: clientes ativos, taxa de retorno, ticket médio e pontos distribuídos
- QR Code exclusivo por estabelecimento para registro de compras no balcão
- Criação de campanhas sazonais e promoções segmentadas
- Campanhas automáticas por comportamento (ex: cliente sem visitar há 30 dias recebe cupom automaticamente)
- Relatórios avançados com segmentação de clientes e mapa de horários de pico
- Integração com WhatsApp para disparo de notificações (plano Pro)

### Landing Page (index.html)
- Apresentação institucional da plataforma
- Seção de funcionalidades e diferenciais
- Página de planos e preços (Fiel Plus e planos para lojistas)
- Seção "Como funciona" em 4 passos
- Depoimentos de clientes e lojistas

---

## 💰 Modelo de Negócio

### Para Consumidores — Fiel Plus
O app é gratuito. O plano **Fiel Plus** (R$ 14,90/mês) oferece:
- Pontos em dobro em toda a rede
- Cupons exclusivos toda semana
- Acesso antecipado a promoções relâmpago
- Relatório mensal de gastos
- Badge exclusivo de cliente Fiel Plus

### Para Lojistas — Dois Planos

| | Essencial | Pro |
|---|---|---|
| **Preço** | R$ 49,90/mês | R$ 197,00/mês |
| Acesso à rede de clientes | ✅ | ✅ |
| Painel de gestão | ✅ | ✅ |
| Relatórios de frequência e ticket médio | ✅ | ✅ |
| Campanhas manuais | ✅ | ✅ |
| Suporte por e-mail | ✅ | ✅ |
| Relatórios avançados com segmentação | ❌ | ✅ |
| Mapa de horários de pico | ❌ | ✅ |
| Campanhas automáticas por comportamento | ❌ | ✅ |
| Destaque no app para clientes próximos | ❌ | ✅ |
| Integração com WhatsApp | ❌ | ✅ |

---

## 🛠️ Stack Tecnológica

| Camada | Tecnologia |
|---|---|
| **Front-end web** | HTML5, CSS3, JavaScript (vanilla) |
| **App mobile** | React Native *(planejado)* |
| **Back-end** | Node.js *(planejado)* |
| **Banco de dados** | PostgreSQL *(planejado)* |
| **Tipografia** | Syne + DM Sans (Google Fonts) |
| **Infraestrutura** | Nuvem (estimativa: R$ 200–400/mês) |

As telas em HTML/CSS/JS presentes neste repositório representam os **protótipos de alta fidelidade** das interfaces do sistema — landing page, app do cliente e painel do lojista.

---

## 🚀 Como Rodar Localmente

Nenhuma dependência ou build necessário. Basta abrir os arquivos HTML diretamente no navegador:

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/fiel-patrocinio.git
cd fiel-patrocinio

# Abra o site principal
open index.html

# Abra o app do cliente
open app.html

# Abra o painel do lojista
open painel-lojista.html
```

Ou simplesmente arraste qualquer arquivo `.html` para o navegador.

---

## 📊 Projeção Financeira (Cenário Conservador)

| Fonte | Qtd. | Receita/mês |
|---|---|---|
| Lojistas — Plano Essencial | 30 | R$ 1.497,00 |
| Lojistas — Plano Pro | 10 | R$ 1.970,00 |
| Assinantes Fiel Plus | 200 | R$ 2.980,00 |
| **Total** | | **≈ R$ 6.447,00/mês** |

---

## 🌍 Impacto Esperado

- Clientes que acumulam pontos em Patrocínio têm motivo concreto para comprar na cidade, reduzindo a evasão para Uberlândia e e-commerces
- Lojistas tomam decisões baseadas em dados reais, não em intuição
- Programas de fidelidade bem implementados aumentam em até **30% a frequência de retorno** e elevam o ticket médio em até **20%** (SEBRAE)
- O projeto é desenvolvido por estudantes da própria cidade, criando legado tecnológico local

---

## 👥 Equipe

| Nome | Papel |
|---|---|
| Tiago Souza de Castro | Desenvolvimento |
| Arthur Xavier | Desenvolvimento |
| Pedro Henrique Lopes | Desenvolvimento |

Projeto desenvolvido para a disciplina de **Extensão III — 01/2026**.

---

## 📄 Licença

Este projeto é de caráter acadêmico e educacional. Todos os direitos reservados aos autores.

---

<div align="center">
  Feito com ❤️ em Patrocínio — MG · © 2026 Fiel Patrocínio
</div>
