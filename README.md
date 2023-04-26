# hello-openai
ℹ️ It is an executable .exe "ready to use", and an easy way to make queries & questions (prompts) to OPENAI, from a command line interpreter (CLI) for Windows, Linux, Mac

🚀 Features

+ You can perform automation from the command line. (Powershell, Terminal, command.com, ...)
+ Use it in a script, ready to run from a task. (lots, .bat, "Windows Task Scheduler" ...)
+ You can redirect standard output to a new file ">" or ">>"
+ Programs that run commands, can now call OPENAI directly.
+ Made with love🤟in GOlang 

📋 Requirements: 

A valid APIKEY from https://platform.openai.com/account/api-keys
and set OPENAI_APIKEY Environment variable. Example on Windows Powershell, to set a enviroment variable: ``` $env:OPENAI_APIKEY = 'YOUR_API_KEY'``` 


🔧 Usage

hello-openai.exe --query="any questions or prompt"

💡 Example 1 - simple question:

``` ./hello-openai.exe --query="act as only one word response: ¿What is the capital of Spain?" ``` 
and the output is:
  Madrid.
  
💡 Example 2 - create a text table in spanish:

``` ./hello-openai.exe --query="Comportate como un simulador. Crea una tabla con 5 nombres y un apellido cada uno, con edades entre 18 y 99 años. y un numero de hijos cualquiera. Estos datos son totalmente inventados así que no sean comunes" ``` 
and the output is:
| Nombre    | Apellido   | Edad | Hijos |
|-----------|------------|------|-------|
| Yahaira   | Araujo     | 25   | 2     |
| Gaspar    | Baptiste   | 81   | 7     |
| Aram      | Costa      | 44   | 0     |
| Fausto    | Fortunato  | 64   | 4     |
| Florinda  | Vega       | 18   | 1     |

💡 Example 2 - create a text table in spanish:

``` ./hello-openai.exe --query="Comportate como un simulador. Crea una tabla con 5 nombres y un apellido cada uno, con edades entre 18 y 99 años. y un numero de hijos cualquiera. Estos datos son totalmente inventados así que no sean comunes" ``` 
💡 Example 3 - redirec output to a new file tabla.txt :

``` ./hello-openai.exe --query="crea una tabla de texto con los 10 libros más famosos del mundo" > tabla.txt
and the output is a new file tabla.txt ``` 
--------------------------------------------------------------------

* Disclaimer of responsibilities for executable:

The following executables files are provided as-is and without any warranty or guarantee of any kind, whether express or implied. The use of these executables is at your own risk, and we do not assume any responsibility for any consequences that may arise from its use.

We have taken reasonable steps to ensure that the executable is free from viruses, malware, or any other harmful components. However, we cannot guarantee that the executable is completely free from such elements, and we will not be liable for any damages or losses that may result from any virus, malware, or other harmful components that may infect your system or cause damage to your files.

We will not be responsible for any loss or damage, including without limitation, indirect or consequential loss or damage, or any loss or damage whatsoever arising from the use of this executable.

By using these executables, you acknowledge that you have read this disclaimer of responsibilities and agree to its terms.

Virus checked:  https://online620.drweb.com/cache/?i=ea26b9025f9fc4e64529e422517b7f8e
