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

