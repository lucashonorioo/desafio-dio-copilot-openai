# desafio-dio-copilot-openai

Entendendo Desafio 
Agora é a sua hora de brilhar e construir um perfil de destaque na DIO! Explore todos os conceitos abordados até aqui, aplique os conhecimentos adquiridos nas aulas e documente sua experiência para demonstrar sua compreensão dos temas discutidos.

Descrição do Desafio
Este laboratório tem como objetivo explorar as funcionalidades do Copiloto e das ferramentas da OpenAI, com ênfase nos filtros de conteúdo e nos recursos de criação assistida por inteligência artificial. O entregável consiste em um repositório organizado com exemplos de uso, prompts aplicados e anotações sobre os aprendizados adquiridos.

Objetivos de Aprendizagem 
Ao concluir este desafio, você será capaz de: 

Aplicar os conceitos aprendidos em um ambiente prático;
Documentar processos técnicos de forma clara e estruturada; 
Utilizar o GitHub como ferramenta para compartilhamento de documentação técnica. 

Resumo do que foi feito por mim: 

Para a aula de laboratório foi solicitado duas atividades a utilização do Copilot e a criação do recurso Azure OpenAI.

No Copilot, solicitei a geração de uma função recursiva em Java para calcular o fatorial de um número inteiro. O assistente retornou corretamente o código-fonte, que foi registrado nas imagens da atividade. Essa funcionalidade foi interessante para visualizar como a IA pode auxiliar na criação de trechos de código de forma rápida e precisa.

Dentro do portal do Azure, iniciei o processo de criação do recurso Azure OpenAI, que tem como objetivo explorar as ferramentas de IA do Azure, com foco especial nos filtros de conteúdo e na criação assistida por inteligência artificial.

Depois de confirmar que eu tinha acesso ao Azure AI Services, decidi avançar com a criação do recurso do Azure OpenAI para explorar os modelos de linguagem oferecidos.

Naveguei até a opção de criar um novo recurso no portal do Azure. Na seção de Noções básicas, selecionei minha assinatura, criei um grupo de recursos chamado RecursoIaEstudo, escolhi a região East US, defini um nome para a instância (implícito) e selecionei o tipo de preço Standard S0.

Na etapa de Rede, deixei habilitado o acesso para todas as redes, visando facilitar a configuração inicial. Pulei a parte de Tags. Por fim, revisei todas as configurações na aba “Examinar + Enviar” e iniciei a criação do recurso.

Após a implantação ser concluída, cliquei em "Ir para o recurso" e acessei o Azure OpenAI Studio. Dentro do estúdio, fui até o Playground de chat, onde fui informado de que era necessário implantar um modelo para começar. Escolhi o modelo gpt-35-turbo e fiz a implantação com sucesso, permitindo que eu pudesse interagir com ele diretamente no ambiente do Playground.

Como parte dos testes, tentei gerar uma função recursiva em Java usando o prompt: "Gere uma função recursiva em Java para calcular o fatorial de um número inteiro."
No entanto, recebi um erro do tipo OperationNotSupported, indicando que a operação de chatCompletion não era compatível com o modelo da forma como a solicitação foi feita. Isso provavelmente ocorreu porque a tarefa exigia o uso do modo "Completions" ou uma reformulação do prompt adequado ao modo "Chat".
