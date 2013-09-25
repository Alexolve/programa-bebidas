se tiene una vinateria que ofrece
a)tequila
b)brandy
c)whisky
d)coñac
*donde se puede comprar de cada una solo por pieza (no cajas)
*de las opciones desplegar dos marcas
*se tienen 350 piezas de cada uno
*el usuario puede comprar 1, 2, 3 o mas articulos pero tambien puede cancelar pedido
*mostrarpor usuario cantidad a pagar
*si compra mas de 5 botellas descuento del 10%
*hacerlo ciclico para "n" usuarios
*total a pagar y numero de articulos vendidos

programa-bebidas
algoritmo bebidas
inicio
  desplegar programa de bebidas
  mostrar las opciones de cada marca
  realizar las compras deseadas 
  mostrar numero de articulos
  desplegar totales
fin

pseudocodigo bebidas
inicio
 variables
 opc, opc1, x, total,
 DR<--350, caz<--350, tor<--350, ado<--350, JB<--350, JD<--350, XO<--350,RM<--350 
 
 escribe("programa de bebidas")
 Repite
 escribe("menu")
 escribe("1.-tequila")
 escribe("2.-brandy")
 escribe("3.-whisky")
 escribe("4.-coñac")
 escribe("5.-salir")
 escribe("teclea opcion")
 lee (opc)
  caso (opc)
        opc=1
          escribe("tequila")
          escribe("1.-Don Ramon")
          escribe("2.-cazadoeres")
          escribe("3.-salir")
          escribe("teclea opcion")
          lee (opc1)
              si (opc1=1) entonces
              escribe("comprare tequila Don ramon, con un precio de $150")
              escribe("¿cuantas deseas comprar?")
              lee (x)
                 si (DR>0)y (DR<=350)entonces
                 DR<--DR-x
                 total<--x*150
                 fin (si)
                 fin (si)
          otro
              si (opc1=2)entonces
              escribe("comprare tequila cazadores, con un precio de $170")
              escribe("¿cuantas deseas comprar?")
              lee (x)
                 si (caz>0)y (caz<=350)entonces
                 caz<--caz-x
                 total<--x*170
                 fin (si)
                 fin (si)
        opc=2
            escribe("brandy")
            escribe("1.-torres10")
            escribe("2.-azteca de oro")
            escribe("3.-salir")
            escribe("teclea opcion")
            lee (opc1)
                si (opc1=1) entonces
                escribe("comprare brandy torres10, con un precio de $250")
                escribe("¿cuantas deseas comprar?")
                lee (x)
                si (tor>0)y (tor<=350)entonces
                tor<--tor-x
                total<--x*250
                fin (si)
                fin (si)
          otro
              si (opc1=2)entonces
              escribe("comprare brandy azteca de oro, con un precio de $230")
              escribe("¿cuantas deseas comprar?")
              lee (x)
                 si (ado>0)y (ado<=350)entonces
                 ado<--ado-x
                 total<--x*230
                 fin (si)
                 fin (si)
        opc=3
            escribe("whisky")
            escribe("1.-JB")
            escribe("2.-Jack Daniels")
            escribe("3.-salir")
            escribe("teclea opcion")
            lee (opc1)
                si (opc1=1) entonces
                escribe("comprare whisky JB, con un precio de $300")
                escribe("¿cuantas deseas comprar?")
                lee (x)
                si (JB>0)y (JB<=350)entonces
                JB<--JB-x
                total<--x*300
                fin (si)
                fin (si)
          otro
              si (opc1=2)entonces
              escribe("comprare whisky Jack Daniels, con un precio de $500")
              escribe("¿cuantas deseas comprar?")
              lee (x)
                 si (JD>0)y (JD<=350)entonces
                 JD<--JD-x
                 total<--x*500
                 fin (si)
                 fin (si)
       opc=4
            escribe("coñac")
            escribe("1.-XO")
            escribe("2.-Remy martin")
            escribe("3.-salir")
            escribe("teclea opcion")
            lee (opc1)
                si (opc1=1) entonces
                escribe("comprare coñac XO, con un precio de $2000")
                escribe("¿cuantas deseas comprar?")
                lee (x)
                si (XO>0)y (XO<=350)entonces
                XO<--XO-x
                total<--x*2000
                fin (si)
                fin (si)
          otro
              si (opc1=2)entonces
              escribe("comprare coñac Remy martin, con un precio de $1300")
              escribe("¿cuantas deseas comprar?")
              lee (x)
                 si (RM>0)y (RM<=350)entonces
                 RM<--RM-x
                 total<--x*1300
                 fin (si)
                 fin (si)
                  si(compra>5)entonces
                  total=compra*.10
                  pago=compra-total
 hasta (opc=5)
  fin (caso)
            escribe ("articulos vendidos:", x)
            escribe ("total a pagar:", pago)
            
  
  
  
  
  
    
  
