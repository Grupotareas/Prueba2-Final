<!DOCTYPE html>
<html lang="es">

<head>
    <!-- Meta Tags Requeridos -->
    <meta charset="UTF-8">
    <meta name="description"
        content="">

    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <link rel="shortcut icon" href="imagenes/carwash.jpg">
    <link rel="stylesheet" href="css/style.css">
    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/css/bootstrap.min.css"
        integrity="sha384-TX8t27EcRE3e/ihU7zmQxVncDAy5uIKz4rEkgIXeMed4M0jlfIDPvg6uqKI2xXr2" crossorigin="anonymous">
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"
        integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj"
        crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-ho+j7jyWK8fNQe+A12Hb8AhRq26LrZ/JpcUGGOn+Y7RsweNrtN/tE3MoK7ZeZDyx"
        crossorigin="anonymous"></script>
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
    <script src="jquery3.5.1.min.js"></script>
    <script src="jQuery.js"></script>
    <script type="text/javascript"
        src="https://rawcdn.githack.com/franz1628/validacionKeyCampo/bce0e442ee71a4cf8e5954c27b44bc88ff0a8eeb/validCampoFranz.js"></script>
    <title>Super Clean</title>
</head>

<body class="body"> 
    <div class="container-fluid bg-info"> 
        <!-- Inicio cabecera  -->

        <nav class="navbar navbar-expand-md navbar-dark  ">

            <a class="navbar-brand mr-5 " href="index.html">
                <img src="imagenes/carwash.jpg" width="50" height="50" class="d-inline-block align-top" alt="" loading="lazy">
                <span class= "ml-5" >The Cleners </span>  
            </a>        
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
    
            <!--  Inicio Menú de Navegación -->
       
                    
                    <div class="collapse navbar-collapse" id="navbarNav">
                        <ul class="navbar-nav navbar-nav ml-auto">
                            <li class="nav-item active">
                                <a class="nav-link" href="ot.html">Orden de Trabajo<span class="sr-only">(current)</span></a>
                            </li>
                            <li class="nav-item ">
                                <a class="nav-link" href="#ancla1">Registro Clientes</span></a>
                            </li>
                            <li class="nav-item "> 
                                <a class="nav-link" href="#ancla2">Registro Vehículo</a>
                            </li>
                        </ul>
                    </div>
                </nav>
            
        </div>

            <!--  Fin Cabecera-->

            <!--  Inicio Formulatio Registro Cliente-->  

            <div class=" container fluid alert alert-secondary mt-3 mb-3 offset-md-2 col-12 col-md-8 col-lg-9  border border-info rounded justify-content-center">
            <form role="form">   
                <div class= " row justify-content-center mt-3 mb-3   ">
                    <a name="ancla1"></a>
                        <h1>Registro</h1>
                </div>           

    
   
    <div class="container-fluid">
        <div class="row">

            <div class="col-md-6">

                <form role="form">
                    <h2>Datos de Cliente</h2>
                    <div class="form-group">
                        <label>
                            RUT
                        </label>
                        <div class="form-group">
                            <table>
                                <tr>
                                    <td><input class="form-control" type="text" name="txtRut" id="txtRut"  value="" maxlength="8"placeholder="Ingrese su Rut"></td>
                                    <td>-</td>
                                    <td><input type="text" name="txtCodRut" id="txtCodRut" maxlength="1" class="form-control w-25"></td>
                                </tr>
                            </table>
                        </div>
                    </div>

                    <div class="form-group">
                        <label>
                            Nombre
                        </label>
                        <input type="text" required name=txtNombre id="txtNombre" class="form-control" maxlength="50"placeholder="Ingrese su Nombre">
                    </div>
                
                    <div class="form-group">
                        <label>
                            Apellido
                        </label>
                        <input type="text" required name=txtApellido id="txtApellido" class="form-control" maxlength="50"placeholder="Ingrese su Apellido">
                    </div>
                
                    <div class="form-group">
                        <label>
                            Dirección
                        </label>
                        <input type="text" required name=txtDireccion id="txtDireccion" class="form-control" maxlength="100"placeholder="Ingrese su Dirección">
                    </div>
                
                    <div class="form-group">
                        <label>
                            Comuna
                        </label>
                        <select name=combo required name=cmbComuna class="form-control">
                            <option value="">--</option>
                            </select>
                    </div>
                    <div class="form-group">
                        <label>
                            Lavado
                        </label>
                        <br>
                        <input type="checkbox" name="chkRevTec" required class="" value=1> Lavado Exterior $5.000.-
                        <br>
                        <input type="checkbox" name="chkRevTec" required class="" value=2> Lavado de Motor $8.000.-
                    
                    </div>
                               
                    <div class="form-group">
                        <label>
                            Operador
                        </label>
                        <select class="form-control" required name=cmbOperador>
                            <option value="">--</option>
                            <option value=1>Cesar</option>
                            <option value=2>Robinson</option>
                            <option value=3>Fernanda</option>
                        </select>
                    </div>

                    <div class="form-group">
                        <label>
                            Agende su Servicio
                        </label>
                        <input type="datetime-local" name="txtFyHora" required class="form-control">
                    </div>
                </form>


            </div>

            <div class="col-md-6">
               
                <form role="form">
                    <h2>Datos del Vehículo</h2>
                    <div class="form-group">

                        <P>Tipo de Vehículo:</P>
                        <input type="radio" name=rdoTipoVehiculo value=1> Furgón
                        <br>
                        <input type="radio" name=rdoTipoVehiculo value=2> Automóvil
                        <br>
                        <input type="radio" name=rdoTipoVehiculo value=3> Camión   
                        <br>
                        <input type="radio" name=rdoTipoVehiculo value=4> Camioneta
                        <br>
                        <input type="radio" name=rdoTipoVehiculo value=5> Moto
                    </div>
                
                    <div class="form-group">
                        <label>
                            Marca
                        </label>
                        <input type="text" name="txtMarca" required id="txtMarca" class="form-control" maxlength="20" placeholder="Marca del Vehículo">
                    </div>
                
                    <div class="form-group">
                        <label>
                            Modelo
                        </label>
                        <input type="text" name="txtModelo" required id="txtModelo" class="form-control" maxlength="20" placeholder="Modelo del Vehículo">
                    </div>

                    <div class="form-group">
                        <label>
                            Año
                        </label>
                        <input type="text" name="txtAno" id="txtAno" maxlength="4" required class="form-control" placeholder="Año del Vehículo">
                    </div>

                    <div class="form-group">
                        <label>
                            Revisión Técnica Vigente
                        </label>
                        <input type="checkbox" name="chkRevTec" class="">
                    </div>


                    <form id="contact-form" action="" method="POST">
                
                        <div class="form-group">
                            <label>Lavado Exterior</label>
                            <input type="number" name="txtLavExterior" id="txtLavExterior">
                        </div>
                        <div class="form-group">
                            <label>Lavado de Motor</label>
                            <input type="number" name="txtLavMotor" id="txtLavMotor">
                        </div>
                        
                        <div class="form-group">
                            <input type="button" id="btnSumar" value="Sumar" class="btn btn-primary">
                        </div>
                        <div class="form-group">
                            <input type="button" id="btnTotal" value="TOTAL del Servicio" class="btn btn-primary">
                        </div>
                        <div id="divMensajes">
                        </div>

                        <script>
                        function sumar(){
                         var numero1 = document.getElementById("txtLavExterior").value;
                         var numero2 = document.getElementById("txtLavMotor").value;
                       
                         var suma = parseInt(numero1) + parseInt(numero2);
                       
                         document.writeln(suma);
                        }
                        </script>
    
                    </form>

                    
                </form>


            </div>
        </div>
    </div>
    
</body>



</html>