# scaling-system


## Network Working Group               Guilherme D.Sanches/Felipe Versiane
## Request for Comments: 2023	IFG/W3C
## Category: Standards Track	outubro 2023

# EMAILGSFV- 1.0



# Status 

Este documento define o protocolo EMAILGSFV para a comunidade do EMAILGSFV e convida à discussão e sugestões de aprimoramento. Consulte a versão atual das "Normas Oficiais do Protocolo EMAILGSFV" para acompanhar o estado de padronização e o status deste protocolo. A distribuição deste memorando é ampla e não possui restrições.



# Abstract

Este RFC descreve o protocolo EMAILGSFV, uma linguagem de formatação de textos para emails. O protocolo EMAILGSFV foi desenvolvido como parte de um projeto acadêmico de redes com o objetivo de permitir a formatação de emails independentes de plataforma, fornecendo uma estrutura padronizada para a criação de emails. O RFC descreve a sintaxe, os comandos e as diretrizes para o uso da marcação EMAILGSFV.


# Sumario 
1.	Introdução	2
2.	Padrão EMAILGSFV	2
2.1	Colchete Simples	2
3.	EMAILGSFV Comandos	3
3.1	comandos	4
3.2	Exemplo EMAILGSFV Documentação	4
4.	Comandos Documentação	3
5.	Exemplo EMAILGSFV Documentação	5
6.	Conclusão	8

	 
## 1.	Introdução

O protocolo EMAILGSFV (Email Generic Standard Format Version) é uma linguagem de formatação de emails projetada para simplificar a formatação de mensagens de email, fornecendo uma estrutura padronizada e flexível para a criação de emails independentes de plataforma.

Desde a sua introdução, o EMAILGSFV tem se destacado como uma solução eficaz para a formatação de emails, abordando a crescente necessidade de estabelecer padrões eficazes para garantir que a comunicação por email seja eficaz, consistente e acessível.

Este RFC busca definir o protocolo EMAILGSFV, fornecendo uma descrição detalhada de sua sintaxe, comandos disponíveis e diretrizes para o uso adequado. Além disso, ele estabelece o EMAILGSFV como uma linguagem padronizada para formatação de emails, contribuindo para a interoperabilidade e a facilidade de uso em um cenário diversificado de plataformas e clientes de email.

O protocolo EMAILGSFV está alinhado com os padrões de formatação de emails existentes, enquanto introduz uma abordagem flexível e eficaz para atender às necessidades em constante evolução dos usuários de email.

Este RFC é um documento de referência vivo e sujeito a atualizações à medida que o protocolo EMAILGSFV continua a evoluir.



## 2.	Padrão EMAILGSFV

O protocolo EMAILGSFV segue um padrão de escrita simples e uniforme, projetado para garantir a clareza e a facilidade de uso na criação de emails formatados. O padrão de escrita do EMAILGSFV é definido pelos seguintes princípios:

## 2.1 colchete Simples
		
Os comandos no EMAILGSFV seguem uma notação única para garantir clareza e simplicidade na formatação de e-mails. As chaves simples([]) são usadas para todos os comandos de estrutura, como por exemplo, [negrito], [itálico] e [vermelho].

Além disso, com exceção dos comandos quebralinha, divisória e item (que não precisam de um segundo comando para o fechamento).Todos os outros comandos usam o padra de um comando de abertura a mensagem a ser editada e o comando de fechamento como por exemplo: [negrito]mensagem em [negrito;]




## 3.	EMAILGSFV Comandos

Os comandos do EMAILGSFV são descritos por palavras-chave descritivas. Cada comando identifica a formatação a ser aplicada ao texto formatado.
É essencial que o comando seja escrito exatamente como especificado para garantir a aplicação correta da formatação.


## 4.	 Comandos Documentação
	 	
	4.1 Comando [to]
		
O comando {to} permite que o remetente insira o nome do destinatário na mensagem de Email.

	
## 4.2 Comando [titulo]
		
O comando {titulo } é usado para definir o assunto do Email, fornecendo um título claro para a mensagem.

## 4.3 Comando[body]
O comando body e usado para conter todo o corpo da mensagem onde se tem a maioria dos comandos do protocolo.

	
## 4.4 Comando [Negrito]
	
