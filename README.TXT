## Componente: Camila Santiago, Victor Affonso e Yuri Pedro


Este projeto referente a disciplina de Topicos Especiais F, tem como o intuito fazer uma analise de uma grande quantidade de dados e de tipos diferentes.

Inicialmente recebemos um arquivo de onde extrair todos os dados, MontgomeryCountyCrime2013.csv, a qual extraimos para uma variavel nomeada crimes.

Apartir disso poderiamos resolver os problemas propostos no trabalho que seguem a baixo:

1 -Analyzing the times of crimes
    What day of the week are the most crimes committed on? (ie Monday, Tuesday, etc)
	O dia da semana com maior ocorrencia foi em uma terça feira.

    During what time of day are the most crimes committed?
	As 7:38:24 e 09:40:11

    During what month are the most crimes committed?
	Durante o mes de outubro

    During what time of day when crimes are committe?
	Manhã

    Were you surprised by your findings? 
	Sim

    Why do you think that crimes follow the patterns that they do?
	Pela manhã devem ocorrer por ser em horário onde as pessoas saem para trabalhar e ainda não dá para concluir nada em relação ao mês
    
    Take a look at the End Date / Time and Start Date / Time columns. Are these different from the Dispatch Date / Time column? 
	Sim, mas a diferença é minima entre Time and Start Date e Dispatch Date / Time e com relação a End Date / Time existe muitos Not a Number em vez do valor propiamente dito. Dessa forma não dá para tirar nenhuma conclusão.

    Would it be useful to use one or both of those columns to do this analysis instead?
	Não, uma vez que o Start Date parece muito com o Dispatch Date gerando um dado redudante e desnecessario enquanto End Date há muito dados Not a Number o que a torna uma variavel não confiavel

2 - Analyzing locations of crimes

    In what area did the most crimes occur? What physical locations (like cities) does this area correspond to?
		A maioria dos crimes ocorre na area de CEP 20910 localizado na cidade de Silver Spring.

    Which area has the highest number of crimes per capita? 
		The area that has the highest number of crimes per capta is:  SILVER SPRING  with crime rate per capta:  3640.3 /100,000.

