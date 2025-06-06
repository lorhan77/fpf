﻿# Desafio Técnico  
**Este é o desafio técnico Full Stack da FPF Tech**

Este projeto combina um **servidor Django** com uma **interface Angular**.  
Siga os passos abaixo para configurar e executar a aplicação.  

---  

## O que você precisa  

Antes de começar, verifique se possui instalado:  

- **Docker** e **Docker Compose** (para o backend)  
- **Node.js** (versão 16+) e **npm** (para o frontend)  
- **Python** (versão 3.11 ou superior)  

---  

## Servidor (Backend)  

Desenvolvido em Django com suporte a tarefas assíncronas usando Celery.  

### Rodando com Docker  

1. Tenha o Docker e Docker Compose instalados.  
2. No diretório principal, execute:  
   ```sh  
   docker-compose up --build  
   ```  
3. O servidor estará acessível em: `http://localhost:8000`. 
4. O serviço do *Celery* iniciará automaticamente.


## Interface (Frontend)  

Construída em Angular para uma experiência dinâmica.  

### Configuração  

1. Acesse a pasta do frontend:  
   ```sh  
   cd frontend  
   ```  
2. Instale as dependências:  
   ```sh  
   npm install  
   ```  
3. Inicie o servidor de desenvolvimento:  
   ```sh  
   ng serve  
   ```  
   ou  
   ```sh  
   npm start  
   ```  
4. Acesse via: `http://localhost:4200`.  

---  

## Organização do Projeto  

- **Backend**: Pastas `desafiofpf` e `fpfbackend`.  
- **Frontend**: Toda a estrutura Angular em `frontend`.  

---  

## Dicas Importantes  

- Mantenha backend e frontend rodando ao mesmo tempo para o correto funcionamento.  
- Consulte a [documentação oficial do Angular CLI](https://angular.io/cli) para mais detalhes.  

---  
 

## Funcionamento  

- Preencha os campos com valores numéricos (inteiros ou decimais)  
- Acione o cálculo clicando no botão  
- Em instantes, serão exibidos: média, mediana e status  