O comando {Negrito} aplica formatação de texto em negrito ao texto inserido entre as chaves mais externas. 

		
## 4.5 Comando [Italico]

O comando {Italico} é usado para aplicar formatação de texto em itálico ao conteúdo definido entre as chaves externas.

	
## 4.6 Comando [Sublinhado]

O comando {Sublinhado} aplica sublinhado ao texto inserido entre as chaves mais externas.


## 4.7 Comando [tachado]
O coamndo [tachado]basicamente risca a palavra ao meio.

	
## 4.8 Comando [citacao]

O comando [citação] permite citar algum trecho de texto.



## 4.9 Comando [divisoria]

O comando [divisoria] é usado para separar blocos de texto usando um risco.

## 4.10 Comando [Lista]

O comando [Lista] é usado para criar listas de itens com marcadores de ponto nesse comando cada item e separado pelo comando [item].

## 4.11 Comando [quebralinha]

O comando [quebralinha] é utilizado para quebrar uma linha assim como o ‘\n’ em C.

## 4.12 Comando [Link]

O comando [Link] é usado para inserir links em textos, permitindo a vinculação a recursos externos, como sites da web.

## 4.13 Comando [branco]

O comando [branco] converte o texto para a cor branca.

## 4.14 Comando [roxa]

O comando [roxa] converte o texto para a cor roxa.

	
## 4.15 Comando [vermelho]

O comando [vermelho] converte o texto para a cor vermelho.

## 4.16 Comando [verde]

O comando [verde] converte o texto para a cor verde.

## 4.17 Comando [azul]

O comando [azul] converte o texto para a cor azul.

	
## 4.18 Comando [amarelo]

O comando [amarelo] converte o texto para a cor amarelo.

## 4.19 Comando[ciano]
		
O comando [ciano] converte o texto para a cor ciano.

## 4.20 Comando [cinzaclaro]
	
O comando [cinzaclaro] converte o texto para a cor cinza claro.

## 4.21 Comando {Data}

O comando {Data} insere a data atual no Email.


## 4.22 Comando {Hora}

O comando {Hora} insere a hora atual no Email.

## 4.23 Comando [assinatura]
		
O comando [assinatura] assina o email com seu usuário.




## 5.	Exemplo EMAILGSFV Documentação

No contexto do padrão EMAILGSFV, existem duas abordagens para declarar o texto que deve ser formatado, delimitado pelas chaves externas.

## 5.1 Declaração de comados de edição de texto

A declaração de edição de texto é a abordagem mais direta e amplamente utilizada na maioria dos comandos do EMAILGSFV. Ela permite a aplicação de formatação ao texto de maneira simples e eficaz.

Exemplo de código:


 		[Comando]Mensagem que ficara em negrito[Comando;]



## 5.2 Declaração de comando de data
	
Na declaração de data se segue o padrão DD/MM/AA em que D representa dia, M        representa mês e A o ano.
     
     Exemplo de Código:
	
		
		[data]01/02/23[data;]


	
## 5.3 Declaração de Horas
	
No comando ‘Hora’ se usa o seguinte padrão do exemplo

     Exemplo de Código:


	[hora]15:20[hora;]


## 5.4 Declaração de quebra de linha e diivsoria
Os comandos de quebra de linha e de divisória são usados apenas com um comando sem a necessidade de fechar o comando usando o ponto e virgula.


		[divisoria]

		[qubralinha]



## 5.5 Declaração de lista 

A declaração de listas e feita com cada elemento estando dentro do comando estando separados por espaços.

Exemplo de Código:


	[lista][item]Elemento 1 [item]Elemento 2 [lista;]
	


## 5.6 Declaração de link

A declaração de  link e bem simples funciona como a declaração de texto porem com algum link.

Exemplo de Código:



	[Link]www.site.com[link;]
	
## 6.	Conclusão 

Este RFC estabelece as bases para a compreensão do protocolo EMAILGSFV, sua sintaxe, comandos e diretrizes de uso. À medida que o EMAILGSFV evolui e novos recursos são desenvolvidos, este documento servirá como referência e guia para os usuários, desenvolvedores e pesquisadores interessados em melhorar a comunicação por Email.

