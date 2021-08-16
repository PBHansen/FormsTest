1) Create clean .NET Framework 4.7.2 solution
2) Install UmbracoCMS 8.15.1 from Nuget
3) Build
4) Startup solution from VS (ctrl + f5)
5) Install Umbraco, SQL CE, No starter Kit
    - Username: test@test.test
	- Password: umbraco4tw
6) Install UmbracoForms 8.7.6
7) Build and Run
8) Backoffice -> Create new form
9) Create 2 fields, both mandatory, both with a condition to hide if the other value is greather than 0


--
For some reason they are not hiding with the conditional logic, however if I fill out 1 field the site shuts down.
If I fill out both, they work.