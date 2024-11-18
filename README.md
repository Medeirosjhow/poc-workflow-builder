
# Workflow Builder POC

Este repositório é uma Prova de Conceito (POC) para a implementação de um **Workflow Builder** utilizando **Angular**, **SCSS** e **Rete.js**.

O objetivo deste projeto é criar um ambiente funcional que permita a construção e manipulação visual de workflows, com base em nós e conexões. A aplicação será modular e extensível, servindo como base para futuras integrações ou desenvolvimento de ferramentas mais complexas.

---

## 🚀 Tecnologias Utilizadas

- **Angular**: Framework para desenvolvimento de aplicações web modernas e dinâmicas.
- **SCSS**: Pré-processador CSS utilizado para estilização avançada e modular.
- **Rete.js**: Biblioteca JavaScript para construção de editores visuais baseados em nós e fluxos.

---

## 🛠️ Funcionalidades Planejadas

- **Criação Visual de Workflows**: 
  - Permitir adicionar, editar e excluir nós e conexões de forma intuitiva.
- **Design Modular**:
  - Componentização clara para facilitar a reutilização de elementos.
- **Estilização Personalizada**:
  - Estilo customizável e responsivo utilizando **SCSS**.
- **Base para Extensões**:
  - Suporte para integração com regras e condições personalizadas.

---

## 📂 Estrutura do Projeto

```
src/
├── app/
│   ├── components/          # Componentes do Workflow Builder
│   ├── services/            # Serviços para lógica de negócios
│   ├── styles/              # Arquivos SCSS globais e variáveis
│   └── app.module.ts        # Módulo principal da aplicação
├── assets/                  # Arquivos estáticos
├── environments/            # Configurações de ambiente
└── main.ts                  # Ponto de entrada do Angular
```

---

## 🖼️ Interface

A interface do Workflow Builder permite:
1. **Nós personalizados**: Criação de blocos (nós) com diferentes configurações.
2. **Conexões interativas**: Arraste e solte para conectar ou remover nós.
3. **Integração de temas**: Estilos personalizáveis utilizando SCSS.

---

## 📦 Instalação e Configuração

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/workflow-builder-poc.git
   cd workflow-builder-poc
   ```

2. Instale as dependências:
   ```bash
   npm install
   ```

3. Inicie o servidor de desenvolvimento:
   ```bash
   ng serve
   ```

4. Acesse a aplicação em [http://localhost:4200](http://localhost:4200).

---

## 🛡️ Pré-requisitos

- Node.js >= 16.x
- Angular CLI >= 16.x
- Navegador atualizado (recomendado: Chrome ou Edge)

---

## 📖 Próximos Passos

- Implementar um sistema de armazenamento de workflows.
- Adicionar validação de conexões e regras.
- Documentação detalhada para desenvolvedores.

---

## 🤝 Contribuições

Sinta-se à vontade para abrir **issues** ou enviar **pull requests**. Feedbacks e sugestões são bem-vindos!

---

## 📝 Licença

Este projeto está sob a licença [MIT](LICENSE).
