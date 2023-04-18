# hello-openai

Easy OPENAI query, from command line (CLI)
+ OPENAI_APIKEY Environment variable requirements, example on Windows Power shell: $env:OPENAI_APIKEY = 'YOUR_API_KEY'
+ from https://platform.openai.com/account/api-keys


* Example 1:
  hello-openai.exe --query="act as only one word response: ¿What is the capital of Spain?"
and the output is:
Madrid.
  
* Example 2:
  hello-openai.exe --query="Crea una tabla con 5 nombres y 1 apellidos cada uno, con edades entre 18 y 99 años. y un numero de hijos cualquiera para una simulación"

and the output is:
| Nombre   | Apellido  | Edad | Número de hijos |
|----------|-----------|------|-----------------|
| Ana      | Pérez     | 23   | 1               |
| Luis     | García    | 45   | 2               |
| Julia    | Fernández | 32   | 0               |
| Miguel   | Hernández | 60   | 3               |
| Carolina | Ortiz     | 78   | 4               |
