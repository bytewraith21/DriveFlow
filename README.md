# DriveFlow — Gestão Financeira para Motoristas Autônomos

> **Projeto Integrador** — Disciplina de Design Profissional para Análise e Desenvolvimento de Sistemas.  
> **Curso:** Análise e Desenvolvimento de Sistemas — Universidade Positivo (2026)  
> **Docente:** Prof. Sedenilso Antonio Machado  
> **Desenvolvedor / Responsável:** José Ricardo Bordoni Soares  
> **Empresa:** DriveFlow  
> **Repositório:** [github.com/bytewraith21/DriveFlow.git](https://github.com/bytewraith21/DriveFlow.git)

---

## - Sobre o Projeto

O **DriveFlow** é um web app simples e direto feito para motoristas de aplicativo (Uber, 99 e particulares) acompanharem seus ganhos e gastos do dia a dia sem complicação.

O objetivo principal é acabar com a famosa **ilusão do faturamento bruto**: no final do dia o app mostra um valor alto (ex: R$ 380,00), mas o motorista não sabe ao certo quanto sobrou de verdade depois de tirar combustível, manutenção, alimentação, aluguel do carro ou a depreciação do veículo.

---

## - Contexto e Mercado

O projeto foi estruturado com base na pesquisa de mercado do Prof. Sedenilso Machado (feita com mais de 40 mil pessoas):

- **Sem enrolação:** Planilhas complexas ou sistemas cheios de etapas têm mais de **78% de abandono em 30 dias**. Quem tá na rua precisa de agilidade.
- **Demanda alta:** A categoria de **Gestão Financeira para Motoristas de App** foi a mais pedida da pesquisa, liderando com **92% de interesse**.
- **Foco no que importa:** Exibir direto na tela o **Saldo Líquido**, o **Custo por KM** e a **Meta Diária**.

---

## - O que o sistema faz

- **Painel Geral:** Mostra Receitas, Despesas, Saldo Líquido e Custo por KM em tempo real.
- **Lançamento Rápido:** Formulário enxuto para cadastrar entradas e saídas (tipo, valor, km, categoria e descrição).
- **Meta do Dia:** Barra visual que calcula o progresso em relação à meta configurada.
- **Salva no Navegador:** Usa `localStorage`, então os dados ficam gravados no próprio celular/computador sem precisar criar conta ou fazer login.
- **Exportação CSV:** Opção para baixar os registros em formato de planilha para controle pessoal.
- **Responsivo:** Interface limpa e adaptada para telas de celulares.

---

## - Tecnologias

Desenvolvido sem dependência de servidores pesados ou bancos de dados relacionais:

- **HTML5:** Estrutura das telas.
- **CSS3:** Visual limpo, responsivo e de fácil leitura.
- **JavaScript (Vanilla ES6+):** Cálculos, manipulação de dados e regras do sistema.
- **localStorage:** Armazenamento local direto no navegador do usuário.

---

## - Como Rodar


1. **Clone o repositório:**
   ```bash
   git clone https://github.com/bytewraith21/DriveFlow.git
   ```
2. **Entre na pasta:**
   ```bash
   cd DriveFlow
   ```
3. **Execute:**
   Dê dois cliques no arquivo `index.html` e o sistema abre rodando direto no seu navegador.

---

## - Arquivos do Repositório

```text
DriveFlow/
├── index.html                    # Interface, visual e lógica do sistema                 
├── relatorio_projeto_integrador.html # Relatório técnico do trabalho
├── logo_rodacerta.svg            # Logo e identidade gráfica
└── README.md                     # Documentação oficial
```

---

## - Pesquisa com Motoristas (Fase 1)

Conversando com quem roda no dia a dia, definimos dois perfis principais para guiar o sistema:

1. **Cleber (38 anos) — Rodando em carro próprio:**  
   *Necessidade:* Parar no posto, lançar o abastecimento/km e saber na hora se o dia deu lucro real ou se só pagou gasolina e desgaste do carro.
2. **Lucas (26 anos) — Carro alugado:**  
   *Necessidade:* Ver a barra da meta ficar verde para saber que já cobriu o custo diário do aluguel do veículo e combustível.

---

## - Créditos

Trabalho desenvolvido por **José Ricardo Bordoni Soares** para o curso de **Análise e Desenvolvimento de Sistemas** da **Universidade Positivo (2026)**, na disciplina de *Design Profissional* do **Prof. Sedenilso Antonio Machado**.

**Empresa do Projeto:** DriveFlow  
**Desenvolvedor:** José Ricardo Bordoni Soares
