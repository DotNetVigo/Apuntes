# Apuntes sobre temas hablados en el canal dotnet de VigoTech Alliance

Existe un canal de Slack en [VigoTech](https://vigotech.org/), abierto a todo el mundo, donde hablamos sobre Net.

Aquí mantendremos apuntes sobre las aportaciones de todos.


# Entorno de trabajo

Backend
- Visual Studio Profesional
	- Resharper
	- VisualSVN
	- NCrunch
- DotTrace
- DotMemory
- SQL Server Management Studio
- SQL Server Profiler
- Entity Framework Profiler

Frontend
- Visual Studio Code

Otras herramientas
- Jenkins
- SonarQube

	
## Articulos interesantes

- [Novedades de ASP.NET Core 3.0](https://www.campusmvp.es/recursos/post/novedades-de-asp-net-core-3-0.aspx)
- [Como generar IDs de la forma más rápida posible](https://www.nimaara.com/generating-ids-in-csharp/)
-  [Implementación de Array.Sort](https://ayende.com/blog/188865-C/bad-sorting-and-other-pitfalls) Curiosa la implementación de Array.Sort, en función del número de elementos a ordenar utiliza un algoritmo distinto lo que implica que pasando siempre la misma función de comparación unas veces funcione y otras de error en tiempo de ejecución.

## Herramientas útiles
- [Herramienta para pasar los csproj al nuevo formato de 2017](https://github.com/hvanbakel/CsprojToVs2017) Formato mucho más sencillo que evita conflictos en los merges.
- [Herramienta extensible para modificar los ensamblados](https://github.com/Fody/Home) Es una herramienta que ayuda a librarnos de un montón de ruido de nuestro código mediante distintos plugins, por ejemplo el plugin NullGuard nos permite definir un atributo sobre un parámetro de un método indicando que no puede ser nulo, así nos evita tener que añadir esa comprobación dentro del método. Hay otro plugin llamado Caseless para evitar tener que establecer en cada comparación de strings que deseas que no distinga mayúsculas de minúsculas... Tiene un móntón de [addons](https://github.com/Fody/Home/blob/master/pages/addins.md)

- [Proyecto Orleans](https://github.com/dotnet/orleans) Permite crear aplicaciones altamente escalables y distribuidas

## Otros
- [Newsletter de C#](https://csharpdigest.net/) Un email cada domingo con tan solo 5 enlaces.
- [Newsletter de CampusMVP](https://www.campusmvp.es/boletin/) 



