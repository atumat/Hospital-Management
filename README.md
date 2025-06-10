<h1>Hospital Management System</h1>

Hospital Management System is a system enabling hospitals to manage information and data related to all aspects of healthcare – processes, providers, patients, and more. It is designed with a strong emphasis on Object-Oriented Programming (OOP) principles, leveraging them to create a modular, scalable, and maintainable code.

 
 <p align="center">
<img src="https://img.shields.io/badge/made%20by%20-Aarti-blue">
<img src="https://img.shields.io/badge/C++-orange">
<img src="https://img.shields.io/badge/contributions-Welcome-brightgreen">
<img src="https://badges.frapsoft.com/os/v1/open-source.svg?v=103">
</p>




 <p align="center">
  <img width="460" height="300"src="https://user-images.githubusercontent.com/116307514/218166840-350e6312-48dd-4b74-897f-048048f99982.png">
</p>
 
 

<h2 >Object Oriented Programming </h2>
 <p align="justify">
 Object-oriented programming is essentially a concept or technique for computer programming that models software architecture around data or objects rather than functions and logic.A data field is referred to as an object if it has distinct characteristics and behaviour. In OOP, everything is categorised as objects.
</p>
<p>

Among developers, it is the most often used programming paradigm. Large, complicated, and actively updated or maintained programmes work well with it. It provides fundamental ideas like abstraction, inheritance, polymorphism, and encapsulation, which make programme creation and maintenance easier. These fundamental ideas define OOP.
  
</p>



User-defined data types called classes serve as the building blocks for specific objects, properties, and methods.
 Objects are instances of a class that were generated using data that was defined. Objects can be an abstract concept or a real-world thing. 

 

Classes and Objects:

Classes serve as blueprints for real-world entities within the hospital environment. Examples include Patient, Doctor, Nurse, Appointment, Department, Bill, Medicine, etc.
Objects are instances of these classes, representing actual patients, doctors, appointments, and so on, each with their unique data and behaviors.
Example: A Patient object might have attributes like name, patientID, age, medicalHistory, and methods like getsAdmitted(), undergoesTreatment(). A Doctor object might have name, doctorID, specialization, workingHours, and methods like checksPatient(), prescribesMedication().
Encapsulation:

Data and the methods that operate on that data are bundled together within classes. This ensures data integrity by preventing direct external access to an object's internal state.
Access to attributes is typically controlled through public methods (getters and setters), allowing for validation and controlled modification.
Example: A Patient object's medicalHistory might be private, only accessible and modifiable through methods like addMedicalRecord() or getMedicalHistory(), ensuring that medical data is handled securely and consistently.
Inheritance:

Common attributes and behaviors are extracted into base (parent) classes, and specialized classes (child classes) inherit from them. This promotes code reusability and establishes a clear hierarchy.
Example:
A Person base class could have common attributes like name, age, gender, address.
Patient, Doctor, and Staff could inherit from Person, each adding their specific attributes and methods (e.g., Patient adds patientID, medicalHistory; Doctor adds specialization, doctorID).
Polymorphism:

"Many forms" - allows objects of different classes to be treated as objects of a common superclass. This enables flexible and extensible code.
Method Overriding: Child classes provide their specific implementation for a method already defined in their parent class.
Example: A Person class might have a generic displayDetails() method. Patient, Doctor, and Staff classes could override this method to display details relevant to their specific roles (e.g., Patient displays patientID and medicalHistory, Doctor displays specialization and workingHours).
Virtual Functions (in C++ context): Used to achieve runtime polymorphism, allowing the correct method implementation to be called based on the actual object type at runtime, even when accessed through a base class pointer or reference.


Focuses on showing only the essential information and hiding the complex implementation details. This is achieved through abstract classes and interfaces.
Example: An abstract User class might define common operations like login() and logout(), without specifying how each specific type of user (Admin, Doctor, Patient) implements these. The concrete Admin, Doctor, and Patient classes would then provide their specific login() implementations.


<h2> Exception Handling </h3>
<p> Exception handling in C++ consist of three keywords: try, throw and catch: <br> </p>
<ol type="I">
    <li> The try statement allows you to define a block of code to be tested for errors while it is being executed. </a></li>
    <li> The throw keyword throws an exception when a problem is detected, which lets us create a custom error. </a></li>
    <li> The catch statement allows you to define a block of code to be executed, if an error occurs in the try block. </a></li>
 












