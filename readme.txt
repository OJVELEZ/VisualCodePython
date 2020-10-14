1-Visual studio code ahcer click en el icono de las extensiones que es un cuadrado en el menú (view bar) de la izquierda (extensions)
2-Digitar python
	elegir el oficial de microsoft
	
3-Desde el view menú 
		command palette
		acceso rápido con ctrl-shift-p
		Digitar
			python select interpreter
		Seleccionar la version de python apropiada	

4-Comandos
	crl-shift-p -> command palette, acceso para ejecutar todos los comandos de visual studio
	crl-shift-s -> search - buscar
	crl-shift-d -> debug
	crl-shift-x -> extensions
	ctrl-k + z -> zen mode
	shift-enter > run the selected line(s) in the terminal
	ctrl-ñ -> run terminal se puede seleccionar power shell, python, git, default(cmd)
	F2 -> rename an object
	F5 -> start debugging
	F10 -> debugging continue line by line
	F11 -> debugging continue inside the method or function
	
	
5-vistas
		toggle zen mode
		view -> appearence -> zen mode 
		pantalla gigante para codificar
		salida con esc

6-Ejeucución
		hacer click derecho
			run python file in the terminal

7-REPL
		read evaluate print loop	
		interactive way to interact with python
		
		como en jupyter se puede ir ejecutarndo fragmentos y la terminal va guardando la ejecución en memoria
		
8-Formatting python code
		pip install autopep8	
		file/preferences/settings
		digitar python formatting
			buscar python formatting: Provider
				autopep8
				
		digitar formatonsave
			check format a file on save. a formatter must be...
			
		FORMATTING AUTOMATIC THE CODE WHEN YOU SAVE THE FILE :O !!!
			INDENTATION
				
9-Refactor	
		exercise 2-4
		Rename the class geometry_solver 
		select the name of the class	
			right click or F2
			
		si no esta instalado el rename
			pip install -U rope --user 
			

		Refactor extract variable
			por ejemplo: return math.pi * radius**2
			seleccionar math.pi * radius**2
				click derecho
				elegir extrac variable y refactor:
				    ans = math.pi * radius**2
					return (ans)
				
		Refactor extract method
			seleccionar multiple código
10-Debug
	open the py file to do the debug
	customize run and debug 
		create a launch.json file
			add "stopOnEntry": true
			
	It created a folder
		.vscode
		inside is the launch.json
		
		
	on the file that you want to debug, you can do it by 3 manners
		f5 
		Run/start debugging 
		green play icon on the rigth
		
		to analize line by line	
			F10
	
10-Conditional breakpoints
	Click on the left to add a breakpoint as usual
	
	Right click on the left to add a CONDITIONAL BREAKPOINT as usual
		a condition
	
	The condition can be area > 50 and widht < 20
	
	Or whe you select conditional breapoint you can choose hit count
		this is the number of times that a breakpoint line is executed
		
10-Log points
	When you right click on the left pane instead of choose conditional breakpoint choose:
		log points
		Log message for example:
			"parameters: r: {radius}"
			
		After executing you can see the log messages below on the debug console	

		Great in production  when you cannot stop the program	

	
11-Market place - extensions
	write in extensions	
		autodocstring
		select and install
		
	to use it you select for example a method
	digit """	
	select docstring
        """[summary]

        Args:
            width ([type]): [description]
            length ([type]): [description]

        Returns:
            [type]: [description]
        """	
		
	write in extensions	
	better commetnts
	select and install
	
		# * Important to make sure teacher doesn't find out about this
		# ? Not sure whether to specify using floats or decimals yet
		# ! Error checking has not been added yet, be careful with params
		# todo consider adding more volume methods
		
	everithing is customizable	

12-extension for rest 
	look for REST Client
		install
		
	puede enviar solicitudes rest directamente desde el IDE	
	puede generar el código curl!!!	
		curl --request POST --url http://httpbin.org/post --header 'content-type: application/json' --header 'user-agent: vscode-restclient' --header 'x-my-name: JoeMarini' --data '{"arg1" : "value1"}'
		
	para agregar multiples request los debe separar con ###	
	
	Puede tambien guardar la respuesta
		
		
		
		
		
	
		
	

		
		

		
		
		