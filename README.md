# simula-o-com-medusa
# 🔐 Laboratório de Auditoria de Senhas com Kali Linux e Medusa

## 📌 Sobre o projeto

Este projeto foi desenvolvido como parte de um desafio prático da **Digital Innovation One (DIO)**, com o objetivo de estudar e compreender ataques de força bruta (*Brute Force*) em ambientes controlados, utilizando ferramentas de segurança ofensiva.

O laboratório foi implementado utilizando o **Kali Linux** como máquina atacante e o **Metasploitable 2** como máquina-alvo, ambos virtualizados no Oracle VM VirtualBox.

Durante a atividade, foram explorados conceitos de auditoria de credenciais, reconhecimento de serviços, tentativas automatizadas de autenticação e identificação de vulnerabilidades relacionadas ao uso de senhas fracas.

> ⚠️ Todos os testes foram realizados em ambiente virtual controlado, utilizando uma máquina intencionalmente vulnerável para fins educacionais.

## 🎯 Objetivos

- Compreender o funcionamento de ataques de força bruta.
- Utilizar a ferramenta Medusa em testes de auditoria.
- Identificar serviços vulneráveis em ambientes Linux.
- Entender os riscos relacionados ao uso de senhas fracas.
- Estudar técnicas de enumeração de serviços e usuários.
- Conhecer medidas de prevenção contra ataques de força bruta.
- Documentar os procedimentos técnicos utilizando GitHub.

## 🖥️ Ambiente utilizado

| Componente | Descrição |
|---|---|
| Máquina atacante | Kali Linux |
| Máquina-alvo | Metasploitable 2 |
| Virtualização | Oracle VM VirtualBox |
| Ferramenta principal | Medusa |
| Ferramenta auxiliar | Nmap |
| Ambiente | Rede virtual isolada |

## 🛠️ Ferramentas utilizadas

### Kali Linux
Distribuição Linux voltada para testes de invasão, auditoria de segurança e análise de vulnerabilidades.

### Medusa
Ferramenta utilizada para realizar testes automatizados de autenticação em diferentes serviços de rede, permitindo avaliar a resistência de credenciais contra tentativas de força bruta.

### Nmap
Ferramenta de reconhecimento de rede utilizada para identificar hosts ativos, portas abertas e serviços disponíveis na máquina-alvo.

### Metasploitable 2
Máquina virtual desenvolvida intencionalmente com vulnerabilidades para treinamento e prática de segurança ofensiva.

## 🔎 Desenvolvimento do laboratório

### 1. Configuração do ambiente

Inicialmente, foram preparadas duas máquinas virtuais no Oracle VM VirtualBox:

- Kali Linux, utilizado como máquina atacante.
- Metasploitable 2, utilizado como máquina-alvo.

Foi configurada a comunicação entre as máquinas por meio de uma rede virtual isolada, permitindo a execução dos testes em ambiente controlado.

### 2. Reconhecimento e enumeração

Foi realizado o reconhecimento da máquina-alvo utilizando o Nmap, com o objetivo de identificar os serviços disponíveis, portas abertas e possíveis pontos de exposição.

### 3. Testes de força bruta

Com o ambiente configurado, foram realizados testes controlados utilizando a ferramenta Medusa.

O objetivo foi compreender como tentativas automatizadas de autenticação podem explorar credenciais fracas ou padrões previsíveis de senhas.

Foram estudados cenários envolvendo autenticação em serviços de rede e os conceitos de força bruta e password spraying.

### 4. Análise dos resultados

Após a execução dos testes, foram analisados os resultados obtidos, considerando:

- Serviços identificados na máquina-alvo.
- Comportamento dos mecanismos de autenticação.
- Riscos associados ao uso de senhas fracas.
- Possibilidade de acesso indevido por meio de credenciais vulneráveis.

## 🛡️ Medidas de prevenção e mitigação

A realização do laboratório permitiu compreender a importância de implementar mecanismos de proteção contra ataques de força bruta.

Entre as principais medidas de segurança estão:

- Utilização de senhas fortes e únicas.
- Implementação de bloqueio temporário após tentativas consecutivas de autenticação.
- Utilização de autenticação multifator (MFA).
- Limitação de tentativas de login.
- Monitoramento de logs de autenticação.
- Desativação de serviços desnecessários.
- Restrição de acesso por meio de firewall.
- Atualização periódica dos sistemas e serviços.

## 📚 Aprendizados adquiridos

A execução deste laboratório proporcionou uma compreensão mais prática sobre segurança ofensiva e defensiva.

Entre os principais conhecimentos desenvolvidos estão:

- Utilização do Kali Linux em atividades de auditoria.
- Reconhecimento de serviços utilizando Nmap.
- Funcionamento da ferramenta Medusa.
- Compreensão de ataques de força bruta e password spraying.
- Identificação dos riscos relacionados a credenciais vulneráveis.
- Importância da configuração segura de serviços de rede.
- Aplicação de boas práticas de segurança da informação.

O projeto reforçou a importância de compreender as técnicas utilizadas em ataques para desenvolver estratégias eficientes de prevenção e proteção de sistemas.

## ⚖️ Aviso de responsabilidade

Este projeto possui finalidade exclusivamente educacional.

As técnicas apresentadas foram estudadas e aplicadas em um ambiente virtual controlado, utilizando uma máquina intencionalmente vulnerável.

Não utilize ferramentas de auditoria ou técnicas de força bruta contra sistemas, redes ou serviços sem autorização expressa dos responsáveis.

## 👨‍💻 Autor

**Gustavo**

Estudante de Engenharia de Software, infraestrutura, Linux e segurança da informação.

Projeto desenvolvido como atividade prática da Digital Innovation One (DIO).
