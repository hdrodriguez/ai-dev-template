# System Architecture

The project follows a layered architecture.

## Layers

Views  
Services  
Models  

---

## Rules

Business logic must live in services.

Views must remain thin.

Models represent persistence.

---

## Multi-tenancy

All models must include:

tenant_id