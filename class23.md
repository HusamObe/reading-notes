# Permissions & Postgresql

## Question 1: DRF Permissions

### Purpose of DRF Permissions:
DRF Permissions in Django Rest Framework (DRF) are used to control access to API views and resources. They determine whether a user is allowed to perform specific actions on certain resources based on authentication, user roles, and custom logic.

### Components of DRF Permissions:
1. `BasePermission`: Abstract class serving as the base for custom permission classes.
2. Built-in Permissions: Pre-defined classes such as `IsAuthenticated`, `IsAdminUser`, etc.
3. Custom Permissions: User-defined permission classes by subclassing `BasePermission`.

### Role in Securing an API:
- Access Control: Permissions limit access to specific views, actions, or objects based on user roles and ownership.
- Data Protection: Permissions at the object level ensure users interact only with relevant data.
- User Authorization: Permissions authorize users based on their roles and privileges.
- API Security: Permissions add an extra layer of security by controlling access and protecting sensitive resources.


## Question 2: DRF Generic Views

### Role of DRF Generic Views:
DRF Generic Views simplify building RESTful APIs by providing pre-built views for common CRUD operations on resources. They work with Django's model system, eliminating boilerplate code and promoting code reusability.

### Types of DRF Generic Views:
1. `ListAPIView`: Read-only view for listing a collection of resources.
2. `CreateAPIView`: View for creating a new resource.
3. `RetrieveAPIView`: Read-only view for retrieving a single resource by its primary key.
4. `UpdateAPIView`: View for updating a resource by its primary key.
5. `DestroyAPIView`: View for deleting a resource by its primary key.
6. Combining Views: Various combinations for different needs (e.g., `ListCreateAPIView`, `RetrieveUpdateAPIView`, etc.).

### Example Usage for a 'Book' Model:
1. Define the `Book` model.
2. Create a serializer for `Book` instances.
3. Create views using DRF Generic Views (`ListCreateAPIView` and `RetrieveUpdateDestroyAPIView`).
4. Define URL patterns for the views.


## Question 3: SQL SELECT Statement

### Purpose of SELECT Statement:
The `SELECT` statement in SQL is used to retrieve data from a database table. It allows specifying columns to retrieve and applying conditions to filter data based on criteria.

### Retrieving All Columns from 'employees' Table:
To retrieve all columns from a table called 'employees', use the `SELECT * FROM employees;` statement. The asterisk (*) wildcard character selects all columns, returning all data stored in each column of the 'employees' table.
