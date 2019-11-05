# pruebita
#Salvador


/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package guiadeevaluacion;

/**
 *
 * @author Estudiante
 */
public class Libro extends Object {

    private String ISBN;
    private String titulo;
    private String autor;
    private int numeroDePaginas;

    public void setISBN(String _ISBN) {
        this.ISBN = _ISBN;
    }

    public String getISBN() {
        return ISBN;
    }

    public void setTitulo(String _titulo) {
        this.titulo = _titulo;
    }

    public String getTitulo() {
        return titulo;
    }

    public void setAutor(String _autor) {
        this.autor = _autor;
    }

    public String getAutor() {
        return autor;
    }

    public void setNumerDePaginas(int _numeroDePaginas) {
        this.numeroDePaginas = _numeroDePaginas;
    }
    
    public int getNumeroDePaginas(){
        return numeroDePaginas;
    }

    @Override
    public String toString() {
        return "El libro con "+ISBN
                +" creado por el autor "+autor+" tiene" 
                +numeroDePaginas+ "páginas";
    }
    
  
}
