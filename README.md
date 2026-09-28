# 💧 Sistema de Classificação de Consumo de Água

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)
![Status](https://img.shields.io/badge/Status-Conclu%C3%ADdo-brightgreen?style=for-the-badge)

## 📌 Sobre o Projeto
Este sistema foi desenvolvido em Python para a campanha de conscientização ambiental da companhia de saneamento local. O objetivo do programa é classificar o perfil de consumo de água dos imóveis e emitir alertas educativos personalizados para os moradores e empresários.

---

## ⚙️ Regras de Negócio e Funcionalidades

O script analisa a categoria do imóvel e o consumo mensal em metros cúbicos ($m^3$) de acordo com os seguintes critérios:

- **Comercial:** Exibe mensagem sobre a aplicação de tarifa comercial.
- **Apartamento com consumo < 10 $m^3$:** Identificado como consumo econômico.
- **Apartamento ou Casa com consumo de até 25 $m^3$:** Identificado como consumo moderado.
- **Demais casos (consumo acima do limite):** Emite alerta de consumo excessivo e orientação para checagem de vazamentos.

---

## 🚀 Como Executar o Projeto

### Pré-requisitos
- [Python 3.x](https://www.python.org/) instalado na máquina.

### Passo a Passo

1. Clone o repositório para a sua máquina local:
   ```bash
   git clone [https://github.com/seu-usuario/seu-repositorio.git](https://github.com/seu-usuario/seu-repositorio.git)