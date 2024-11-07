<h1>🔑 ASP.NET Core Web Application with MVC, Authentication, and Employee CRUD</h1>

<p>This project demonstrates an ASP.NET Core Web Application utilizing MVC architecture with integrated authentication. It includes features for managing employee records through **Create**, **Read**, **Update**, and **Delete** (CRUD) operations. The project also integrates **ASP.NET Core Identity** for secure authentication and connects to a **SQL Server** database for data management.</p>

<h2>📑 Table of Contents</h2>
<ul>
  <li><a href="#features">Features</a></li>
  <li><a href="#technologies">Technologies</a></li>
  <li><a href="#getting-started">Getting Started</a></li>
  <li><a href="#database-setup">Database Setup</a></li>
  <li><a href="#dependencies">Dependencies</a></li>
  <li><a href="#configuration">Configuration</a></li>
  <li><a href="#usage">Usage</a></li>
  <li><a href="#contributing">Contributing</a></li>
  <li><a href="#license">License</a></li>
</ul>

<h2 id="features">🚀 Features</h2>
<ul>
  <li>Employee CRUD operations (Create, Read, Update, Delete).</li>
  <li>Secure user authentication using ASP.NET Core Identity.</li>
  <li>Responsive and user-friendly interface using MVC architecture.</li>
  <li>Database interaction through Entity Framework Core with SQL Server.</li>
</ul>

<h2 id="technologies">🛠️ Technologies</h2>
<ul>
  <li><strong>Frontend:</strong> Razor Views, Bootstrap</li>
  <li><strong>Backend:</strong> ASP.NET Core MVC, Web API</li>
  <li><strong>ORM:</strong> Entity Framework Core (Code First)</li>
  <li><strong>Authentication:</strong> ASP.NET Core Identity</li>
  <li><strong>Database:</strong> SQL Server</li>
</ul>

<h2 id="getting-started">⚙️ Getting Started</h2>

<h3>🔧 Prerequisites</h3>
<p>Make sure you have the following installed:</p>
<ul>
  <li><a href="https://visualstudio.microsoft.com/" target="_blank">Visual Studio</a> (v2019 or later)</li>
  <li><a href="https://dotnet.microsoft.com/download" target="_blank">.NET 8.0 SDK or later</a></li>
  <li><a href="https://www.microsoft.com/en-us/sql-server/sql-server-downloads" target="_blank">SQL Server</a> (or SQL Server Express)</li>
</ul>

<h2 id="dependencies">📦 Dependencies</h2>
<p>This project requires the following NuGet packages:</p>

<p>These packages provide functionality for authentication, API integration, JSON handling, and Web API development. Install them in the NuGet Package Manager Console with:</p>
<pre><code>
Install-Package Microsoft.AspNetCore.Identity.EntityFrameworkCore -Version 8.0.0
Install-Package Microsoft.AspNetCore.Identity.UI -Version 8.0.0
Install-Package Microsoft.EntityFrameworkCore -Version 8.0.0
Install-Package Microsoft.EntityFrameworkCore.SqlServer -Version 8.0.0
Install-Package Microsoft.EntityFrameworkCore.Tools -Version 8.0.0
Install-Package Microsoft.VisualStudio.Web.CodeGeneration.Design -Version 8.0.3
</code></pre>


<h2 id="database-setup">📂 Database Setup</h2>
<ol>
  <li>Clone the repository:</li>
  <pre><code>git clone https://github.com/MdAshikur-Rahman-Ashik/ASP_CoreWebAppWith_MVC_AuthenticationEmployeeCRUD</code></pre>
  
  <li>Add the initial migration:</li>
  <pre><code>dotnet ef migrations add InitialCreate</code></pre>

  <li>Update the database:</li>
  <pre><code>dotnet ef database update</code></pre>
</ol>

<h2 id="configuration">🔧 Configuration</h2>
<h3>appsettings.json</h3>
<p>Ensure that the connection string in the <strong>appsettings.json</strong> file points to your SQL Server instance:</p>
<pre><code>
 "ConnectionStrings": {
   "con": " server=(LocalDB)\\MSSQLLocalDB; database=MyEmploygheeDB2; Trusted_Connection=true; TrustServerCertificate=true; MultipleActiveResultSets=true;"
 }
</code></pre>



<h2 id="contributing">🤝 Contributing</h2>
<p>Contributions are welcome! Please fork the repository, create a new branch, and submit a pull request.</p>

<h2 id="license">📝 License</h2>
<p>This project is licensed under the MIT License. See the <a href="LICENSE" target="_blank">LICENSE</a> file for more details.</p>

<h2>📧 Contact</h2>
<p>For any questions or suggestions, please contact:</p>
<ul>
  <li><strong>Name:</strong> Md Ashikur Rahman Ashik</li>
  <li><strong>Email:</strong> <a href="mailto:mohammadashikidb@gmail.com">mohammadashikidb@gmail.com</a></li>
</ul>




![Screenshot 1](https://github.com/user-attachments/assets/c9ab4c01-c91d-480d-a368-33f25a117bed)
![Screenshot 2](https://github.com/user-attachments/assets/a5077643-681c-40a7-9782-6ab5f1395e9e)
![Screenshot 3](https://github.com/user-attachments/assets/98b16a93-1e93-43c9-98cb-3486e81b40b4)
![Screenshot 4](https://github.com/user-attachments/assets/56fa075a-4b8f-4af4-bf99-7928e7354d98)
![Screenshot 5](https://github.com/user-attachments/assets/14888f22-850d-46c2-ba42-fb1435cc05bf)
![Screenshot 6](https://github.com/user-attachments/assets/cc72dfbd-8103-4222-bfc6-0e38e02cdde0)
![Screenshot 7](https://github.com/user-attachments/assets/62434757-6ed6-45e8-bff9-e0bfa10baf8e)
![Screenshot 8](https://github.com/user-attachments/assets/7375c760-5fac-49e9-843a-9fc1d2b616d9)
![Screenshot 9](https://github.com/user-attachments/assets/87bb1b16-5f94-4766-b0a1-a24e2b0b7f4a)
![Screenshot 10](https://github.com/user-attachments/assets/1ec65556-862e-43d8-ae52-bcd885898830)

