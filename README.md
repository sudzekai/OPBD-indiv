# Таблицы

#### 1. Clients
* ClientId (INT, PRIMARY KEY)
* FullName (VARCHAR)
* Phone (VARCHAR)
* Email (VARCHAR)

#### 2. Orders
* OrderId (INT, PK)
* ClientId (INT, FK)
* DueDate (DATE)ssss
* TotalPrice (DECIMAL)

#### 3. Items
* ItemId (INT, PK)
* ItemDescription (VARCHAR)

#### 4. Operations
* OperationId (INT, PK)
* ItemId (INT, FK)
* OperationType (VARCHAR)
* Price (DECIMAL)

#### 5. Tailors
* TailorId (INT, PK)
* FullName (VARCHAR)
* Phone (VARCHAR)
* Email (VARCHAR)

# Соответствие 3НФ
Соответствует 3НФ, так как каждый атрибут в таблицах содержит всего одно значение и зависит от первичного ключа.
