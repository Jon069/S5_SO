Patrones de Diseño
Para Martínez (2020) “Los patrones de diseño o design patterns, son una solución general, reutilizable y aplicable a diferentes 
problemas de diseño de software”. Los patrones de diseño a usar en este sistema permiten organizar el sistema, facilitar su 
mantenimiento, mejorar su funcionamiento y son:

-	Factory Method (Patrón creacional):
  Permite crear diferentes tipos de objetos sin que el sistema tenga que conocer todos los detalles de su creación. En el sistema,
 	se puede utilizar para crear registros de rescates, adopciones o seguimientos postadopción, según la necesidad. Esto facilita
 	agregar nuevos tipos de registros sin cambiar toda la estructura del programa.

-	Facade (Patrón estructural):
  Facilita una interfaz sencilla para acceder a varias funciones del sistema, disimulando la complejidad de los procesos internos.
  Por ejemplo, permite coordinar el registro de un rescate, la actualización de los datos del animal y su disponibilidad para adopción
 	mediante una operación más fácil.

-	Observer (Patrón de comportamiento):
  Permite que diferentes componentes reciban avisos cuando sucede un cambio importante en el sistema. Por ejemplo, cuando una solicitud
  de adopción es aprobada o se registra un seguimiento postadopción, el sistema puede comunicar automáticamente al personal responsable
 	o a los usuarios correspondientes.
