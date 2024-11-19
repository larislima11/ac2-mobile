# **Cadastro de Alunos - Atividade 4**

Este projeto foi desenvolvido como parte da Atividade 4 do curso, com o objetivo de criar um aplicativo Android para cadastro e listagem de alunos. Ele utiliza a API **ViaCEP** para preenchimento automático do endereço e o **MockAPI** para armazenamento dos dados.

---

## **Índice**
1. [Funcionalidades](#funcionalidades)
2. [Tecnologias Utilizadas](#tecnologias-utilizadas)
3. [Pré-requisitos](#pré-requisitos)
4. [Configuração e Execução](#configuração-e-execução)
5. [Estrutura do Projeto](#estrutura-do-projeto)
6. [Demonstração](#demonstração)
7. [Autor](#autor)

---

## **1. Funcionalidades**

### **Tela de Cadastro**
- Preenchimento automático do endereço ao informar o CEP.
- Integração com a API **ViaCEP** para buscar endereço.
- Salvamento dos dados no **MockAPI** via requisição POST.

### **Tela de Listagem**
- Listagem de todos os alunos cadastrados no MockAPI.
- Dados exibidos em um `RecyclerView`.

---

## **2. Tecnologias Utilizadas**
- **Linguagem:** Java
- **Frameworks e Bibliotecas:**
  - Retrofit
  - Gson
  - Android Architecture Components
- **APIs Utilizadas:**
  - [ViaCEP](https://viacep.com.br/)
  - [MockAPI](https://mockapi.io/)
- **Interface:** XML para layouts no Android Studio
- **Ambiente de Desenvolvimento:** Android Studio com Gradle







