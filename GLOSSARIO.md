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
## Encapsulamento

## Palavra reservada "this"
## Getters/Setters
## Palavras reservadas "public/private"
## Assinatura de método
## Sobrecarga de método
## Escopo de classe (Class scope)
## Escopo de objeto (Object scope)
## Palavra reservada "final" (Reserved word "final")
## Relacionamento de dependência (Dependency relationship)
## Relacinamento de Agregação (Aggregation relationship)
## Relacionamento de Composição (Composition relationship)