Pet Class
Overview
The "Pet" class is a Java class designed to represent individual pets in a boarding facility. It encapsulates various attributes of pets, such as type, name, age, available spaces for dogs and cats, days of stay, and the amount due for boarding.

Class Structure
The class is structured with private fields representing different attributes of a pet. It includes two constructors, one with default values and another with parameters for custom initialization. The class also provides getters and setters for each field to allow access and modification.

Fields
petType (String): Represents the type of pet (e.g., dog or cat).
petName (String): Stores the name of the pet.
petAge (int): Represents the age of the pet.
dogSpaces (int): Indicates the available spaces for dogs in the boarding facility.
catSpaces (int): Indicates the available spaces for cats in the boarding facility.
daysStay (int): Stores the number of days the pet is expected to stay.
amountDue (double): Represents the amount due for the boarding services.
Constructors
Default Constructor: Initializes the fields with default values. This constructor can be used when creating a pet object without providing specific values.

Parameterized Constructor: Accepts parameters for each field, allowing for custom initialization of a pet object.

Getters and Setters
Each field has a corresponding getter and setter method, enabling external classes to access and modify the values of the pet attributes.

Usage
To use the "Pet" class, create instances of it in your main program and set the values using the provided setters. You can then use the getters to retrieve information about each pet.

java
Copy code
// Example Usage
Pet myPet = new Pet();
myPet.setPetType("Dog");
myPet.setPetName("Buddy");
myPet.setPetAge(3);
// Set other attributes as needed
Additional Methods
The class can be extended with additional methods specific to pet management, such as methods to calculate the total amount due, check the availability of spaces, etc.

java
Copy code
// Additional Method Example
public double calculateTotalAmountDue() {
    // Implement the logic to calculate the total amount due
    return daysStay * amountDue;
}
Feel free to customize the class to suit the specific requirements of your pet boarding system.
