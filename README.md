# EduLogCpp: Projeto em C++ usando os principais conceitos de Orientação à Objetos, boas práticas e biblioteca de terceiros.

### Software focado na aplicação de polimorfismo, encapsulamento, herança, tratamento de erros 

**Descrição:**  
Projeto em C++ desenvolvido para aprender a criar códigos organizados usando Orientação a Objetos e boas práticas de programação. O software simula sensores de engenharia que coletam dados de um poço e usa uma biblioteca de terceiros para exibir essas informações na tela. É um sistema simples e direto criado para colocar em prática conceitos básicos como classes, herança e funções de um jeito fácil de entender.

---

## O Estudo de Caso Aplicado: Perfilagem Geofísica (Wireline Logging)
Para dar vida aos conceitos abstratos de Orientação a Objetos, o projeto utiliza como domínio de negócio a **Perfilagem Geofísica de Poços**. 

O software funciona como uma ferramenta educacional interativa que simula a descida de uma sonda presa por um cabo elétrico (*wireline*) em um poço subterrâneo. À medida que a sonda desce, o sistema executa o registro vertical contínuo de dados físico-químicos das rochas de 10 em 10 metros, gerando curvas de log em tempo real. 

### 📐 Mapeamento do Domínio em Conceitos de C++:
*   **A Sonda (`Sonda.hpp`):** Classe controladora que gerencia o estado da profundidade, velocidade de descida e o ciclo de vida dos sensores acoplados.
*   **Os Sensores (`Sensor.hpp`):** Uma classe base puramente abstrata (interface) que define o comportamento polimórfico de leitura.
*   **Curvas de Log (`RaioGama.hpp`, `Resistividade.hpp`, `Densidade.hpp`):** Classes derivadas que herdam de `Sensor` e implementam suas próprias fórmulas matemáticas e algoritmos de captura de dados de forma especializada.

Dessa forma, o usuário aprende conceitos de geologia e geofísica na prática, enquanto desenvolve o domínio completo de estruturas de dados e Orientação em C++.
