# Item API

## How to run
1. Clone project
2. Run mvn spring-boot:run
3. API endpoints:

### Endpoints
- GET /items` → Get all items
- GET /items/{id}` → Get item by ID
- POST /items` → Add new item
    - JSON body: `{ "id": 1, "name": "Laptop", "description": "Gaming Laptop" }

## Notes
- Data is stored in-memory (ArrayList), so it will reset on restart
- Input validation for name and description is implemented
