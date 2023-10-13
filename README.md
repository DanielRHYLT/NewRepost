# NewRepost
Pasos para crear un API web:
1.	Seleccionar crear nuevo proyecto
2.	Seleccionar la plantilla ASP.NET Core Web API en lenguaje C#
3.	Nombre con .API, solución sin .API
Configurar perfil de git local:
git config --global user.name "DanielRHYLT"
git config --global user.email 20100771@ue.edu.pe
install providers:
Scaffold-DbContext "Server=WS2300724;Database=PeruDB;Integrated Security=True;TrustServerCertificate=True" Microsoft.EntityFrameworkCore.SqlServer -OutputDir Models -Force -nopluralize
