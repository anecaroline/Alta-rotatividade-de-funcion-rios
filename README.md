# Alta rotatividade de funcionários

Em um mundo corporativo em constante evolução, a gestão eficaz de recursos humanos é essencial para o sucesso de qualquer organização. No entanto, enfrentar desafios como alta rotatividade de funcionários, custos significativos associados a contratações e desligamentos, além da necessidade de retenção de conhecimento e desenvolvimento de talentos, tornou-se uma realidade cada vez mais comum para muitas empresas.

Para o departamento de Recursos Humanos, essas questões representam não apenas obstáculos, mas também oportunidades para criar soluções inovadoras que impulsionem o crescimento e a sustentabilidade organizacional. Por este motivo nós **Ane Caroline Ferreira Ribeiro** e **Gabriel Vilarinho** Cientistas de Dados embarcamos neste desafio para entender as dores da equipe de RH e fornecer soluções para a questão de alta rotatividade de fúncionarios.

O projeto foi desenvolvido para o 1º Desafio de Dados(Data Viking), utilizando uma base de dados real de uma empresa com alta rotatividade de funcionários. Realizamos a análise e exploração dos dados para obter insights e aplicamos um modelo de classificação para prever o churn.

##**O projeto garantiu o 3º lugar no desafio!**

Existem apenas 213 funcionários com a permanência maior que dois anos.A análise fornece alguns insights os motivos do desligamento dos funcionários. Principais pontos levantados:

-   Pontuação de Desempenho:Os funcionários desligados tendem a ter uma pontuação de desempenho superior à média, o que sugere que o desligamento não está relacionado ao baixo desempenho. Isso pode indicar que outros fatores estão contribuindo para o desligamento.
-   Satisfação com o Trabalho: A satisfação com o trabalho entre os funcionários desligados também é maior que a média. Isso pode indicar que o desligamento não está diretamente ligado à insatisfação com o trabalho.
-   Salários: É importante considerar que os funcionários com mais tempo de serviço geralmente recebem bônus, como triênio e quinquênio. Portanto, embora não haja uma diferença significativa nos salários entre os funcionários desligados e os que permanecem na empresa, pode haver discrepâncias nos benefícios adicionais oferecidos aos funcionários com mais tempo de serviço, o que pode influenciar nas decisões de desligamento.
-   Horas Extras: Os funcionários desligados tendem a trabalhar uma quantidade significativa de horas extras, o que pode indicar sobrecarga de trabalho. Isso pode ser um motivo para o desligamento, especialmente se não houver compensação adequada pelas horas extras trabalhadas.
-   Tempo de Serviço: Se 82% dos funcionários permanecem na empresa,indicando uma alta retenção.Porém possui uma taxa de rotatividade de cerca de 17.84% pode ser considerada moderada, indicando que uma parte significativa da força de trabalho está deixando a empresa em um determinado período de tempo. Isso pode sugerir alguns problemas de retenção de talentos ou insatisfação entre os funcionários.

----------

# Conclusão das análises

Buscando entender os motivos que levaram ao desligamento dos funcionários, observamos uma discrepância significativa nos dados entre funcionários ativos e inativos. Portanto, exploramos cada grupo individualmente, analisando as possíveis relações entre as variáveis disponíveis no dataset. A partir dessa análise, conseguimos tirar algumas conclusões:

### **Horas extras**

Foi observado que os funcionários desligados tendem a realizar uma quantidade significativa de horas extras, destacando assim a importância dessa variável nas relações presentes neste dataset. Ao analisar individualmente esta variável, notamos que, em termos gerais, a idade e o salário estão correlacionados com as horas extras. Isso indica que funcionários mais velhos tendem a trabalhar mais horas extras e receberem salários mais altos. No entanto, é provável que esses resultados estejam sendo influenciados por outliers (funcionários fora da curva). Portanto, decidimos separar os funcionários que realizaram um número elevado de horas extras para uma análise mais detalhada.

Observamos que a idade e o salário continuam fortemente relacionados com as horas extras, mas com uma diferença notável: funcionários mais velhos tendem a trabalhar menos horas extras agora. Além disso, as correlações entre os meses de serviço e a pontuação de desempenho aumentaram significativamente.

Notamos que os meses de serviço, a idade e a pontuação de desempenho estão inversamente relacionadas com a quantidade de horas extras trabalhadas.

**Pode haver alguns motivos para isso:**

Quando um funcionário inicia sua jornada na empresa, está se adaptando aos procedimentos internos e aos métodos de trabalho. Como todos os funcionários analisados ocupam cargos de nível sênior, as demandas são naturalmente mais elevadas. Essa fase inicial de adaptação, aliada às crescentes responsabilidades, muitas vezes requer um investimento de tempo adicional, além do horário regular, levando a um aumento no número de horas extras. No entanto, à medida que o funcionário se familiariza e ganha mais experiência com as práticas da empresa, tende a se tornar mais eficiente em suas tarefas, o que resulta em uma redução gradual na necessidade de horas extras e em um aumento em sua pontuação de desempenho.

### **Tempo de empresa**

**Ponto importante notado:**

82% dos funcionários permaneceram na empresa após 2 anos de serviço, refletindo uma forte retenção de colaboradores. Contudo, cerca de 18% dos funcionários deixaram a empresa nesse período, o que representa uma rotatividade significativa, indicando que parte da força de trabalho está se desligando da empresa em um determinado período de tempo. Foi observado que os salários variam consideravelmente ao longo do tempo, com pouca consideração pelo tempo de serviço ou implementação de bonificações, havendo colaboradores com menos tempo de casa recebendo muito mais que alguém com mais tempo. Essa falta de reconhecimento pode ter motivado muitos funcionários a buscar oportunidades de emprego em outras empresas.

### **Mesclando as duas análises**

Observa-se que o tempo de serviço do funcionário na empresa tem uma correlação bastante fraca com o desligamento. No entanto, quando analisado em conjunto com outras variáveis, pode-se observar uma possível relação.

**Funcionários com menos tempo na empresa** tendem a trabalhar mais horas extras, o que pode levá-los a se sentirem sobrecarregados e mal adaptados à empresa, resultando em um desempenho ruim e, eventualmente, na busca por outras oportunidades.

Por outro lado, **funcionários com mais tempo de casa**, devido à baixa variação salarial ao longo do tempo, podem buscar novas oportunidades de emprego. Esta estabilidade salarial pode levar à busca por empresas que ofereçam melhores perspectivas de crescimento profissional e remuneração.

### **Pontos observados:**

**Data de Desligamento:**

-   Devido à falta de dados, não podemos tirar conclusões definitivas sobre a data de desligamento dos funcionários.
    
-   Tudo indica que não houve um motivo específico para que todos os funcionários fossem demitidos no mesmo dia.
    

**Ausência da Informação sobre o Cargo:**

-   A ausência de informações sobre o cargo dos funcionários nos impede de avaliar se os salários estavam abaixo da média.
    
-   A falta dessa informação dificulta entender se o salário pode ter levado os funcionários a deixarem a empresa.