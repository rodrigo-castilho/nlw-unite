{
  nome: "Mayk Brito",
  email: "mayk@gmail.com",
  dataInscricao: new Date(2024, 2, 22, 19, 20),
  dataCheckIn: new Date(2024, 2, 25, 22, 00)
  
}

for(let participante of participantes) {
  output = output + criarNovoParticipante(participante)
}


//Não envia o formulario

<form onsubmit="adicionarParticipante(event)">

const adicionarParticipante = (event) => {
  event.preventDefault()
}