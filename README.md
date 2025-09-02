# Nodo Bitcoin | 23C1-pequenos-rustaceans
Repo for Rust Taller De Programacion 1 FIUBA

Trabajo de mediano tamaño para la materia **Taller de Programación I** de la Facultad de Ingeniería de la Universidad de Buenos Aires (**FIUBA**), durante el primer cuatrimestre del año 2023. Consiste en la implementación de un Nodo Bitcoin con funcionalidades acotadas, capaz de conectarse a la red _p2p_ Bitcoin, comunicarse con otros nodos por medio de TCP Sockets, realizar validaciones con funciones de hash y con merkle tree, entre otras cosas. Además, se implementó una _Wallet_ junto a su interfaz gráfica para que el usuario pueda conectarse con una o varias cuentas al nodo. Para más detalle sobre el trabajo, se tiene disponible el [enunciado](https://taller-1-fiuba-rust.github.io/proyecto/23C1/proyecto.html).

El trabajo fue desarrollado en un repositorio privado de la organización de la materia, por lo que no es posible visualizar en este proyecto el historial completo de *commits*, ramas y seguimiento detallado del proceso.

# Compilacion 
Para correr la wallet:
```bash
cargo run --bin wallet <path de configuracion>
```

Para correr el nodo:
```bash
cargo run --bin node <path de configuracion>
```

# Pruebas
Para probar el programa, dejamos a continuacion dos billeteras que ya contienen plata cargada

privkey en wif: 92SD2oqjN8jUb33XoGmkkoGML1nRxBdcGZiXoqDL9xU1yowgHpJ
address: mg5Xt8ogUKjj5oxxeDYdLvLUVSw7HNE6Cn

privkey en wif: 93JcZKAPezbqvV5Ntut5XCFZSowipPJJpWxkPnVgyaRRY1iVHjT
address: n1oeWx2DbzpB46xgMgt52EuR2JpsvvDuRx
