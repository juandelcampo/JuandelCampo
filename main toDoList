

let addToDoButton = document.getElementById("button");
let toDoContainer = document. getElementById("toDoContainer");
let inputField = document.getElementById("input");


/*Se agregó esta opción de alerta al no escribir nada dentro del campo*/
addToDoButton.onclick = function(){
    if(inputField.value.length == 0){
        alert("Por favor, ingresa una tarea")
    }else{
            
    var paragraph = document.createElement("p");
    paragraph.classList.add("paragraph-styling");
    paragraph.innerText = inputField.value;
    toDoContainer.appendChild(paragraph);
    inputField.value = "";
    paragraph.addEventListener("click", function(){
    paragraph.style.textDecoration= "line-through";
    /*esto era doble click y se pasó a un click dentro de la función porque en movil no
    respondía bien*/
    paragraph.addEventListener("click", function(){
    toDoContainer.removeChild(paragraph);
    }) 
    })
    }}


