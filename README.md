# Orders

<details open="">

 <summary><b>Database</b></summary>
  
  ```mermaid

classDiagram
    class Order {
        +uuid id
        +timestamp CreatedAt
        +text Status
        +text Creator
          
    }

    class OrderProductItem {
        +uuid id
        +uuid OrderId
        
    }
    
    OrderProductItem <| -- Order

```
  
</details>
