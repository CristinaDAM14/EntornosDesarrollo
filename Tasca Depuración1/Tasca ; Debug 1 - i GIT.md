# Ejercicio Depuración

## **1. En la función1... Què fan aquestes línies de codi?**
### String string2 = "string2";
### string2= string2.substring(0, string2.length()-1);
### string2=string2+"1";
> Se está creando una variable de texto, a la cual se le da el nombre de string2, y también se le da ese valor.<br>
> A continuación va variando el valor de la variable.
## **2. Què valen les variables string1 i string2 abans d'executar el codi de comprovació següent?**
### if(string1 == string2 ) {
### System.out.println("SÓN IGUALS " + a );.
### }
### else {
### System.out.println("SÓN DIFERENTS");
### }
> Las variables tienen un valor de texto, en el caso de que se le haya puesto algún valor al crear la variable, tendrán ese valor, en el caso de no hacerlo, no tendrá ningún valor. Con el if se está haciendo una comparación, en este caso viendo si la primera variable y la segunda son iguales, en el caso de que no lo fueran, se ejecutará otro texto en pantalla.<br>
> Los valores de ambos serían el siguiente, teniendo en cuenta que en el código no hay puesto ningun valor:<br>
> public String string1 = "";<br>
> public String string2 = "";
## **3. Per què no funciona l'operador == ? Quin operador s'ha d'usar en lloc d'aquest?**
>En Java solo los tipos primitivos, por ejemplo int o char, se comparan con ==, los Strings en Java se comparan entre ellos con el metodo equals.
## **4. La función2() està declarada com segueix:**
### public void funcion2() {
### System.out.println("--------------------");
### System.out.println("Aquesta és la funció 2");
### System.out.println("Com faig la crida perquè funcione????");
### } 
## **Aquesta   funció   com   l'he   de   cridar   des   del   mètode   MAIN   perquè   funcione.   Existeixen   2 possibilitats. Explica-les.**
> Desde main o psvm, lo que habría que poner sería lo siguiente:<br>
> public static void main(String[] args){ }<br>
> A continuación, tendremos que ir al   botón   derecho   del   símbolo
“play”   verde   en   el   método   main   de   la   clase   y
seleccionando Debug.<br>
> Arriba a la derecha también veremos el botón de play, al cual podremos pulsarle para que se cargue el programa