* make sure you install .net framework 4.5 to run this code. using microsoft.aspnet.webapi.selfhost which run on 4.5
* issue: i encounter error "no type was found that matches the controller named"
	my mistake was: Web API controllers need to be public.
	other related issue: routeTemplate: "api/{controller}/{action}/{id}" miss api without configuration
	ApiControllers class names need to be suffixed with "Controller"
* before run test, you need to start self-host app in terminal first
