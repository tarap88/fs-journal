# A bit more CSharp and SQL
1. What does ***inheritance*** accomplish for us in C#?

  > | It allows you to create classes that reuse and modify other classes. |

2. How does ***member inheritance*** work in C#? Does a `Class` inherit all members of the base `Class`?

  > | The base whose properties are inherited by others; however it does not inherit all members of the base class.  |

3. How does ***accessibility*** affect inheritance?

  > | Public and protected members are always inherited and accessible in derived classes.
Private members are not inherited.
Internal and protected internal members are inherited but may have limitations based on the assembly.|

4. What is the difference between a `PRIMARY KEY` and a `FOREIGN KEY`

  > | Primary Key: Uniquely identifies each row in its own table.
      Foreign Key: Links rows between two tables.|

5. What is an ***alias***?

  > | An alias is just a different name for something, making it easier to refer to or understand, i.e Namespace|

6. Demonstrate how you would query a join statement that would get all of a doctors patients from the following collections:

  ```SQL
  CREATE TABLE doctors (
    id INT NOT NULL AUTO_INCREMENT,
    -- CODE OMITTED
    PRIMARY KEY (id)
  )

  CREATE TABLE patients (
    id INT NOT NULL AUTO_INCREMENT,
    -- CODE OMITTED
    PRIMARY KEY (id)
  )

  CREATE TABLE patient_doctors (
    id INT NOT NULL AUTO_INCREMENT,
    doctorId INT NOT NULL,
    patientId INT NOT NULL,

    FOREIGN KEY (doctorId)
      REFERENCES doctors(id),
    FOREIGN KEY (patientId)
      REFERENCES patients(id),
  )


  > | 
  SELECT doctors.*, patients.*
FROM doctors
JOIN patient_doctors ON doctors.id = patient_doctors.doctorId
JOIN patients ON patients.id = patient_doctors.patientId;|
