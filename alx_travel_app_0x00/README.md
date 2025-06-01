# Milestone 2: Creating Models, Serializers, and Seeders


## Objective

Define the database models, create serializers for API data representation, and implement a management command to seed the database.

---

## Instructions Summary

### 1. Duplicate Project  
- Duplicate the existing `alx_travel_app` project into a new project named `alx_travel_app_0x00`.

### 2. Create Models  
- In `listings/models.py`, define the following models:
  - **Listing**
  - **Booking**
  - **Review**  
Each model should include appropriate fields, relationships, and constraints as per the provided structure.

### 3. Set Up Serializers  
- Create serializers for the `Listing` and `Booking` models inside `listings/serializers.py` for API data representation.

### 4. Implement Seeders  
- Create a management command at `listings/management/commands/seed.py` to populate the database with sample `Listing` data.

### 5. Run Seed Command  
- Test the seeder by running the management command to populate the database with sample data.

---

## Repository Structure

alx_travel_app/
├── listings/
│   ├── models.py
│   ├── serializers.py
│   ├── management/
│   │   └── commands/
│   │       └── seed.py
│   └── README.md
├── alx_travel_app/
│   ├── settings.py
│   ├── urls.py
├── requirements.txt
├── .env
└── README.md