# hoja-de-vida
Mi magnifica hoja de vida

```javascript

function Tip (){
  console.log("¡Estás dando un gran paso al comenzar tu camino en la programación!");
  console.log("No te detengas, cada línea de código que escribes te acerca más a tus metas.");
  console.log("Al principio puede parecer desafiante, pero cada error y cada aprendizaje te hacen más fuerte.");
  console.log("Lo estás haciendo bien, sigue así, porque lo mejor está por venir.");
  console.log("¡No hay límites para lo que puedes lograr si sigues aprendiendo y perseverando!");
  console.log("¡Sigue adelante, vas por el camino correcto! ❤️");

  console.log("A la proxima cierra la cuenta")
}

Tip()

class Persona {
  constructor(nombre, github, telefono) {
    this.nombre = nombre;
    this.github = github;
    this.telefono = telefono;
  }

  // Método para mostrar información de la persona
  mostrarInfo() {
    console.log(`Nombre: ${this.nombre}`);
    console.log(`GitHub: ${this.github}`);
    console.log(`Teléfono: ${this.telefono}`);
  }
}

// Crear una instancia de la clase Persona
const programador1 = new Persona("Juan David", "https://github.com/GREND-LEARD", "3102570586");
const programador2 = new Persona("David Triana", "https://github.com/David-Triana55", "3008550592");

// Llamar al método para mostrar la información
programador1.mostrarInfo();
programador2.mostrarInfo();
