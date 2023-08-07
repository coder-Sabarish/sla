Class Diagram:
Class Diagram – The class diagram is the most extensively used UML diagram. It serves as the foundation for all object-oriented software systems. Class diagrams are used to depict a system’s static structure by displaying its classes, methods, and properties. Class diagrams also assist us in determining the links among various classes or objects. 
1. customer class is created, with six customer data to collect information to the shopping system
2. product class is created, with five data's that specify the product name, product color, product id, product price and its description
3. Order class is specfied with unique details about the product and customer 
4. The cart contains the number of the items, and the customer id
5. The payment class is for authentication with the customer id
6. The Delivery of the product is tracked by the product id and the product details
7. The feedback is received based on the quality and quantity from the user
8. The return class is triggered only if the product received is damaged, or variant in the product color, Product quality

UseCase Diagram:
Use Case Diagram are used to describe the functionality of a system or a component of a system. They’re frequently utilized to depict a system’s functional requirements and interactions with external agents (actors). A use case is a diagram that depicts the various contexts in which a system can be applied. Use case diagrams provide us a high-level overview of what a system or element of a system performs without diving into the nitty-gritty of implementation.
1. The customer would have the access to , "Place order", "Make Payment", "Add to cart", "Browse Products"
2. The Product owner woukd get access to "Browse the products", "Check stock of the products"

Sequence Diagram:
Sequence Diagram simply depicts the interactions between items in a series, i.e. the order in which these interactions take place. A sequence diagram can also be referred to as an event diagram or an event scenario. Sequence diagrams show how and in what order the components of a system work together. Businesspeople and software engineers frequently use these diagrams to document and understand the needs of new and current systems. 
1. The Customer has to create an order of their wish.
2. If the customer's need is not understandable, it is returned to reenter the specific needs
3. For eacg order specify the product name, product quantity.
4. The system fill check for the availability of the product mentioned and the required stock is in stock
5. If the stock is available, the product is returned 
6. Then , the order gets confirmed from the customer
7. Once the order gets confirmed , the payment is initiated.
8. The Authentication process starts to verify the Payment sender and the account 
9. Once the authentication is completed, the order is placed successfully