# ✚ hospital_DB

## 📑 Sumário
- [Sobre o projeto](#-sobre-o-projeto)
- [Objetivo](#-objetivo)
- [Estrutura do banco](#-estrutura-do-banco)
- [Tecnologias utilizadas](#-tecnologias-utilizadas)
- [Consultas SQL](#-consultas-sql)
- [Organização dos arquivos](#-organização-dos-arquivos)
- [Autor](#-autor)
- [Objetivo educacional](#-objetivo-educacional)

## 📌 Sobre o projeto
O `hospital_DB` é um projeto acadêmico desenvolvido em MySQL para organizar dados relacionados ao funcionamento de um hospital, reunindo informações sobre pacientes, médicos, consultas, internações, quartos e prescrições.

## 🎯 Objetivo
O projeto busca aplicar na prática os conceitos de banco de dados relacionais, permitindo armazenar, relacionar e consultar informações de forma organizada.

## 🗄️ Estrutura do banco
O banco de dados é formado por seis tabelas:

- 🧑‍⚕️ Pacientes: dados dos pacientes e seus convênios.
- 🩺 Médicos: informações dos profissionais e suas especialidades.
- 📅 Consultas: registros dos atendimentos, datas, valores e status.
- 🏨 Internações: dados sobre entradas, saídas e valores das diárias.
- 🛏️ Quartos: identificação, tipo e situação dos quartos.
- 💊 Prescrições: medicamentos, dosagens e quantidades prescritas.

## ⚙️ Tecnologias utilizadas
- 🐬 MySQL 8.0
- 🖥️ MySQL Workbench

## 📊 Consultas SQL
O projeto possui 10 consultas SQL que permitem analisar diferentes informações do hospital, como faturamento de consultas, médias de valores, internações, prescrições e atendimentos realizados.

Para isso, foram utilizados recursos como `INNER JOIN`, `WHERE`, `LIKE`, `GROUP BY`, `ORDER BY`, `SUM`, `AVG` e `COUNT`.

## 📂 Organização dos arquivos
Os arquivos SQL estão organizados na pasta `dumps/Dump20261112`, contendo os scripts de criação e preenchimento das tabelas, além do arquivo `querys.sql`, que reúne as consultas desenvolvidas.

---

## 👨‍💻 Autor

Projeto desenvolvido como atividade acadêmica de Banco de Dados.

**Autor:** Felipe Lisboa Carvalho

---

## 📚 Objetivo educacional
O projeto foi desenvolvido para praticar a criação de tabelas, relacionamentos, chaves primárias e estrangeiras, inserção de dados e elaboração de consultas SQL, aplicando os conhecimentos adquiridos durante as aulas de Banco de Dados.
