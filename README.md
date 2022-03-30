package com.company;

public class Main {

    public static void main(String[] args){
      coche micoche = new coche();
        micoche.IncrementarPuertas();
        System.out.println(micoche.puertas);
}
    public static void suma (int a, int b) {
    }
}

class coche {
    public int puertas = 4;

    public void IncrementarPuertas() {
            this.puertas++;
        }
}
