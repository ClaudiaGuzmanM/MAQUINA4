Eduardo Flores Guzmán 202004616-6
Claudia Guzmán Muñoz  202004546-1

Posicionarse en cada carpeta correspondiente a la entidad (las que empiezan por MV):
ejecutar 
- go mod download -------- ante todo
- make build ----------------------
- make run----------------------------
-make clean--------------------------------------
- go run Mercenarios/main.go
######################################
En caso de no funcionar Docker
----------------------------------------------------
	go mod download

--------------------------------------------------
	go run <CarpetaQueContieneMain>/main.go

------------------------------------------------
	Ejecutar en el siguiente orden
	- go run director/main.go
	- go run doshbank/main.go
	- go run nameNode/main.go
	- go run dataNode1/main.go
	- go run dataNode2/main.go
	- go run dataNode3/main.go
	- go run Mercenarios/main.go

Excusa: No supimos como ejecutar el código mediante las maquinas virtuales, así que se recomienda probarlo de manera local. Hicimos todo lo posible :c


