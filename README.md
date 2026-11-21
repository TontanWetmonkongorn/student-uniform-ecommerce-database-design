# Student Uniform E-Commerce Database Design

Academic team project for Database Systems and Applications. We designed a relational model for an online school uniform store. The deliverables were an entity–relationship diagram (ERD) and schema documentation. The database was not implemented or deployed.

## Entity–relationship diagram

![Entity–relationship diagram for the student uniform store](student-uniform-erd.png)

`ORDER_ITEM` links orders and products. Each line item records the quantity of a product in an order. The original diagram shows one-to-one relationships for orders and payments, and for products and stock records. Multiple payment attempts and inventory across multiple locations are outside the project scope.

**Credit:** Based on the original Database Systems and Applications team project.
