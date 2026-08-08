
# RELATÓRIO 1: ESPECIFICAÇÃO DO PROJETO EDUCATIVO (EduLogCpp)

**Disciplina:** Programação Orientada a Objetos em C++
**Data de Entrega:** 13/08/2026
**Integrantes:** [Seu Nome Completo] (e dos seus colegas, se houver)
**Link do Repositório:** [Cole o link do seu GitHub aqui]

---

## 1. ESPECIFICAÇÃO DO SISTEMA (O QUE É O PROJETO)

O projeto consiste no desenvolvimento de um software educativo escrito em C++ utilizando o paradigma de Programação Orientada a Objetos (POO) e boas práticas de desenvolvimento. O sistema simulará o processo geofísico de Perfilagem de Poços (Wireline Logging).

### 1.1. O Estudo de Caso (Domínio de Negócio)
O software funcionará como um simulador interativo onde uma sonda virtual desce por um poço em terra de 10 em 10 metros. Conforme a sonda avança em profundidade, ela realiza leituras fictícias através de sensores para mapear as características do subsolo, gerando três curvas de dados essenciais: Raios Gama, Resistividade e Densidade.

### 1.2. Estrutura de Classes Planificada (Conceitos de POO)
Para garantir um código limpo e de fácil manutenção, utilizaremos os pilares de POO através das seguintes classes:
*   **Classe `Sonda`:** Responsável por controlar a descida vertical no poço, armazenar a profundidade atual e acionar os sensores.
*   **Classe Base `Sensor`:** Uma classe abstrata que servirá de modelo para todos os sensores.
*   **Classes Derivadas (`SensorRaioGama`, `SensorResistividade`, `SensorDensidade`):** Classes que herdam de `Sensor` e utilizam o conceito de herança para calcular e retornar as leituras específicas de cada curva geofísica.
*   **Classe `Poco`:** Gerencia as camadas da terra e simula o ambiente físico que os sensores estão lendo.

### 1.3. Biblioteca de Terceiros Pretendida
Para atender aos requisitos técnicos, planejamos integrar uma biblioteca externa para formatação, manipulação ou exibição simplificada dos dados capturados em tela de forma visual e didática.

---

## 2. CONFIGURAÇÃO DO REPOSITÓRIO GITHUB

O ambiente de desenvolvimento do projeto já foi configurado e estruturado publicamente. 
*   **Nome do Repositório:** EduLogCpp
*   **Membros Cadastrados:** Todos os integrantes da equipe foram convidados e adicionados como colaboradores formais no painel de controle do repositório (Configuration > Collaborators).
*   **Documentação Inicial:** O arquivo README.md inicial já conta com o título do projeto, subtítulo de escopo técnica e descrição resumida para fácil entendimento do avaliador.
