BOSSMAN EMMANUEL
FOE.21.006.019.24
# GENERIC-PROGRAMMING-Smart-Warehouse-Inventory-System
Project Overview
A logistics company warehouse system using Python generics. Instead of creating separate classes for each item category, we use one reusable generic `Inventory[T]` class that works with any data type.

## Task Requirements
1. Create generic class `Inventory[T]`
2. Store item of any type
3. Retrieve stored items
4. Display item's type and value
5. Demonstrate with `str`, `int`, `float`, `list`
6. Extend class to maintain multiple items with type consistency

## Implementation
- **Language**: Python 3.9+
- **Core Concept**: `typing.Generic` and `TypeVar` for type-safe generic programming
- **File**: `generic_warehouse_inventory_system.py`
- **Type Safety**: Each inventory instance is locked to one type `T`
