# Minha-Escola Soft 🏫

O Minha-Escola Soft é uma aplicação Java projetada para automatizar processos críticos de administração escolar, garantindo a organização eficiente de dados e o controle rigoroso de fluxo de estudantes.

## 🛠️ Funcionalidades Principais
    -Módulo de Inscrição Inteligente: Cadastro de alunos com captura de dados demográficos e acadêmicos completos.
    -Garantia de Integridade de Dados: Algoritmos de validação que asseguram a unicidade de documentos críticos, como Bilhete de Identidade e Número de Matrícula.
    -Gestão de Capacidade Operacional: Controle automatizado de ocupação de salas, respeitando o limite máximo de 40 alunos por turma e teto de 3 salas ativas.
    -Mecanismo de Busca e Relatórios: Consulta rápida por múltiplos identificadores e listagem segmentada por turma ou visão global da instituição.
    
## 🏗️ Arquitetura do SistemaO projeto utiliza uma arquitetura em camadas para facilitar a manutenção e escalabilidade:
    -Model: Representação das entidades de negócio.-
    -Service: Camada de lógica onde residem as regras de validação e restrições.
    -Repository: Abstração de armazenamento de dados em memória.
    -View: Interface de interação com o usuário final.
    
## 🚀 Próximos Passos (Roadmap)
    -[ ] Implementação de Persistência de Dados (JSON/Database).
    -[ ] Desenvolvimento de Interface Gráfica (Swing/JavaFX).
    -[ ] Sistema de relatórios exportáveis em PDF.
