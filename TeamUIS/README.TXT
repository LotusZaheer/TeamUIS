/**
 * Esta clase crea y guarda información sobre los estudiantes.
 * 
 * @author (TeamUis) 
 * @version (a version number or a date)
 */


public class Estudiante
{
    // instance variables - replace the example below with your own
    private String nombre;
    private String codigo;
    private String carrera;
    private String telefono;   
    

    /**
     * Constructor for objects of class Estudiante
     */


    public Estudiante(String nombre, String codigo, String carrera, String telefono)
    {
        // initialise instance variables
        this.nombre = nombre;
        this.codigo = codigo;
        this.carrera = carrera;
        this.telefono = telefono;        
    }
}


/**
 * Esta clase crea las materias requeridas por los estudiantes.
 * 
 * @author (TeamUis) 
 * @version (a version number or a date)
 */


public class Materia
{
    // instance variables - replace the example below with your own
    private String nombre;
    private String codigo;

/**
* Constructor for objects of class Materia
*/


public Materia(String nombre, String codigo)
    {
        // initialise instance variables
        this.nombre = nombre;
        this.codigo = codigo;
    } 
}


/**
 * Esta clasea crea los tutores con sus respectivas matertias.
 * 
 * @author (your name) 
 * @version (a version number or a date)
 */


public class Tutor
{
    // instance variables - replace the example below with your own
    private String nombre;
    private String codigo;
    private String carrera;
    private String telefono;
    private Materia materia;

    /**
     * Constructor for objects of class Tutor
     */


public Tutor(String nombre, String codigo, String carrera, String telefono, Materia materia)
    {
        // initialise instance variables
        this.nombre = nombre;
        this.codigo = codigo;
        this.carrera = carrera;
        this.telefono = telefono;
        this.materia = materia;
        
    }
}


import java.util.*;
/**
 * Esta clase crea y gestiona los diferentes grupos de estudio.
 * 
 * @author (teamUIs) 
 * @version (a version number or a date)
 */


public class Grupo
{
    // instance variables - replace the example below with your own
    private ArrayList<Estudiante> estudiantes;
    Estudiante estudiante;
    private Tutor tutor;
    private Materia materia;
    private String detalles;

    /**
     * Constructor for objects of class Grupo
     */
/**
 * Esta clase crea y guarda información sobre los estudiantes.
 * 
 * @author (TeamUis) 
 * @version (a version number or a date)
 */


public class Estudiante
{
    // instance variables - replace the example below with your own
    private String nombre;
    private String codigo;
    private String carrera;
    private String telefono;   
    

    /**
     * Constructor for objects of class Estudiante
     */


    public Estudiante(String nombre, String codigo, String carrera, String telefono)
    {
        // initialise instance variables
        this.nombre = nombre;
        this.codigo = codigo;
        this.carrera = carrera;
        this.telefono = telefono;        
    }
}


/**
 * Esta clase crea las materias requeridas por los estudiantes.
 * 
 * @author (TeamUis) 
 * @version (a version number or a date)
 */


public class Materia
{
    // instance variables - replace the example below with your own
    private String nombre;
    private String codigo;

/**
* Constructor for objects of class Materia
*/


public Materia(String nombre, String codigo)
    {
        // initialise instance variables
        this.nombre = nombre;
        this.codigo = codigo;
    } 
}


/**
 * Esta clasea crea los tutores con sus respectivas matertias.
 * 
 * @author (your name) 
 * @version (a version number or a date)
 */


public class Tutor
{
    // instance variables - replace the example below with your own
    private String nombre;
    private String codigo;
    private String carrera;
    private String telefono;
    private Materia materia;

