# Caderno de Prompts

Geradores de prompts de IA para professores, alinhados às competências e
habilidades da **BNCC de Computação** (Complemento à BNCC — Computação,
Resolução CNE/CEB nº 1/2022).

- 92 geradores, organizados por Planejar, Atividades, Avaliar, Engajar,
  Pesquisar, Materiais, Comunicar e Tecnologia
- Formato de saída escolhido pelo professor em todos os geradores: texto
  corrido, tabela, slides, documento para impressão, quiz ou mapa mental
- Habilidades da BNCC e da BNCC de Computação selecionadas pela IA: o prompt
  leva o código e o texto oficial das 141 habilidades de Computação (as da
  etapa) e instrui a IA a escolher, justificar e marcar as habilidades usadas
- Botões que copiam o prompt e abrem a IA recomendada para cada tarefa
- Guias: IAs recomendadas, instalar no celular, publicar o app, BNCC de Computação

Aplicação de página única, sem dependências além das fontes do Google.
O arquivo `index.html` é autossuficiente.

## Caderno de Contexto (`/contexto`)

Novo aplicativo baseado na metodologia v3 (engenharia de contexto). Em vez de
gerar um prompt a cada pedido, ele monta uma vez o contexto pedagógico do
professor e o mantém atualizado com a memória de cada turma.

- Contexto em 7 camadas: referência curricular (texto oficial das habilidades
  de Computação da etapa), perfil docente, escola, turma, memória da turma,
  regras de trabalho e pedido
- Configuração única; depois, três perguntas por uso (turma, material e tema,
  formato de saída)
- Entrega por conversa (pacote completo) ou persistente (contexto fixo num
  projeto ou assistente e só o pedido a cada aula); versão comentada das camadas
- Caderno de Memória da Turma: registro pós-aula em um minuto, síntese
  automática e editável, que entra no próximo pacote
- Modo claro e escuro; dados só no navegador, com exportar, importar e apagar

Arquivo único e autossuficiente: `contexto/index.html`.

## Créditos

Adaptação do modelo **“Geradores de Prompts de IA para Professores”**, de
**Sérgio Araújo** (<https://educ.nekoweb.org/geradores/home.html>), licenciado
em CC BY-NC-SA 4.0. O código desta versão foi escrito do zero; a ideia e a
organização vêm do trabalho dele.

## Licença

[CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.pt-br) —
uso não comercial, com atribuição e compartilhamento pela mesma licença.
