# ramazan



let mesajSayac = 1; 

function mesajGonder() {
    var mesaj = document.getElementById("mesaj").value;
    
   
    document.getElementById("mesajKutulari").innerHTML += "<div class='gidenMesaj' id='dene1' > mesaj:" + mesajSayac + " <br>" + mesaj + "<br> </div> ";
    
    mesajSayac++; 
    document.getElementById("mesaj").value = ""; 
}
