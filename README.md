# Hello World feito com Kotlin






### Notas feitas durante a aula

- Criar em 'Empty Activity', NÃO CRIAR em 'No Activity'

- .java == .kt 

- ':' = 'extends' em Java

- public é implícito, não é necessário escrever public ao criar classes.

- fun funcaoTeste(param1: Objeto, param2: Objeto): Retorno
	* fun = função
	* param: Obj = parâmetro extends de Obj (equivalente ao 'Object param' em Java)
	* : Retorno = Classe que será retornada (int, String, e etc)

- O @Override em Java agora é escrito dentro da função:
	* override fun funcao123()


## Aula 3/3
- Inner padding é usado para não se preocupar com modelos de celulares que possuem câmera "dentro" da tela, adicionando um padding automático para o conteúdo e textos aparecerem abaixo da câmera.

- modifier: Modifier = Modifier (se nenhum argumento for inserido para a var modifier, o programa assumirá que é da classe Modifier).
```
fun LoginScreen(modifier: Modifier = Modifier)
```

- @Composable -> Serve para mostrar ao programa que a função ali é para ser composta na construção da tela, é que nem avisar para alguém que está construindo com legos que aquela peça (função) é para ser usada lá.

- unidade de medida 'dp' -> Serve para que as telas tenham uma consistência na apresentação dos objetos (semelhante ao vw e vh no css)

- 
