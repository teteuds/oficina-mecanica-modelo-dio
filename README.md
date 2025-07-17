# 💼 Sistema de Gerenciamento de Oficina Mecânica

## 📚 Descrição do Projeto

Este projeto consiste na modelagem de um *esquema conceitual* para um sistema de controle e gerenciamento de ordens de serviço em uma *oficina mecânica*. A proposta visa representar de forma lógica como as informações estão interligadas e organizadas, partindo da narrativa fornecida.

O sistema permite:
- Registro de clientes e seus veículos
- Designação de equipes de mecânicos para execução de serviços
- Criação e controle de Ordens de Serviço (OS)
- Cálculo automático dos valores com base em mão-de-obra e peças utilizadas
- Registro de autorização dos serviços pelo cliente

## 🔧 Entidades Principais

- *Cliente:* Informações pessoais de quem contrata os serviços.
- *Veículo:* Associado a um cliente, pode passar por revisão ou conserto.
- *Mecânico:* Profissionais da oficina, organizados em equipes.
- *Equipe:* Grupo de mecânicos designado para realizar uma OS.
- *Ordem de Serviço (OS):* Documento com os serviços e peças a serem utilizados.
- *Serviço:* Tipo de manutenção ou conserto a ser feito, com valor de mão de obra.
- *Peça:* Itens utilizados durante a execução da OS.

## 🔁 Relacionamentos

- Um cliente pode ter vários veículos.
- Um veículo pode gerar várias ordens de serviço.
- Uma equipe realiza a OS de um veículo.
- Uma equipe possui vários mecânicos.
- Uma OS pode conter múltiplos serviços e peças.

## 🧠 Considerações

Alguns elementos não estavam definidos na narrativa (como nomes de entidades ou tabelas auxiliares). Portanto, utilizei o bom senso e práticas comuns em modelagem de dados para completar o esquema. Todas essas decisões estão documentadas aqui para futura validação.

