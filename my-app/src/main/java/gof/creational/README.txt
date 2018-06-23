Abstract Factory

When to use:
-- To support families of related or dependent objects.
-- To encapsulate platform dependencies to make an application portable
-- To prevent client code from using the 'new' operator.
-- To easily swap the underlying platform with minimal changes.

Intent or Purpose:
Provide an interface for creating families of related or dependent objects without specifying their 
concrete classes

Components:

1. An abstract Factory class(public)
2. Factory implementations for various families (protected)
3. Interfaces for various products (public)
4. Set of product implementations for various families (protected)
