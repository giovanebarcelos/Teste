# teste

<details>

<summary>Tips for collapsed sections</summary>

### You can add a header

You can add text within a collapsed section. 

You can add an image or a code block, too.

```ruby
   puts "Hello World"
```

</details>

<details>

<summary>Tips for collapsed sections1</summary>

fdsafdasfasd
fdsafdas
fdas
fdsa

</details>

Here is a simple flow chart:
```plantuml
@startuml
actor Cliente 

usecase "Visualizar espetáculos" as VisualizarEspetaculos
usecase "Selecionar assentos" as SelecionarAssentos
usecase "Adicionar compras ao carrinho de compras" as AdicionarCompras
usecase "Finalizar a reserva" as FinalizarReserva
usecase "Efetuar pagamento" as EfetuarPagamento
usecase "Cadastrar-se" as CadastrarSe
usecase "Logar" as Logar
usecase "Confirmar pagamento" as ConfirmarPagamento
usecase "GerarBilhete" as GerarBilhete

Cliente --> VisualizarEspetaculos
Cliente --> SelecionarAssentos
Cliente --> AdicionarCompras
Cliente --> FinalizarReserva
Cliente --> EfetuarPagamento
Cliente --> CadastrarSe
Cliente --> Logar
Cliente --> ConfirmarPagamento
Cliente --> GerarBilhete

FinalizarReserva ..> AdicionarCompras : <<include>> 
FinalizarReserva ..> CadastrarSe : <<include>> 
FinalizarReserva ..> Logar : <<include>> 
EfetuarPagamento ..> FinalizarReserva : <<include>>
GerarBilhete ..> EfetuarPagamento : <<include>>

@enduml
```

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

```mermaid
mindmap
  root((mindmap))
    Origins
      Long history
      ::icon(fa fa-book)
      Popularisation
        British popular psychology author Tony Buzan
    Research
      On effectiveness<br/>and features
      On Automatic creation
        Uses
            Creative techniques
            Strategic planning
            Argument mapping
    Tools
      Pen and paper
      Mermaid
```

```
Bloco qualquer
```

```
Outro Bloco 2
```
