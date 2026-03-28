FPGA VENDING MACHINE

As a project for the Digital Electronic Systems course, we have decided to make a vending machine on a NEXYS A7 board. The chosen project was one of the proposals presented by the course professors, since not having previous experience in handling FPGAs, we preferred to work with what they recommended. The project statement is as follows: "Design a soda vending machine. It accepts 10c, 20c, 50c, and 1€ coins. It only accepts the exact amount, so if more money is inserted it gives an error and "returns" all the money. When the exact amount of the soda (1€) is reached, a signal will be activated to dispense the product. It will have input signals indicating the coin, product indicator signals, and output signals for error and product." 1.2 Objectives The main purpose of the project is to design the vending machine as proposed in the statement. To achieve this, the main objectives are: - Select among several products. - Synchronize asynchronous inputs. - Detect edges and generate pulses. - Display payment information on the Display. - Count the inserted coins. - Manage errors. As an extra goal, we have decided to add: - Stock management. - A greater quantity of products to choose from, each with its individual stock. - Display on screen all the real information that an authentic vending machine would have.





SPANISH

Como trabajo de la asignatura de Sistemas Electrónicos Digitales hemos decidido 
hacer una máquina expendedora en una placa NEXYS A7. El trabajo elegido era una 
de las propuestas presentadas por los profesores de la asignatura, dado que al no 
tener experiencia previa en el manejo de las FPGA’s hemos preferido trabajar con lo 
que nos recomendaban. El enunciado del trabajo es el siguiente: 
“Diseñe una máquina expendedora de refrescos. Admite monedas de 10c, 20c, 50c y 
1€. Sólo admite el importe exacto, de forma que si introducimos dinero de más da un 
error y “devuelve” todo el dinero. Cuando se llega al importe exacto del refresco (1€) 
se activará una señal para dar el producto. Como entradas tendrá señales indicadoras 
de la moneda, señales indicadoras de producto y como salidas la señal de error y la 
de producto”.  
1.2. Objetivos 
El principal propósito del trabajo es el diseño de la máquina expendedora como se 
propone en el enunciado, para llevar esto a cabo los principales objetivos son: - Seleccionar entre varios productos. - Sincronizar entradas asíncronas. - 
Detectar flancos y generar pulsos. - Mostrar por el Display información sobre el pago. - Contar las monedas introducidas. - Gestionar los errores. 
Nosotros como objetivo extra hemos decidido añadir: - Gestión de stock. - Mayor cantidad de productos a poder elegir cada uno  
con su stock individual. - Mostrar por pantalla toda la información real que tendría  
una máquina expendedora auténtica





