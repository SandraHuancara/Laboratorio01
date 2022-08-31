# Laboratorio01
<!DOCTYPE html>
<html lang="en">
<head>
    <link href="estilos.css" rel="stylesheet" type="text/css"/>
    <meta charset="uft - 8"/>
    <title> Formularios en HTML 5 -Tecsup </title>
</head>
<body>
    <section>
        <h1>Travel Authorization Form </h1>
        <form>
            <h2> Seccion A: Informacion del cliente </h2>
            <p> 

                <label for="name"> Cargo:</label>
                <input type="text" style="text-transform: uppercase"
                 name="name" 
                 id="name" min="4" max="100"/>
            </p>
        </div>
        <p>
            <label for="name"> Nombre:</label>
            <input type="text" style="text-transform: uppercase"
             name="name" 
             id="name" min="4" max="100"/>
        </p>
        <p>
            <label for="name"> Primer apellido:</label>
            <input type="text" style="text-transform: uppercase"
             name="name" 
             id="name" min="4" max="100"/>
        </p>
        <p>
            <label for="name"> Segundo apellido:</label>
            <input type="text" style="text-transform: uppercase"
             name="name" 
             id="name" min="4" max="100"/>   
        </p>
        <p>
            <label for="email">Correo Electrico:</label>
            <input type="email" name="email" id=""
            placeholder="tecsup.arp@tecsup.edu.pe"/>
        </p>
        <p>
            <label for="email">Numero de telefono:</label>
            <input type="number" name="numero" max="999999999" max="999999999">
        </p>
        </form>
        <h2> Seccion B: Informacion del viaje</h2>
        <form>
        <p>
            <label for="aerolinea" id="aerolinea"> Nombre de la aeolinea </label>
            <select name="Seleccione una aerolinea">
                <option value="0"> Seleccione una aerolinea</option>
                <option value="1">LATAM</option>
                <option value="2">AEROMEXICO</option>
                <option value="3">COPA AIRLINES</option>
                <option value="4">CONDOR</option>
            </select>
        </p>
        <p>
            <label for="name">Destino:</label>
            <input type="text" name="name" id="name"/>
        </p>
        <p>
            <label for="fecha">Fecha de salida:</label>
            <input type="date" name="fecha" id="fecha"/>
        </p>
        <p>
            <label for="fecha">Fecha de regreso:</label>
            <input type="text" name="fecha" id="fecha"/>
        </p>
        <p>
            <label for="number">Coste estimado:</label>
            <input type="number" id="costo" name="costo" min="100" max="1000"/>
        </p>
        <p>
            <label for="cliente">¿Incluye la visita al cliente?</label>
            <input type="checkbox" name="casilla"/>
        </p>
        <p>Gastos adicionales estimados</p>
        <p>
            <label for="number">Coste estimado:</label>
            <input type="number" id="gastos" name="gastos" />
        </p>
        <p>
            <label for="number">Hotel:</label>
            <input type="number" id="gastos" name="gastos" />
        </p>
        <p>
            <label for="number">Comidas:</label>
            <input type="number" id="gastos" name="gastos" />
        </p>
        <p>
            <label for="number">Hotel:</label>
            <input type="number" id="gastos" name="gastos"/>
        </p>
        <p>
            <label for="number">Total estimado:</label>
            <input type="number" id="gastos" name="gastos" placeholder="0.00€" />
        </p>
        <div>
            <label for="number">Metodo de pago utilizados</label><br />
            <label type="radio" name="boton" value="1" />Metalico<br/>
            <label type="radio" name="boton" value="2" />tarjeta de credito<br/>
            <label type="radio" name="boton" value="3" />Cheque<br/>
        </div>
        <div>
            <label for="number">Proposito del viiaje</label>
            <textarea name="texto" rows="10" cols="10000"></textarea>
        </div>
        </form>
        <input type="submit" name="Enviar" />
    </section>
</body>

</html>
