# ejercicio-de-bootstrap-elementos
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ejercicio Bootstrap</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-GLhlTQ8iRABdZLl6O3oVMWSktQOp6b7In1Zl3/Jr59b6EGGoI1aFkw7cmDA6j6gD" crossorigin="anonymous">
</head>
<body>
    <div class="container py-4">
        <div class="bg-lingt p-5 rounded-3" >
            <div class="container-fluid py-5">
                <h1 class="display-5 fe-bold">Custom jumbotron</h1>
                <p class="col-md-8 fs-4">Using a series of utilities, you can create this jumbotron, just like the one in previous versions of Bootstrap. Check out the examples below for how you can remix and restyle it to your liking</p>
            <button 
            type="button" 
            class="btn btn-primary" 
            data-bs-toggle="modal" 
            data-bs-target="#modal-ejemplo"
            >
                click aqui
            </button>
            <div class="modal" 
            data-bs-backdrop="footer" id="modal-ejemplo">
                <div class="modal-dialog modal-dialog-centered">
                    <div class="modal-content">
                        <h4 class="modal-header">Esta es la ventana modal</h4>
                        <div class="modal-body">
                            
                        <hr/>
                        <br>
                        <br>
                        <div class="mb-3">
                            <label class="form-label" for="nombre" >introduce tu nombre</label>
                            <imput id="nombre" type="text" class="form-control" placeholder="tu nombre" disables/>
                            <div class="form-text">introduce tu nombre de pila</div>
                        </div>
                        <div class="mb-3">
                            <label for="exampleFormControlInput1" class="form-label">Introduce numero de Telefono</label>
                            <input type="number"  class="form-control"   id="exampleFormControlInput1" placeholder="number">
                        </div>
                        <div class="mb-3">
                            <label for="exampleFormControlTextarea1" class="form-label">Example textarea</label>
                            <textarea class="form-control" id="exampleFormControlTextarea1" rows="3"></textarea>
                        </div>
        
    <div class="card" style="width:15rem;">
        <img src="https://rinconesgipuzkoa.diariovasco.com/fotos/2017/09/donostia-sunset-201709260812-800x.jpg"
        class="card-img-botton" 
        alt="imagen"
        />
            <h5 class="card-title">Yailen gimenez</h5>
            <p class="card-text"> Hola! soy Yai ,esta es mi tarjeta de presentacion :soy una estudiante de la escuela Santa Justina del secundario ,estoy cursando ya en mi ultimo año. Vivo con mi familia que esta compuesta por mis dos padres y dos hermanos menores.
                Me considero una chica que le gusta aprender constantemente ,respestuosa,inteligente,solidaria,disiplinada y con grandes objetivos por cumplir.
                Estoy en el bachiller de Informatica ,soy Community Manager y ya eh lanzado mi marca en instagram.Actualmente estoy en curso de programacion aprendiendo nuevos leguajes y asi comenzar en un nuevo trabajo.
            </p>
            <div class="card-footer">
                <button class="btn btn-primary btn-sm"> yailengimenez23@gmail.com</button>
            </div>
        </div>
    </div>
        </div>
    </div>
</div>
</div>

</body>
<script 
src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js" integrity="sha384-w76AqPfDkMBDXo30jS1Sgez6pr3x5MlQ1ZAGC+nuZB+EYdgRZgiwxhTBTkF7CXvN" crossorigin="anonymous"></script>
</html>
