# Criptografar-Descriptografar-WebConfig-ConnectionStrings
Comandos para Criptografar e Descriptografar a seção ConnectionString da Web.Config em Projetos Asp.Net

## Comando

Abrir o command prompt (CMD) como administrador na pasta de instalação da framework  
  
**DIR:**  
C:\Windows\Microsoft.NET\Framework64\v4.0.30319  


**---ENCRIPT**  
aspnet_regiis.exe -pef "connectionStrings" "C:\caminho-pasta-app"


**---DECRIPT**  
aspnet_regiis.exe -pdf "connectionStrings" "C:\caminho-pasta-app" 
