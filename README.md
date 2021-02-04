# POOjavascrip
tutorial de JavaScript Programación Orientada a Objeto

class animales{

	constructor(color,raza,tipo){

		this.color=color;
		this.raza=raza;
		this.tipo=tipo;

		this.info= `soy ${this.color}, tengo un perro ${this.raza}, y el tipo de raza es  ${this.tipo}`


	}
}
	let perro=new animales("Deimer","fino","pinche");
	
	let perro2=new animales("Hellen","fino","pinche");


	document.write(perro.info);
		document.write( "<br></br>");
	document.write(perro2.info);


class animal{

	constructor(especie,color,raza){

		this.especie=especie;
		this.color=color;
		this.raza=raza;

		this.info= `la especie del perro es, ${especie}, el color es ${color}, y la raza es ${raza}`;



	}
}

let perro = new animal("Husky Siberiano","negro","pitbul");

document.write(perro.info);
