![Banner do Projeto ElyOS](img/elyos_banner_horizontal.png)
# ElyOS - Praticando a Comunicação Não Violenta

## Sobre o Projeto

ElyOS é um protótipo de chatbot projetado para auxiliar usuários a aprender e praticar os princípios da Comunicação Não Violenta (CNV). Ele atua como um companheiro virtual, oferecendo conteúdo educativo, exercícios e um sistema simples de acompanhamento de progresso representado por um animal companheiro virtual.

Este repositório contém o **core funcional** do protótipo, desenvolvido em Python.

## Como Rodar o Core Funcional

O núcleo deste protótipo é um script Python que pode ser executado em ambientes como o Google Colab ou qualquer terminal Python com as dependências necessárias instaladas (principalmente as bibliotecas do Google GenAI e ADK, conforme especificado no código).

1.  Certifique-se de ter as bibliotecas `google-genai` e `google-adk` instaladas (`pip install google-genai google-adk`).
2.  Configure sua API Key do Google Gemini (em Colab, isso geralmente é feito via `userdata.get('GOOGLE_API_KEY')`).
3.  Execute o script Python principal.

Atualmente, a interação ocorre via entrada e saída de texto no console/terminal.

## Status do Protótipo

Este projeto está em fase de prototipagem. O código Python neste repositório representa a **lógica de backend** (agentes de processamento de linguagem, busca de conteúdo, gerenciamento básico de estado do companheiro).

A **interface gráfica** interativa para o usuário está em desenvolvimento.

## Interface Planejada (Mockup Visual)

Para ilustrar a experiência do usuário final planejada, criamos um mockup visual da interface mobile. Você pode visualizar o design proposto aqui:

[**Veja o protótipo da interface no Figma**](https://www.figma.com/proto/0hHZWy4FhENz0QWhhcaPNj/Chatbot?page-id=43%3A8161&node-id=47-377&p=f&viewport=255%2C244%2C0.58&t=jMnI4K8SJqcg1u4x-1&scaling=min-zoom&content-scaling=fixed)

[**Link para ver o código direto no Google Colab**](https://colab.research.google.com/drive/16Kk2JcQw9uTwa_p4SsAF-2_s6z5z3CAX?usp=sharing)

Este mockup demonstra as telas principais de interação do usuário com o ElyOS.

## Próximos Passos

O próximo passo no desenvolvimento é implementar a interface de usuário funcional, integrando o core Python com elementos interativoS.

---

Muito obrigado pelo seu interesse no ElyOS!

![Banner do Projeto ElyOS](img/elyos_footer.png)