3 - Analyzing types of crime

    Which crimes are the most common? Least common?
    O crime mais comum foi: 
    	['DRIVING UNDER THE INFLUENCE'] com  1710  ocorrências.
    Os crimes menos comuns foram: 
		LARCENY COIN MACH $50-$199 com  1  ocorrência.
		CDS-POSS INHALANT/GLUE/AEROSOL com  1  ocorrência.
		EMBEZZLE UNDER $300 com  1  ocorrência.
		ANIMAL OFFENSE - HOT CAR com  1  ocorrência.
		BURG FORCE-SCH/TIME UNK com  1  ocorrência.
		PARKING OFFENSES com  1  ocorrência.
		ROB OTHER WEAPON GAS/SVC  STA com  1  ocorrência.
		CDS IMPLMNT-BARBITUR/AMPHETAMI com  1  ocorrência.
		LARCENY COIN MACH OVER $200 com  1  ocorrência.
		CDS-MANU DRUG OVERDOSE NOT FATAL com  1  ocorrência.
		BURG FORCE - ATTEMPT - SCH/NIGHT com  1  ocorrência.
		ANIMAL NUISANCE/BARKING com  1  ocorrência.
		CDS-USE SYNTH DEMEROL/METADONE com  1  ocorrência.
		SUDDEN DEATH DROWNING com  1  ocorrência.
		AGG ASSLT BEAT/INJ ELDERLY com  1  ocorrência.
		TRAFFIC HAZARD com  1  ocorrência.
		ABANDONED AUTO com  1  ocorrência.
		VANDALISM GRAFFITI CHURCH/TEMP com  1  ocorrência.
		VANDALISM POSSESSION GRAFFITI MATERIAL com  1  ocorrência.
		HOMICIDE-OTHER com  1  ocorrência.
		SUICIDE-ATTEMPT-FIREARM com  1  ocorrência.
		BURG NO FORCE - SCH/TIME UNK com  1  ocorrência.
		ROB KNIFE/CUT - CONV. STORE com  1  ocorrência.
		ROB STN ARM - GAS/SVC STA com  1  ocorrência.
		AGG  ASSLT CUT/STAB P.O. com  1  ocorrência.
		BURG FORCE-SCH/DAY com  1  ocorrência.
		AGG ASSLT FIREARM P.O. com  1  ocorrência.
		AGG  ASSLT BEAT/INJ P.O. com  1  ocorrência.
		SANE COLLECTION NON-STRANGER com  1  ocorrência.
		AGG ASSLT OTHER WPN ON ELDERLY com  1  ocorrência.
		CDS RX FORGERY INHALANT/GLUE/AEROS com  1  ocorrência.
	
    Can you split the types of crimes manually into "Violent" (caused harm to others or involved weapons) and "Nonviolent" (mostly property crimes, like theft?
    What's the most common violent crime? The most common nonviolent?
		O crime mais violento que mais ocorre é:  ASSAULT & BATTERY - CITIZEN
		O crime não violento que mais ocorre é:  DRIVING UNDER THE INFLUENCE	

4 - Combine Analysis
    Where are the most violent crimes committed? How about nonviolent?
		The city with most violent crime is:  SILVER SPRING
		The city with most no violent crime is:  SILVER SPRING

    When are the most violent crimes committed? How about nonviolent?
		A data que mais ocorreu crimes violentos foi:  [('09/03/2013', 8)]
		A data que mais ocorreu crimes não violentos foi:  [('10/26/2013', 30)]

5 - Posing and answering your own questions
	Graphically identify areas where crimes most often occur.
		Nota-se que os crimes ocorrem mais entre os CEP's maiores que 20800.
	Top 5 crime occurrences per city:
		Bethesda:
         [('DRIVING UNDER THE INFLUENCE', 263), 
		('LARCENY FROM BUILDING OVER $200', 215), 
		('LARCENY FROM AUTO OVER $200', 186), 
		('POL INFORMATION', 141),
		 ('LOST PROPERTY', 139)]
			
		Outros:
		[('CDS-MANU-HALLUC/LSD/PCP/ETC', 1), 
		('LARCENY SHOPLIFTING $50 - $199', 1), 
		('FORGERY/CNTRFT-CHECKS', 1), 
		('LARCENY FROM AUTO $50 - $199', 1),
		 ('DRIVING UNDER THE INFLUENCE', 1)]

		Germantown:
		[('DRIVING UNDER THE INFLUENCE', 252), 
		('CDS-POSS MARIJUANA/HASHISH', 246), 
		('POL INFORMATION', 139), 
		('MENTAL TRANSPORT', 92), 
		('VANDALISM-MOTOR VEHICLE', 92)]

		Montgomery Village:
		[('DRIVING UNDER THE INFLUENCE', 295), 
		('CDS-POSS MARIJUANA/HASHISH', 267), 
		('MENTAL TRANSPORT', 189),
		('POL INFORMATION', 181),
		('VANDALISM-MOTOR VEHICLE', 137)]

		Rockville:
		[('POL INFORMATION', 270),
		('DRIVING UNDER THE INFLUENCE', 243), 
		('LOST PROPERTY', 157), 
		('CDS-POSS MARIJUANA/HASHISH', 145), 
		('LARCENY FROM AUTO OVER $200', 133)]

		Silver Spring:
		[('CDS-POSS MARIJUANA/HASHISH', 382), 
		('DRIVING UNDER THE INFLUENCE', 347), 
		('POL INFORMATION', 258), 
		('LARCENY FROM AUTO OVER $200', 257), 
		('LIQUOR - DRINK IN PUB OVER 21', 213)]

		Wheaton:
		[('DRIVING UNDER THE INFLUENCE', 308), 
		('CDS-POSS MARIJUANA/HASHISH', 223), 
		('POL INFORMATION', 200), 
		('MENTAL TRANSPORT', 193), 
		('LARCENY FROM BUILDING OVER $200', 154)]

		Takoma Park:
		[('CDS-POSS MARIJUANA/HASHISH', 4),
		 ('MENTAL TRANSPORT', 2), 
		('LIQUOR - FURNISHING LIQUOR UNDER 21', 2), 
		('CDS-SELL-MARIJUANA/HASHISH', 2), 
		('DISORDERLY CONDUCT', 2)]
	Graphically identify the most crimes occurring in each city.
		Conclui-se que a cidade com mais infrações é Silver Spring, cuja a infração mais comum está relacionado a maconha. 
