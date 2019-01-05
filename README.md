# test1
premier test
import { Component } from '@angular/core';


@Component({
  selector: 'app-root',
  templateUrl: './app.component.html',
  styleUrls: ['./app.component.css']
})
export class AppComponent {
	title:string= 'salut';
	inputType: string='color';
	backColor: string='red';
	display: boolean = true;
	
	changeColor(color: string, display2: boolean): void{
		this.backColor = color;
		this.display = display2;
	}

	nom2:string;
	constructor() {
		this.nom2 = 'salut';
	}


}
