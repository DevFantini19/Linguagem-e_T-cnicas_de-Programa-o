🧠 Análise de Código em C - Correções e Explicações
Este repositório contém uma atividade prática da disciplina Linguagem e Técnicas de Programação, do curso de Análise e Desenvolvimento de Sistemas, cujo objetivo foi identificar, 
explicar e corrigir erros em um código-fonte escrito na linguagem C.

📌 Objetivo da Atividade
Analisar trechos de código em linguagem C e descrever de forma técnica:
O tipo de erro encontrado.
O motivo do erro.
A forma correta de resolução.
Boas práticas de programação.

🛠️ Conteúdo
Foram identificados e corrigidos os seguintes erros:
Retorno prematuro dentro de loop
❌ Impedia a exibição da mensagem de erro para número inválido.
✅ Correção: mover a verificação para fora do for.
Índice incorreto na contagem de votos
❌ O loop começava em 1, ignorando o primeiro candidato.
✅ Correção: iniciar a iteração com i = 0.
Cálculo incorreto de percentual
❌ A fórmula (totalVotos / 100) não representava corretamente o percentual.
✅ Correção: uso de (float)candidatos[i].votos / totalVotos * 100.
Falta de break em instruções switch
❌ Fazia com que várias opções fossem executadas indevidamente.
✅ Correção: adicionar break após cada case.

📚 Aprendizados
Importância da lógica e estruturação de fluxos em linguagem C.
Cuidados com estruturas de controle como for, switch e tipos de variáveis.
Cálculos com precisão usando float para evitar erros lógicos.
Escrita de código limpo, bem organizado e funcional.

👩‍💻 Desenvolvido por Laura Fantini Souza Ferreira
Curso: Análise e Desenvolvimento de Sistemas – Unicesumar
Ano: 2025
