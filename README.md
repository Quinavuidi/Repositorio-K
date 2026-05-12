# Repositorio-K
# 📚 Biblioteca-Kiaxi

> Sistema de Gestão de Biblioteca para a cadeira de Prática Profissional e Projeto em CC  
> **CreatSQ - Soluções em Software, LDA** | Autor: Quinavuidi Prepotente

![Status](https://img.shields.io/badge/Status-Em%20Desenvolvimento-yellow)
![Licença](https://img.shields.io/badge/Licença-MIT-blue)
![Versão](https://img.shields.io/badge/Versão-1.0.0-brightgreen)

---

### **📌 Sobre o Projeto**

O **Biblioteca-Kiaxi** é um sistema web/desktop desenvolvido para automatizar e modernizar o controle de acervo, empréstimos e utentes de bibliotecas escolares e comunitárias do município de Kiaxi, Luanda.

O projeto nasceu da observação prática: muitas bibliotecas ainda usam cadernos e fichas manuais, causando perda de livros, demora no atendimento e falta de relatórios de uso do acervo. O Kiaxi resolve isso com uma interface simples, rápida e que funciona offline.

**Nome "Kiaxi"**: Homenagem ao município de Luanda onde o projeto será implantado como piloto.

### **🎯 Objetivos**

**Objetivo Geral**  
Desenvolver um sistema que digitalize todo o fluxo de uma biblioteca: cadastro de livros, utentes, empréstimos, devoluções e relatórios gerenciais.

**Objetivos Específicos**
1. **Eliminar o papel**: Substituir 100% das fichas manuais por registro digital
2. **Reduzir perdas**: Alertar sobre livros com devolução em atraso automaticamente
3. **Agilizar atendimento**: Localizar e emprestar um livro em menos de 30 segundos
4. **Gerar dados**: Criar relatórios de livros mais lidos, utentes ativos e acervo por categoria
5. **Incluir a comunidade**: Interface em português, leve, que roda em PCs antigos das escolas

### **⚙️ Funcionalidades Principais**

| **Módulo** | **O que faz** |
| --- | --- |
| **1. Acervo** | Cadastro de livros com ISBN, título, autor, editora, ano, categoria, quantidade e capa. Busca instantânea por título/autor. |
| **2. Utentes** | Cadastro de alunos/professores com foto, BI, turma, contato. Carteirinha digital com QR Code. |
| **3. Empréstimos** | Registra saída do livro, calcula data de devolução automática, imprime comprovante. Bloqueia utente com pendência. |
| **4. Devoluções** | Dá baixa com 1 clique, calcula multa por atraso se configurado, libera utente. |
| **5. Relatórios** | Livros mais emprestados, ranking de leitores, acervo por categoria, lista de devoluções em atraso. Exporta PDF/Excel. |
| **6. Dashboard** | Total de livros, empréstimos ativos, devoluções hoje, gráfico de uso mensal. |

### **🛠️ Tecnologias Utilizadas**

**Nota**: Ajusta conforme sua stack real. Deixei um exemplo Full-Stack moderno.

**Front-End:**
- **React.js** + Vite - Interface rápida e componentizada
- **TailwindCSS** - Estilização ágil e responsiva
- **Axios** - Consumo de API
- **React-Icons** - Iconografia

**Back-End:**
- **Node.js** + Express - API REST robusta
- **Prisma ORM** - Comunicação segura com banco
- **JWT** - Autenticação de bibliotecários

**Banco de Dados:**
- **PostgreSQL** - Dados relacionais consistentes
- **SQLite** - Opção para versão offline em escolas sem servidor

**Outros:**
- **Git + GitHub** - Versionamento
- **Docker** - Facilitar deploy na escola piloto
- **Jest** - Testes unitários

### **🚀 Como Acessar/Rodar o Projeto**

**Pré-requisitos**
- Node.js v18+ instalado
- PostgreSQL instalado ou Docker
- Git

**1. Clone o repositório**
```bash
git clone https://github.com/seu-usuario/Biblioteca-Kiaxi.git
cd Biblioteca-Kiaxi