    /**
     * Constructor for objects of class Tutor
     */


public Tutor(String nombre, String codigo, String carrera, String telefono, Materia materia)
    {
        // initialise instance variables
        this.nombre = nombre;
        this.codigo = codigo;
        this.carrera = carrera;
        this.telefono = telefono;
        this.materia = materia;
        
    }
}


import java.util.*;
/**
 * Esta clase crea y gestiona los diferentes grupos de estudio.
 * 
 * @author (teamUIs) 
 * @version (a version number or a date)
 */


public class Grupo
{
    // instance variables - replace the example below with your own
    private ArrayList<Estudiante> estudiantes;
    Estudiante estudiante;
    private Tutor tutor;
    private Materia materia;
    private String detalles;

    /**
     * Constructor for objects of class Grupo
     */


public Grupo(ArrayList<Estudiante> estudiantes, Tutor tutor, String detalles)
    {
        // initialise instance variables
        this.estudiantes = estudiantes;
        this.tutor = tutor;
        this.detalles = detalles;
    }


public Grupo(ArrayList<Estudiante> estudiantes, Materia materia, String detalles)
    {
        // initialise instance variables
        this.estudiantes = estudiantes;
        this.materia = materia;
        this.detalles = detalles;
    }
/**
 * Esta clase crea y guarda información sobre los estudiantes.
 * 
 * @author (TeamUis) 
 * @version (a version number or a date)
 */


public class Estudiante
{
    // instance variables - replace the example below with your own
    private String nombre;
    private String codigo;
    private String carrera;
    private String telefono;   
    

    /**
     * Constructor for objects of class Estudiante
     */


    public Estudiante(String nombre, String codigo, String carrera, String telefono)
    {
        // initialise instance variables
        this.nombre = nombre;
        this.codigo = codigo;
        this.carrera = carrera;
        this.telefono = telefono;        
    }
}


/**
 * Esta clase crea las materias requeridas por los estudiantes.
 * 
 * @author (TeamUis) 
 * @version (a version number or a date)
 */


public class Materia
{
    // instance variables - replace the example below with your own
    private String nombre;
    private String codigo;

/**
* Constructor for objects of class Materia
*/


public Materia(String nombre, String codigo)
    {
        // initialise instance variables
        this.nombre = nombre;
        this.codigo = codigo;
    } 
}


/**
 * Esta clasea crea los tutores con sus respectivas matertias.
 * 
 * @author (your name) 
 * @version (a version number or a date)
 */


public class Tutor
{
    // instance variables - replace the example below with your own
    private String nombre;
    private String codigo;
    private String carrera;
    private String telefono;
    private Materia materia;

    /**
     * Constructor for objects of class Tutor
     */


public Tutor(String nombre, String codigo, String carrera, String telefono, Materia materia)
    {
        // initialise instance variables
        this.nombre = nombre;
        this.codigo = codigo;
        this.carrera = carrera;
        this.telefono = telefono;
        this.materia = materia;
        
    }
}


import java.util.*;
/**
 * Esta clase crea y gestiona los diferentes grupos de estudio.
 * 
 * @author (teamUIs) 
 * @version (a version number or a date)
 */


public class Grupo
{
    // instance variables - replace the example below with your own
    private ArrayList<Estudiante> estudiantes;
    Estudiante estudiante;
    private Tutor tutor;
    private Materia materia;
    private String detalles;

    /**
     * Constructor for objects of class Grupo
     */


public Grupo(ArrayList<Estudiante> estudiantes, Tutor tutor, String detalles)
    {
        // initialise instance variables
        this.estudiantes = estudiantes;
        this.tutor = tutor;
        this.detalles = detalles;
    }


public Grupo(ArrayList<Estudiante> estudiantes, Materia materia, String detalles)
    {
        // initialise instance variables
        this.estudiantes = estudiantes;
        this.materia = materia;
        this.detalles = detalles;
    }


public Grupo(ArrayList<Estudiante> estudiantes, Tutor tutor, String detalles)
    {
        // initialise instance variables
        this.estudiantes = estudiantes;
        this.tutor = tutor;
        this.detalles = detalles;
    }


public Grupo(ArrayList<Estudiante> estudiantes, Materia materia, String detalles)
    {
        // initialise instance variables
        this.estudiantes = estudiantes;
        this.materia = materia;
        this.detalles = detalles;
    }