# 💻 EduLogCpp: Engenharia de Software Aplicada à Perfilagem Geofísica

### Software educativo em C++ estruturado com Programação Orientada a Objetos e boas práticas para simulação de curvas de log com sondas wireline.

<p align="center">
  <img src="https://shields.io" alt="C++ Version">
  <img src="https://shields.io" alt="Paradigma POO">
  <img src="https://shields.io" alt="Boas Práticas">
</p>

## 📝 Descrição do Projeto
Aplicação didática desenvolvida em C++ moderno para demonstrar conceitos avançados de POO, como polimorfismo e encapsulamento, usando a perfilagem de poços como estudo de caso. O software integra bibliotecas de terceiros e adota arquitetura limpa com separação de responsabilidades para simular o registro vertical de curvas geofísicas.

O objetivo principal deste repositório é servir como avaliação prática para a disciplina de **Programação Orientada a Objetos**, utilizando o domínio de negócio da engenharia de petróleo e geofísica (Wireline Logging) como pano de fundo de forma estritamente educativa.

---

## 🛠️ Pilares de POO Aplicados
Para atender aos rigorosos requisitos de engenharia de software, o projeto foi desenhado utilizando os seguintes conceitos:

*   **Encapsulamento:** Proteção do estado interno de classes críticas (como dados dos sensores e propriedades físicas das camadas do poço).
*   **Abstracionismo & Polimorfismo:** Criação de uma classe base abstrata `Sensor`. Sensores específicos (`RaioGama`, `Resistividade`, `Densidade`) herdam desta classe e implementam suas próprias fórmulas de leitura através de funções virtuais puras.
*   **Princípio da Responsabilidade Única (SOLID):** Separação clara entre a lógica de descida da sonda, o processamento físico das rochas e a exibição gráfica/textual dos dados.

---

## 📦 Bibliotecas de Terceiros e Tecnologias
O projeto utiliza ferramentas de mercado para garantir robustez e portabilidade:
*   **Sistema de Build:** `CMake` para gerenciamento moderno de compilação.
*   **Biblioteca Externa:** *[Escolha e adicione aqui a biblioteca usada, ex: `matplotplusplus` para gráficos, `SFML` para interface visual, ou `fmt` para formatação de texto]*.

---

## 📂 Estrutura do Repositório
O código segue o padrão de organização profissional da comunidade C++:

```text
├── include/          # Arquivos de cabeçalho (.hpp) com as assinaturas das classes
│   ├── Sonda.hpp
│   ├── Sensor.hpp
│   └── Poco.hpp
├── src/              # Implementação das regras de negócio (.cpp)
│   ├── Main.cpp
│   ├── Sonda.cpp
│   └── Poco.cpp
├── third_party/      # Dependências e bibliotecas de terceiros
├── CMakeLists.txt    # Script de automação do build do projeto
└── README.md         # Documentação principal
```

---

## 🚀 Como Compilar e Executar

### Pré-requisitos
*   Compilador C++ com suporte a C++17 ou superior (`GCC`, `Clang` ou `MSVC`).
*   `CMake` instalado.

### Passo a Passo
1. Clone o repositório:
   ```bash
   git clone https://github.com
   ```
2. Acesse a pasta do projeto:
   ```bash
   cd nome-do-repositorio
   ```
3. Crie e acesse o diretório de build:
   ```bash
   mkdir build && cd build
   ```
4. Gere os arquivos de build e compile:
   ```bash
   cmake ..
   cmake --build .
   ```
5. Execute o software educativo:
   ```bash
   ./EduLogCpp
   ```

---

## 👨‍💻 Autor
*   **Seu Nome** - *Desenvolvedor Principal* - [Seu GitHub](https://github.com)
