
# GENE KIM
autor de The Phoenix Project: A Novel About IT, DevOps, and Helping Your Business Win 
The Visible Ops Handbook,
pesquisador, fundador e ex-CTO da Tripwire. Sou apaixonado por operações de TI, segurança e conformidade, e como as organizações de TI se transformam com sucesso de “boas a excelentes”. 


# TOSTINES 1984 ****

# DevOps
O DevOps é a combinação de filosofias culturais, práticas e ferramentas que aumentam a capacidade de uma empresa de distribuir aplicativos e serviços em alta velocidade. 

otimizando e aperfeiçoando produtos em um ritmo mais rápido do que o das empresas que usam processos tradicionais de desenvolvimento de software e gerenciamento de infraestrutura. 

Essa velocidade permite que as empresas atendam melhor aos seus clientes e consigam competir de modo mais eficaz no mercado.


# 1- fluxo de valor  - lean  -  agilizar otimizar - lead time

## 1. trabalho visivel - kanbam

## 2. diminuir o entregavel e aumentar a frequenacia

## 3. remover as restricoes :
	(ciclo ) livro "a meta" - Goldratt (alocar os recursos)
		identificar
		explorar
		sincronizar o sistema  a restrição (focar e eliminar)
		elevar a restrição( fazer de tudo o que possivel para aumente capacidade)
		melhoria continua ( ai surge a nova restrição)
		
## 4. focar no que o cliente quer  desperdicios herança do lean (8-9 principios)
	trabalho parcialmente pronto -  focar em finalizar para iniciar coisas novas
	processos extras 		 -  atividades desnecessarias para agregar valor ao cliente
	recursos extras  - funcionalidades que nao agregam valor para o cliente
	multitarefa  - fazer tudo ao mesmo tempo e muitos projetos
	defeitos - retrabalho para corrigir erros
	trabalho manual - atividades propicio a erros
	ato heroico - esforço acima do normal para atingir meta ( só ele sabe fazer)

## 5. passagem de bastao

## 6. equipe focar na qualidade do handoff

## 7. limitar o trabalho (WIP) working in progress

## 8. controle de versao IaC

## 9. CI/CD

## 10. Testes TDD

## 11. arquitertura e releases de baixo risco ( canario / blue green)
	release de baixo risco ( tecnicas que nao impactam o cliente)
	implanta e nao libera( teste, producao)
	liberação da release para usuario

	**release:**
	1- baseado no ambiente:
	2 ou mais ambientes  ( azul -verde e canario )
	2- baseado no aplicativo:
	novas funcionalidades de forma seletiva configuracao simples( não precisa de deploy) (feature flags)

	**arquitetura de baixo risco:**
	1- microserviços (modularização)
    

# 2- feedback o mais rapido

## 1. dados e fatos ( gemba) acompanhar seu codigo
	Gemba é uma palavra de origem japonesa que significa o "verdadeiro lugar". Quando aplicada à manufatura, 
    significa o lugar onde as coisas acontecem na fábrica.

## 2. unificar as pessoas:
	Corda de Andon: dispositivo que existe nas fábricas da Toyota para
	interromper a linha de produção quando é encontrado algum defeito nos
	produtos. O objetivo é aglomerar imediatamente todas as equipes e líderes que
	podem ajudar a resolver o problema na origem, podendo mobilizar os
	executivos e a alta administração.

## 3. gestão de mudanças 
        revisoes em pares e quem ta mais perto tem mais opniao de opinar de quem esta mais longe

## 4. resultados da telemetria ( disponivel, saude da aplicação)
        disponivel a todos

## 5. teste A/B e baseado em hipoteses:
	**teste A/B:**
		tecnica usada no marketing ( controle A: conteudo mantido / controle B: implementa a funcionalidade)
		exemplo: uber  - fila dos motoristas ou localização? 
		
		Alternancia de recursos(sem deploy)
			funcionalidades pra 10% dos usuarios, 
			resultado positivo expandir;

	**hipoteses**
		100 funcionalidades, foca em 5 e entrega - coleta os dados feedbacks
		pivotar de acordo com as acoes e resultados 
        
## 6. trabalhar em conjunto
        Dev e Ops - plantoes de suporte 24/7

## 7. revisão do codigo
    pull request
    code review
    programação em pares
    sobre os ombros
    assistencia por ferramentas



# 3-(errar rapido, aprender rapido e acertar rapido) experimentacao aprendizado  (lean puro)

## 1. ninguem aponta o dedo pra ninguem, sem limitar a criatividade
        cultura justa e segura, evoluir com os erros

## 2. caso netflix:
	Conceito de anti-frágil (musculação)
       Filho e pai - troca de pneu
       Preparar para a falha - Chaos Monkey
       
## 3. pequenas experimentações locais e divugar o (resultado positivo)

## 4. aprender aplicar a melhoria continua KATA,  atacar o debito tecnico erros de arquiteturar, refatoracao 20% tempo equipe 
	O que é um kata?
	
	O termo kata vem das artes marciais, principalmente do caratê. Os katas nas artes marciais são movimentos físicos, chamados de formas, projetados para serem praticados repetidamente. Cada movimento individual é simples e pode ser repetido muitas vezes em um curto período. O praticante de kata se concentra em fazer pequenas melhorias a cada repetição.

	O “Code Kata” é uma adaptação do conceito de kata para o desenvolvimento de software. O movimento Software Craftsmanship adaptou katas para criar exercícios curtos de codificação. Code katas são projetados para ajudar os desenvolvedores de software a praticar a programação.

	DevOps Katas combinam ferramentas DevOps com o conceito Code Kata. A diferença é que DevOps Katas não ensinam programação. O objetivo é aprender a usar ferramentas DevOps, para que todos os exercícios sejam livres de código

## 5. aprender com as falhas, nao ficar se acusando, liderança atuar em equipe.
	De projeto em projeto, existem lições a serem aprendidas e o postmortem é justamente isso, mas de forma organizada e raramente feito. ... Um postmortem de projeto deveria fazer parte da cultura das empresas que criam software, mas só as que realmente estão buscando qualidade incorporam essa prática.

## 6. me preparar para ensair falhas, planejamento. 
        dias de jogos.

## 7. teste automatizado como documentação, manter e aprender. 






	
	

     
1.4 Desperdício: toda atividade que consome recursos sem adicionar valor na
		visão do cliente. Existem oito tipos de desperdícios identificados no Lean:
		‒ Defeito e retrabalho: desfazer, refazer algo.
		‒ Movimentação: caminhadas, deslocamentos e viagens.
		‒ Espera: pessoas aguardando informações, materiais ou outras equipes.
		‒ Transporte: transferências desnecessárias de materiais ou informações.
		‒ Estoques: informações ou materiais sem uso.
		‒ Processamento: etapa redundante ou desnecessária.
		‒ Desconexão ou superprodução: fluxo deficiente ou falta de sincronismo
		entre etapas (antes ou depois do necessário).
		‒ Conhecimento: não aproveitar as habilidades das pessoas adequadamente.

