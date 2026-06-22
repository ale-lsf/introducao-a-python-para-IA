1\) O que é Machine Learning? 

Machine Learning é a área da Inteligência Artificial onde o computador aprende a partir de exemplos e demonstrações.



2\) Diferença entre X e Y:

X representa as entradas e atributos (feature), e Y representa o rótulo, alvo ou valor que desejamos procurar (target).



3\) O que a linha "import panda as pd" faz?

Determina que o panda começará a ser chamado de "pd".



4\) O que é um dataframe?

É a estrutura principal do pandas parecido com uma planilha do Excel.



5\) O que a linha "modelo.fit(X, Y)" faz?

É o comando responsável pelo treinamento do modelo. Ele analisa os dados históricos fornecidos para "aprender" padrões e fazer previsões futuras.





**from sklearn.linear\_model import LogisticRegression**



**x = X = \[\[1], \[2], \[3], \[4], \[5], \[6]]** 

**y = \[0, 0, 0, 1, 1, 1]** 



**modelo = LogisticRegression() # cria o modelo**



**modelo.fit(X, y) # treina o modelo**



**previsao = modelo.predict(\[\[5]]) # faz a previsão**



**print("Resultado:", previsao\[0]) # imprime o resultado**



**if previsao\[0] == 1:**

&#x20;   **print("O aluno foi aprovado.")** 

**else:**

&#x20;   **print("O aluno foi reprovado.")**





