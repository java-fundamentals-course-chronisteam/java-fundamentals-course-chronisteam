# java-fundamentals-course-chronisteam

## Resumen del Curso
Este curso introductorio de 1 hora enseña a estudiantes de secundaria los conceptos básicos de Programación orientada a objetos (POO), utilizando exclusivamente herramientas en línea como Replit y JDoodle.
No requiere experiencia previa en programación ni instalación de software adicional, solo un navegador web.

Los estudiantes aprenderán qué son las clases y los objetos, cómo definir atributos (datos) y métodos (acciones), y cómo modelar situaciones de la vida real usando POO. Al final crearán un pequeño programa orientado a objetos.

**Duración total:** 60 minutos  
**Público objetivo:** Estudiantes de 12 a 17 años sin experiencia previa en programación  
**Prerrequisitos:** Ninguno  
**Herramientas necesarias:** Navegador web   
**Repositorio de código fuente:** https://github.com/java-fundamentals-course-chronisteam/java-fundamentals-course-chronisteam

---

## Secuencia de la Lección

### Lección 1: Introducción a Java y la programación, sintaxis básica: variables, tipos de datos. (- minutos)
**Responsable:**

- **Descripción:**

- **Editor online:** https://www.youtube.com/watch?v=example-link1

- **Consejos clave:** 

---

### Lección 2: Operadores y estructuras de control, métodos, funciones y parámetros. (- minutos)  
**Responsable:**

- **Descripción:**

- **Enlace del video:** https://www.youtube.com/watch?v=example-link1

- **Editor online:**  (link del codigo que desarrollaste)

- **Consejos clave:** 

- **Código inicial utilizado en la exposición:**
```
-
```

