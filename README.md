function sumar() {
    let op1 = document.getElementById("valor1").value
    let op2 = document.getElementById("valor2").value

    let sum = parseInt(op1)+ parseInt(op2)

    document.getElementById("rpta").innerHTML = sum
}

function restar() {


    let op1 = document.getElementById("valor1").value
    let op2 = document.getElementById("valor2").value
    let res = parseInt(op1) - parseInt(op2)
    document.getElementById("rpta2").innerHTML = res

}

function multiplicar() {
    let op1 = document.getElementById("valor1").value
    let op2 = document.getElementById("valor2").value
    let mult = parseInt(op1) * parseInt(op2)
    document.getElementById("rpta3").innerHTML = mult

}


function dividir() {
    let op1 = document.getElementById("valor1").value
    let op2 = document.getElementById("valor2").value
    let division = parseInt(op1) / parseInt(op2)

    document.getElementById("rpta4").innerHTML = division



}
