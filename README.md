# TEMA_1_ACTIVIDAD_3_EJERCICIO_3

   DATOS_PERSONAS
-----------------
   /*Realizar un programa en Java dónde pida los siguientes datos (nombre, 
apellidos, teléfono, sexo, edad, dirección), una vez registrado los datos 
deberá cargarlo en una lista de objetos y mostrar resultados en un JTable.*/
package datospersonales;

public class DatosPersonales {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        VentanaPersona ve = new VentanaPersona(); //crar el objeto de la clase ventana
        ve.setVisible(true);//hacer que la ventana sea visible
        }
        }
-----------------------------------
PERSONAS

package datospersonales;
public class Persona {
    String nombre, apellidos, telefono, sexo, edad, direccion; // declara que seran usados en la tabla

    //crear metodos setter y getter
    public String getNombre() {
        return nombre;
    }

    public void setNombre(String nombre) {
        this.nombre = nombre;
    }

    public String getApellidos() {
        return apellidos;
    }

    public void setApellidos(String apellidos) {
        this.apellidos = apellidos;
    }

    public String getTelefono() {
        return telefono;
    }

    public void setTelefono(String telefono) {
        this.telefono = telefono;
    }

    public String getSexo() {
        return sexo;
    }

    public void setSexo(String sexo) {
        this.sexo = sexo;
    }

    public String getEdad() {
        return edad;
    }

    public void setEdad(String edad) {
        this.edad = edad;
    }

    public String getDireccion() {
        return direccion;
    }

    public void setDireccion(String direccion) {
        this.direccion = direccion;
    }
       //crear constructures
    public Persona(String nombre, String apellidos, String telefono, String sexo, String edad, String direccion) {
        this.nombre = nombre;
        this.apellidos = apellidos;
        this.telefono = telefono;
        this.sexo = sexo;
        this.edad = edad;
        this.direccion = direccion;
    }
    
}
       
