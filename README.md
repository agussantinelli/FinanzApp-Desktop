<h1 align="center">💳 FinanzApp - Desktop</h1>

<div align="center">
    <a href="https://github.com/agussantinelli/FinanzApp-Desktop" target="_blank" style="text-decoration: none;">
        <img src="https://img.shields.io/badge/💻%20Repo%20Principal-FinanzApp-0b7285?style=for-the-badge&logo=github&logoColor=white" alt="Repo FinanzApp"/>
    </a>
    <a href="#" target="_blank" style="text-decoration: none;">
        <img src="https://img.shields.io/badge/📂%20Carpeta%20del%20Proyecto-Google%20Drive-34a853?style=for-the-badge&logo=googledrive&logoColor=white" alt="Carpeta del proyecto"/>
    </a>
</div>

<p align="center">
    <a href="https://github.com/agussantinelli" target="_blank" style="text-decoration: none;">
        <img src="https://img.shields.io/badge/👤%20Agustín%20Santinelli-agussantinelli-000000?style=for-the-badge&logo=github&logoColor=white" alt="Agus"/>
    </a>
</p>

<p align="center">
    <img src="https://img.shields.io/badge/.NET-8.0-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt=".NET Badge"/>
    <img src="https://img.shields.io/badge/Desktop-WinUI%203-0078D4?style=for-the-badge&logo=windows&logoColor=white" alt="WinUI 3 Badge"/>
    <img src="https://img.shields.io/badge/Framework-Windows%20App%20SDK-0078D4?style=for-the-badge&logo=windows&logoColor=white" alt="WinSDK Badge"/>
    <img src="https://img.shields.io/badge/DB-SQL%20Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white" alt="SQL Server Badge"/>
    <img src="https://img.shields.io/badge/ORM-EF%20Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt="EF Core Badge"/>
    <img src="https://img.shields.io/badge/Visual%20Studio-5C2D91?style=for-the-badge&logo=visual%20studio&logoColor=white" alt="Visual Studio Badge"/>
</p>

<div align="center">
  <img src="https://img.shields.io/badge/License-GPLv3-blue.svg?style=for-the-badge&logo=gnu&logoColor=white" alt="GPLv3 License"/>
</div>

<hr>

<h2>🎯 Objetivo</h2>

<p>
    <strong>FinanzApp-Desktop</strong> es una solución de <strong>gestión de activos financieros e inversiones</strong> de alto rendimiento. 
    Diseñada específicamente para Windows 11, la aplicación permite realizar un seguimiento exhaustivo de carteras de inversión (Stocks, Crypto, Bonos), calculando métricas de Profit/Loss en tiempo real y centralizando el historial transaccional en un motor robusto de SQL Server.
</p>

<h2>🚀 Características del MVP</h2>

<ul>
    <li><b>📈 Dashboard de Inversiones:</b> Resumen visual del valor total de la cartera y rendimiento porcentual.</li>
    <li><b>💸 Control Transaccional:</b> Registro detallado de compras, ventas y comisiones operativas.</li>
    <li><b>🏛️ Motor Empresarial:</b> Implementación con <b>SQL Server</b> para integridad de datos y consultas complejas.</li>
    <li><b>✨ Experiencia Windows 11:</b> Interfaz moderna utilizando materiales <i>Mica</i> y <i>Acrylic</i> nativos de WinUI 3.</li>
</ul>

<h2>🛠️ Stack Técnico y Arquitectura</h2>

<table>
    <thead>
        <tr>
            <th>Capa</th>
            <th>Tecnología / Herramienta</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td><b>Frontend (UI)</b></td>
            <td>WinUI 3 (Windows App SDK) con Win2D para gráficos.</td>
        </tr>
        <tr>
            <td><b>Lógica de Negocio</b></td>
            <td>C# 12 bajo patrón MVVM (CommunityToolkit.Mvvm).</td>
        </tr>
        <tr>
            <td><b>Acceso a Datos</b></td>
            <td>Entity Framework Core (EF Core) 8.0.</td>
        </tr>
        <tr>
            <td><b>Base de Datos</b></td>
            <td>Microsoft SQL Server (LocalDB / Express).</td>
        </tr>
    </tbody>
</table>

<h2>📂 Estructura del Proyecto</h2>

<pre><code>FinanzApp-Desktop/
├── .github/                   # Workflows de CI/CD (GitHub Actions)
├── FinanzApp.Desktop/         # Aplicación de Escritorio (WinUI 3)
│   ├── Assets/                # Iconos, imágenes y recursos visuales
│   ├── Properties/            # Perfiles de publicación y configuración
│   ├── App.xaml               # Inicio de la app y recursos globales
│   ├── MainWindow.xaml        # Ventana principal (Dashboard e Historial)
│   └── app.manifest           # Configuración de compatibilidad con Windows
├── FinanzApp.slnx             # Archivo de solución de Visual Studio
├── LICENSE                    # Licencia del proyecto (GPLv3)
└── README.md                  # Documentación y guía del usuario
</code></pre>

<hr>

<div align="center">
    <sub>FinanzApp - Seguridad y Precisión en tus Finanzas Personales</sub>
</div>
