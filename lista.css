window.onload=function(){

//para nomes
var filtro = document.getElementById('filtro-nome');
var tabela = document.getElementById('lista');
filtro.onkeyup = function() {
    var nomeFiltro = filtro.value;
    for (var i = 1; i < tabela.rows.length; i++) {
        var conteudoCelula = tabela.rows[i].cells[0].innerText;
        var corresponde = conteudoCelula.toLowerCase().indexOf(nomeFiltro) >= 0;
        tabela.rows[i].style.display = corresponde ? '' : 'none';
    }
};

//para email
var filtro2 = document.getElementById('filtro-email');
var tabela2 = document.getElementById('lista');
filtro2.onkeyup = function() {
    var nomeFiltro = filtro2.value;
    for (var i = 1; i < tabela2.rows.length; i++) {
        var conteudoCelula = tabela2.rows[i].cells[1].innerText;
        var corresponde = conteudoCelula.toLowerCase().indexOf(nomeFiltro) >= 0;
        tabela2.rows[i].style.display = corresponde ? '' : 'none';
    }
};

}