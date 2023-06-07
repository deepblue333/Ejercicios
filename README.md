
public class Coche {
    private int numPuertas;

    public Coche() {
        numPuertas = 0;
    }

    public void agregarPuerta() {
        numPuertas++;
    }

    public int getNumPuertas() {
        return numPuertas;
    }

    public static int sumarNumeros(int num1, int num2, int num3) {
        return num1 + num2 + num3;
    }

    public static void main(String[] args) {
        // Primera parte
        int resultado = sumarNumeros(5, 3, 2);
        System.out.println("El resultado de la suma es: " + resultado);

        // Segunda parte
        Coche miCoche = new Coche();
        miCoche.agregarPuerta();
        System.out.println("El coche tiene " + miCoche.getNumPuertas() + " puerta(s).");
    }
}
