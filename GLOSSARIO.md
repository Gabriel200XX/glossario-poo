## Construtor
Construtor é responsável por criar o objeto em memória, ou seja, instanciar a classe que foi definida, um mecanismo que permite fazer inicializações no objeto assim que ele é instanciado, com a palavra reservada "new" no Java.  
Exemplo de Construtor:
``` Java
class Glossario {
    public Glossario() {
        System.out.println("Aqui está o construtor");
    }
}
```
## Instanciação
A instanciação é um processo por meio do qual se realiza a cópia de um objeto (classe) existente. Uma classe, a qual tem a função de determinar um tipo de dado, deve ser instanciada para que possamos utilizá-la.  
Exemplo de Instanciação:
``` Java
public class Instanciacao {
    private Glossario glossario = new Glossario();
}
```
## Encapsulamento
Um mecanismo da linguagem de programação para restringir o acesso a alguns componentes dos objetos, escondendo os dados de uma classe e tornando-os disponíveis somente através de métodos.
Exemplo de Encapsulamento com Getters/Setters:
## Getters/Setters
Estes métodos são seletores e modificadores dos atributos de sua classe. Consiste em os atributos de uma classe não poderem ser acessados diretamente.
Exemplo de Encapsulamento com Getters/Setters:
``` Java
public class Encapsulamento {
    private double pontuacao;
    
    public void setPontuacao(double pontuacao) {
        this.pontuacao = pontuacao;
    }
    
    public double getPontuacao() {
        return pontuacao;
    }
}
```
## Assinatura de método
## Sobrecarga de método
## Escopo de classe (Class scope)
## Escopo de objeto (Object scope)
## Palavras reservadas "public/private"
## Palavra reservada "new"
Operador utilizado para criar um objeto, instancia de uma classe.  
Exemplo de uso:
``` Java
public class New {
    private Glossario glossario = new Glossario();
    public Instaniciacao instanciacao = new Instanciacao();
}
```
## Palavra reservada "instanceof"
Operador usado para conferir se um objeto é de um certo tipo (classe, interface, enum, anotação), considerando toda a sua hierarquia.  
Exemplo de uso:
``` Java
public class InstanceOf {
    public boolean EhInstancia(Object obj) {
        boolean eh = false;
        if (obj instanceof InstanceOf) {
            eh = true;
        } else {
            eh = false;
        }
        return eh;
    }
}
```
## Palavra reservada "this"
## Palavra reservada "final" (Reserved word "final")
## Associação Simples
É quando uma classe possui um atributo vindo de outra classe. Atributo da Classe.
Símbolo UML "<-------->"
## Relacionamento de dependência (Dependency relationship)
Ocorre quando uma classe utiliza os serviços de outra classe. Ocorre no método da classe.
Símbolo UML "- - - - - >".
## Relacinamento de Agregação (Aggregation relationship)
É quando duas classes têm uma relação todo-parte, a parte consegue existir sem o todo. Atributo da Classe.
Símbolo UML "-------<>"
## Relacionamento de Composição (Composition relationship)
É quando duas classes têm uma todo-parte, a parte não consegue existir sem o todo. Atributo da Classe.
Símbolo UML "-------<//>"
