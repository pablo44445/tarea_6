<template>
     <h2 style="margin-left: 33%;
                margin-top: -20px;">__________________________________________________________________</h2>

    <h2 style="margin-left: 33%;">tareas por hacer</h2>
   
    <div id="cuerpo">

        <b-card id="ingresar"
            tag="article"
            style="
            margin-top: -60px;
                    width: 430px;
                   margin-left: 40px;
                   color: azure;
                   position:absolute;
                   "
            class="col-md-4 "  bg-variant="dark" >
            <h4 style="margin-left: 120px; margin-bottom: 20px;">agregar tarea</h4>
                <div style="margin-left:20px ;">
                    <label for="descripcion">descripcion</label>
                    <br>
                    <textarea id="descripcion" rows="6" aria-label="Agregar descripcion ..." cols="45" style="color: grey; border-radius: 10px;">
                    </textarea>
                </div>
                <br>
                <div style="margin-left: 200px;">
                    <b-button variant="danger" class="m-1">limpiar</b-button>
                    <b-button type="submit" variant="primary">agregar</b-button>
                </div>
                  
        </b-card>

        <b-card 
            card-top=""
            tag="article"
            style="width: 950px;
                    margin-bottom: 15px;
                    margin-top:15px ;
                   border-radius: 15px;"
            class="col-md-10 offset-md-4"  bg-variant="dark">
                <div>
                    <b-table-simple style="color:azure;
                                            margin-bottom: -4px;">
                    <b-th>
                        <b-td style="width: 850px;"> 
                               <b-text>
                                sacar la basura
                               </b-text>
                        </b-td>

                        <b-td> 
                            <b-button  variant="primary" class="m-1">🗸</b-button>
                        </b-td>
                        <b-td>  
                            <b-button variant="danger" class="m-1">eliminar</b-button>
                        </b-td>
                    </b-th>            
                </b-table-simple>
                </div>             
            
        </b-card>
        <b-card 
            tag="article"
            style="width: 950px;
                    margin-bottom: 15px;
                    margin-top:15px ;
                   border-radius: 15px;"
            class="col-md-10 offset-md-4" bg-variant="dark">
                <div>
                    <b-table-simple style="color:azure;
                                            margin-bottom: -5px;">
                    <b-th>
                        <b-td style="width: 850px;"> 
                               <b-text>
                                arreglar la puerta de la terraza
                               </b-text>
                        </b-td>

                         <b-td> 
                            <b-button  variant="primary" class="m-1">🗸</b-button>
                        </b-td>
                        <b-td>  
                            <b-button variant="danger" class="m-1">eliminar</b-button>
                        </b-td>
                    </b-th>            
                </b-table-simple>
                </div>             
            
        </b-card>



    </div>
   
</template>

<script >

</script>

<style >

</style>