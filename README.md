# Examen T1 De Lenguaje de Programación II

||**Datos del Estudiante**|
|-|-|
|Nombre: | Jesús Eduardo Rojas Alarcón|
|Ciclo: | IV |
|Carrera: | Computación e Informática|
|Sede: |Trujillo|

## Carácterísticas del examen
- Desarrollar un mantenedor para la tabla Subject con JPA y subirlo a github.
  - <img width="209" alt="image" src="https://github.com/user-attachments/assets/870ba6e8-6548-46ab-8725-27be411e3b1c">

## Desarrollo del examen
- Primero se creo el proyecto con Spring Initializr
  - <img width="1382" alt="image" src="https://github.com/user-attachments/assets/ed1bf960-9f73-4e62-86d9-9183678d910b">

- Después se creo descomprimió el proyecto y se añadió la configuración para poder conectarse con la base de datos en mysql.
  - <img width="988" alt="image" src="https://github.com/user-attachments/assets/2d9d86a6-c117-4259-87ca-107d5effc692">

- Luego se creó la entidad Subject para poder mapear los datos en la base de datos con JPA.
  - <img width="993" alt="image" src="https://github.com/user-attachments/assets/e6161a77-9ae6-4e57-8b4e-ba211fc6c98e">

- Luego se creó la interfaz RepositorySubject.java que extiende de JpaRepository.
  - <img width="997" alt="image" src="https://github.com/user-attachments/assets/abc580a7-d213-412f-9886-299147eb8be7">

- Luego se creó el Servicio SubjectService.java para poder manejar las distintas operacion de un CRUD
  - <img width="979" alt="image" src="https://github.com/user-attachments/assets/1d68f0f6-d446-4fc9-ae64-dc551b6bf30c">


- Luego se creó el controlador de subject para poder manejar las peticiones HTTP que se hicieran a la ruta de "/subjects"
  - <img width="981" alt="image" src="https://github.com/user-attachments/assets/7aed1fb2-504a-43f3-9be4-ec4bbd1618de">
  - <img width="981" alt="image" src="https://github.com/user-attachments/assets/de9ae27b-5c4f-4f15-82c3-e79f692f7c98">

- Finalmente se ejecutó el programa SubjectManagementApplication.java
  - <img width="1440" alt="image" src="https://github.com/user-attachments/assets/88bbdfa2-adcd-49b7-91e0-a0fb18adb821">

## Pruebas de las peticiones HTTP con Postman
- **Post "/subjects"**
  - <img width="1392" alt="image" src="https://github.com/user-attachments/assets/b3e30c39-e62f-4c6a-ac75-7abfcada4d35">
  - <img width="1392" alt="image" src="https://github.com/user-attachments/assets/4b766a57-2a23-4166-a31c-b311631c1d76">

- **Get "/subjects"**
  - <img width="1392" alt="image" src="https://github.com/user-attachments/assets/d9a89ae6-a8f9-47f3-8d4c-6e6835acc211">

- **Get "/subjects/{id}"**
  - <img width="1392" alt="image" src="https://github.com/user-attachments/assets/2c77b5c6-7e65-4cd8-9ad4-919bca040eae">
  - <img width="1392" alt="image" src="https://github.com/user-attachments/assets/3480ebc0-dd2d-4809-81b0-905cb1f15cfa">
  - <img width="1392" alt="image" src="https://github.com/user-attachments/assets/158f916e-8ba8-4122-88be-10cb7d50b491">

- **Put "/subjects/2"**
  - <img width="1392" alt="image" src="https://github.com/user-attachments/assets/4065310a-2337-4003-851b-241f309e44b5">
  - <img width="1392" alt="image" src="https://github.com/user-attachments/assets/1b7afe34-a2fe-43f2-b652-bf8131f8356f">
- **Delete "subjects/2"**
  - <img width="1392" alt="image" src="https://github.com/user-attachments/assets/1bbedafe-e197-4fa6-828c-9bb49ad1a547">
  - <img width="1392" alt="image" src="https://github.com/user-attachments/assets/0b19eb29-7a65-48e8-8d95-b9314f4f107a">






