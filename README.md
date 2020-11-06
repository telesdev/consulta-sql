# consulta-sql

Resolução da questão 3:

`
SELECT c.* FROM Customers c JOIN Orders o on (c.CustomerID = o.CustomerID) JOIN OrderDetails od on (o.OrderID = od.OrderID) JOIN Products p on (od.ProductId = p.ProductID) JOIN Suppliers s on (p.SupplierID = s.SupplierID) WHERE s.Country = 'Brazil'
`
