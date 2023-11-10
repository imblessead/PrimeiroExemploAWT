# PrimeiroExemploAWT
PrimeiroExemploAWT

package exemplos;

import java.awt.*;

public class PrimeiroExemploAWT extends Frame{
	
	//metodo construtor E o metodo que vai construir um objeto
	
	PrimeiroExemploAWT(){
		Button b= new Button("Wagner");
		b.setBounds(30, 100, 80, 30);
		
	add(b);
	setSize(300,300);
	setTitle("Chegou o disco voador");
	setLayout(null);
	setVisible(true);

	}
	public static void main(String[] args) {
		PrimeiroExemploAWT awt = new  PrimeiroExemploAWT();
	}

}
