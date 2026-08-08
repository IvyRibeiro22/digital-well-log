# 💻 EduLogCpp: Arquitetura Orientada a Objetos e Engenharia de Software em C++ Moderno

### Software focado na aplicação estrita de Polimorfismo, Encapsulamento Avançado e Gerenciamento de Memória Eficiente com C++17/20 através de Bibliotecas de Terceiros.

**Descrição:**  
Framework desenvolvido em C++ para consolidar conceitos avançados de POO, herança múltipla/virtual, tratamento robusto de exceções e padrões de projeto (Design Patterns). O software adota uma arquitetura modular acoplada via CMake, utilizando compilação estática e bibliotecas de terceiros para demonstrar boas práticas de engenharia de software, separação de responsabilidades (SOLID) e alta performance em sistemas tipados.

---

## 🌎 O Estudo de Caso Aplicado: Perfilagem Geofísica (Wireline Logging)
Para dar vida aos conceitos abstratos de Orientação a Objetos, o projeto utiliza como domínio de negócio a **Perfilagem Geofísica de Poços**. 

O software funciona como uma ferramenta educacional interativa que simula a descida de uma sonda presa por um cabo elétrico (*wireline*) em um poço subterrâneo. À medida que a sonda desce, o sistema executa o registro vertical contínuo de dados físico-químicos das rochas de 10 em 10 metros, gerando curvas de log em tempo real. 

### 📐 Mapeamento do Domínio em Conceitos de C++:
*   **A Sonda (`Sonda.hpp`):** Classe controladora que gerencia o estado da profundidade, velocidade de descida e o ciclo de vida dos sensores acoplados.
*   **Os Sensores (`Sensor.hpp`):** Uma classe base puramente abstrata (interface) que define o comportamento polimórfico de leitura.
*   **Curvas de Log (`RaioGama.hpp`, `Resistividade.hpp`, `Densidade.hpp`):** Classes derivadas que herdam de `Sensor` e implementam suas próprias fórmulas matemáticas e algoritmos de captura de dados de forma especializada.

Dessa forma, o usuário aprende conceitos de geologia e geofísica na prática, enquanto o desenvolvedor demonstra o domínio completo de estruturas de dados e arquitetura de software em C++.
