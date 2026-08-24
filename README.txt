ACADEMIA DE SIMULADOS — ANGOLA
================================

ESTRUTURA
- index.html: aplicação completa.
- data/questions.json: banco de questões separado por disciplina.
- assets/: reservado para imagens/ícones.
- FONTES_OFICIAIS.txt: fontes oficiais usadas para dados transversais.

REGRA DE ORGANIZAÇÃO
1. Cada disciplina mantém os seus conteúdos técnicos.
2. Censo 2024, IIMS 2023–2024, DPA, cultura geral, ética e IA ficam no bloco:
   "Transversais — Cultura Geral / Censo / IIMS / DPA / Ética / IA".
3. Não são misturados conceitos técnicos de Ortoprotesia, Radiologia, Enfermagem,
   Farmácia, Fisioterapia ou Análises Clínicas dentro de Cultura Geral.
4. O mesmo modelo pode receber novas disciplinas sem alterar o motor.

COMO USAR
1. Extraia o ZIP.
2. Coloque a pasta inteira no serviço/app que aceita HTML.
3. Abra index.html.
4. Não retire a pasta data: o banco é carregado de data/questions.json.
5. Para gerar PDF, use o botão "PDF / Imprimir" e escolha "Guardar como PDF"
   no navegador.

NOTA SOBRE "ENCRIPTO"
Este projeto usa JavaScript no navegador. Isso não é proteção criptográfica real:
qualquer banco enviado ao navegador pode ser inspecionado por alguém com conhecimento
técnico. Para proteger questões/gabarito, é necessário um backend com autenticação e
banco de dados. Não foi criada uma senha falsa que dê uma sensação de segurança.

A aplicação já mantém a alternativa escolhida ao voltar para uma questão e embaralha
a ordem das questões a cada novo simulado, sem alterar a posição da resposta correta
dentro de cada objeto.
