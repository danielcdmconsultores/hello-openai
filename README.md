# hello-openai

Easy OPENAI query, from command line interpreter (CLI)

+ Requirements: OPENAI_APIKEY Environment variable. Example on Windows Powershell: $env:OPENAI_APIKEY = 'YOUR_API_KEY'
give one APIKEY from https://platform.openai.com/account/api-keys

-------------------------------------------------------------------

* Example 1 - simple question:
  hello-openai.exe --query="act as only one word response: ¿What is the capital of Spain?"
  
and the output is:
Madrid.
  
* Example 2 - create a text table:
  hello-openai.exe --query="Crea una tabla con 5 nombres y 1 apellidos cada uno, con edades entre 18 y 99 años. y un numero de hijos cualquiera para una simulación"

and the output is:
| Nombre   | Apellido  | Edad | Número de hijos |
|----------|-----------|------|-----------------|
| Ana      | Pérez     | 23   | 1               |
| Luis     | García    | 45   | 2               |
| Julia    | Fernández | 32   | 0               |
| Miguel   | Hernández | 60   | 3               |
| Carolina | Ortiz     | 78   | 4               |


* Example 3 - salida redirec output to a new file tabla.txt :
  hello-openai.exe --query="crea una tabla de texto con los 10 libros más famosos del mundo" > tabla.txt

and the output is a new file tabla.txt


--------------------------------------------------------------------
Disclaimer of responsibilities for executable:

The following executable file is provided as-is and without any warranty or guarantee of any kind, whether express or implied. The use of this executable is at your own risk, and we do not assume any responsibility for any consequences that may arise from its use.

We have taken reasonable steps to ensure that the executable is free from viruses, malware, or any other harmful components. However, we cannot guarantee that the executable is completely free from such elements, and we will not be liable for any damages or losses that may result from any virus, malware, or other harmful components that may infect your system or cause damage to your files.

We will not be responsible for any loss or damage, including without limitation, indirect or consequential loss or damage, or any loss or damage whatsoever arising from the use of this executable.

By using this executable, you acknowledge that you have read this disclaimer of responsibilities and agree to its terms.
