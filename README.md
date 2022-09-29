# c-digo
let filme = {
  nome: 'Os Vingadores',
  cod: '1420',
  categoria: 'Ação'
};
function listarpropriedades(){
  for (const propriedade in filme){
  console.log({propriedade});
}  
}
function listarelementos(){
  for (const propriedade in filme){
  console.log(filme[propriedade]);
}  
}
listarpropriedades();
listarelementos();
