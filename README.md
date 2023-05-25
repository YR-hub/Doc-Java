@Override

/**
*Esta clase gestiona vehiculos
*los modelos que se venden
*/

public void save(Coche coche) {
  //TODO: Mejora esto cun un comentario
    coches.add(coche);
    System.out.println("Coche guardado: " + coche.toString());
}

@Override
public List<Coche> findAll() {
  // Aqui estan todos los coches
    System.out.println("Encontrados todos los coches");
    return coches;
}

@Override
public void delete(Coche coche) {
    coches.remove(coche);
    System.out.println("Coche eliminado: " + coche.toString());
}