- **Práctica**: [Clic para programar]( https://replit.com/~ )

---

### Lección 3: Entrada/salida con Scanner,Arreglos simples o cadenas. (- minutos)  
**Responsable:**

- **Descripción:**

- **Enlace del video:** https://www.youtube.com/watch?v=example-link1

- **Editor online:**  (link del codigo que desarrollaste)

- **Consejos clave:** 

- **Código inicial utilizado en la exposición:**
```
-
```

- **Práctica**: [Clic para programar]( https://replit.com/~ )

---

### Lección 4: Introducción a POO (clases, objetos, constructores), principios básicos: encapsulación, instanciación. (12 minutos)  
**Responsable: Schneider Carlos Alberto Delgado Carrasco**

- **Descripción:**: En esta lección se aplica la idea de clase como *molde* y objeto como *ejemplar real*. Creamos la clase `Student` con atributos, luego instanciamos objetos en `Main`. Agregamos un **constructor** para iniciar los datos en una sola línea y aplicamos **encapsulación** con `private`, getters y un setter con validación para proteger la edad.

- **Enlace del video:** https://www.youtube.com/watch?v=-_Zb4Olarh8

- **Editor online:** [Replit - POO Básico](https://replit.com/@schneider0104dc/Java?v=1)

- **Consejos clave:** 
  - Una clase es un molde; un objeto es un ejemplar de ese molde.
  - Podemos agrupar datos y comportamiento en una sola unidad.
  - Encapsulación ayuda a proteger los datos.

- **Código inicial utilizado en la exposición:**

Student.java
```
// CREACIÓN DE UNA CLASE
public class Student {
  String name;
  int age; 

  // CREACIÓN DEL CONSTRUCTOR
  public Student(String name, int age){
    this.name = name;
    this.age = age;
  }


  // CREACIÓN DE ENCAPSULACIÓN 
  
  // Getter
  public String getName(){
    return name;
  }

  public int getAge(){
    return age;
  }

  //Setter
  public void setAge(int age){
    if (age >= 0 && age <= 120){
      this.age= age;
    }
  }
  
}
```

Main.java
```
/** CREANDO OBJETOS
public class Main {
    public static void main(String[] args) {
        Student s1 = new Student();
        s1.name = "Ana";
        s1.age = 15;

        Student s2 = new Student();
        s2.name = "Luis";
        s2.age = 16;

        System.out.println(s1.name + " tiene " + s1.age + " años.");
        System.out.println(s2.name + " tiene " + s2.age + " años.");
    }
}
*/


/** PARA EL CONSTRUCTOR
    public class Main {
        public static void main(String[] args) {
            Student s1 = new Student("Ana", 15);
            Student s2 = new Student("Luis", 16);

            System.out.println(s1.name + " tiene " + s1.age + " años.");
            System.out.println(s2.name + " tiene " + s2.age + " años.");
        }
    }
*/


// PARA LA ENCAPSULACIÓN 
public class Main {
  public static void main(String[] args) {
    
    Student s1 = new Student("Ana", 17);
    System.out.println(s1.getName() + " tiene " + s1.getAge() + " años. ");

    s1.setAge(19);
    System.out.println("Despues de actualizar, " + s1.getName() + " tiene " + s1.getAge() + " años. ");

    s1.setAge(25);
    System.out.println("Edad final de " + s1.getName() + ": " + s1.getAge());
    
  
    

    
  }
}
```

- **Práctica**: [Clic para programar]( https://replit.com/@replit/Java?v=1)

---

### Lección 5: Programa final POO, mejores practicas y errores comunes. (- minutos)  
**Responsable:**

- **Descripción:**

- **Enlace del video:** https://www.youtube.com/watch?v=example-link1

- **Editor online:**  (link del codigo que desarrollaste)

- **Consejos clave:** 

- **Código inicial utilizado en la exposición:**
```
-
```

- **Práctica**: [Clic para programar](  )

---

## Recursos Adicionales
- **Código Fuente Completo**: [Repositorio de GitHub](https://github.com/java-fundamentals-course-chronisteam/java-fundamentals-course-chronisteam)
- **Todas las Actividades Prácticas**:
## Recursos Adicionales

| Lección | Actividad                         | Editor Online / Enlace |
|--------|------------------------------------|--------------------------|
| 1      | Introducción a Java y la programación, sintaxis básica: variables, tipos de datos.                | https://replit.com/~ |
| 2      | Operadores y estructuras de control, métodos, funciones y parámetros.           | https://replit.com/~ |
| 3      | Entrada/salida con Scanner,Arreglos simples o cadenas.  | https://replit.com/~ |
| 4      | Introducción a la POO (clases, objetos, constructores), principios básicos: encapsulación, instanciación.    | https://replit.com/join/jzpobhqipb-schneider0104dc
| 5      | Programa final POO, mejores practicas y errores comunes    | https://replit.com/~ |
  
**¡Gracias por completar el curso!**
---
## 👥 Elaboración
Universidad Peruana de Ciencias Aplicadas
Carrera de Ingeniería de Software
Período 202520
Curso: 1ASI0729 Desarrollo de Aplicaciones Open Source
NRC 7391
**Nombre del equipo**: chronisteam
**Líder del equipo**: Alejandro Nicolas Barturen Guzman
**Integrantes del equipo**: Andreow Jomark Santiago Peña, Carlos Alberto Lopez Goitia, , Schneider Carlos Alberto Delgado Carrasco & Sebastian Martin Beingolea Montalvo
**Fecha de entrega**: 16/11/25

# Participant Performance Report  
**Startup:** chronisteam
**NRC:** 7391  
**Entrega:** Trabajo Complementario – Course Plan  
**Team Leader:** Alejandro Nicolas Barturen Guzman

| Ítem | Estudiante                                   | Responsabilidades                                                                                                              | Cumplió a tiempo | Cumplió a destiempo | Cumplió parcialmente | No cumplió | Calificación (20/16/13/07/00) |
|------|----------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------|------------------|----------------------|------------------------|------------|-------------------------------|
| 1    | Andreow Jomark Santiago Peña       | Lección 1 (Introducción a Java y la programación, sintaxis básica: variables, tipos de datos).       | X                |                      |                        |            | 20                            |
| 2    | Calors Alberto Lopez Goitia   | Lección 2 (Operadores y estructuras de control, métodos, funciones y parámetros).             | X                |                      |                        |            | 20                            |
| 3    | Sebastian Martin Beingolea Montalvo  | Lección 3 (Entrada/salida con Scanner,Arreglos simples o cadenas).               | X                |                      |                        |            | 20                            |
| 4    | Schneider Carlos Alberto Delgado Carrasco  | Lección 4 (Introducción a la POO (clases, objetos, constructores), principios básicos: encapsulación, instanciación). | X | | | | 20 |
| 5    | Alejandro Nicolas Barturen Guzman *(Líder)*  | Lección 5 (Programa final POO, mejores practicas y errores comunes). | X | | | | 20 |