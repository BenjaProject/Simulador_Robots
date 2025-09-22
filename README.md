# 🤖 Simulador de Robots en Java

Proyecto universitario desarrollado en **Java SE** que simula el comportamiento de robots básicos y avanzados.  
El programa aplica principios de **Programación Orientada a Objetos (POO)**, interfaces y generación aleatoria de estados.

---

## 📌 Descripción
- Se generan robots de tipo **Básico** y **Avanzado**, cada uno con atributos y constantes propias.  
- Los robots se mueven aleatoriamente mientras tengan batería disponible.  
- Cada acción (avanzar o girar) consume batería y se refleja en el estado del robot.  
- Al finalizar la simulación se muestran:  
  - Estado final de cada robot.  
  - El robot que avanzó más.  
  - El robot que avanzó menos.  

---

## 🛠️ Tecnologías
- **Lenguaje:** Java SE  
- **Paradigma:** Programación Orientada a Objetos (herencia, polimorfismo, encapsulación).  
- **IDE recomendado:** NetBeans o IntelliJ.  

---

## 📂 Estructura del Proyecto
El proyecto está organizado en **5 clases** (incluyendo `Main`):  

- `Robot` (clase base).  
- `RobotBasico` (hereda de Robot).  
- `RobotAvanzado` (hereda de Robot).  
- `AlmacenRobots` (gestiona la colección de robots).  
- `Main` (ejecuta la simulación).  

Además, se implementa la interfaz **Girable** con los métodos:  
- `girarDerecha90grados()`  
- `girarIzquierda90grados()`  

---

## ▶️ Ejecución
1. Clona este repositorio:  
   ```bash
   git clone https://github.com/usuario/SimuladorRobots.git
Abre el proyecto en tu IDE Java favorito (NetBeans/IntelliJ/Eclipse).

Compila y ejecuta la clase Main (Solemne).
