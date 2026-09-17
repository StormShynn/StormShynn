<!-- Profile README for github.com/StormShynn -->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0e75b6,100:6a11cb&height=200&section=header&text=Bui%20Hoang%20Tri%20Nghia&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Full-Stack%20.NET%20Developer&descAlignY=55&descSize=18" width="100%" alt="header" />

<a href="https://github.com/StormShynn">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=0E75B6&center=true&vCenter=true&width=760&lines=SAP+ABAP+%7C+RAP+%7C+Fiori+%2F+UI5+Developer;S%2F4HANA+Public+Cloud+%7C+On-Premise+%7C+Business+One;SAP+BTP+%7C+Integration+Suite+%7C+PI%2FPO;Full-Stack+.NET+%7C+ASP.NET+Core+%7C+Oracle+%7C+SQL+Server;Clean+core%2C+clean+code%2C+clean+commits." alt="Typing SVG" />
</a>

<br/>

<a href="https://linkedin.com/in/stormshyn"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="https://dev.to/stormshyn"><img src="https://img.shields.io/badge/DEV.to-0A0A0A?style=for-the-badge&logo=devdotto&logoColor=white" alt="Dev.to"/></a>
<a href="https://fb.com/stormshyn"><img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white" alt="Facebook"/></a>
<a href="https://instagram.com/storm_shyn"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram"/></a>
<a href="mailto:chinghia19031999@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>

<br/>

<img src="https://komarev.com/ghpvc/?username=StormShynn&label=Profile%20views&color=0e75b6&style=flat-square" alt="profile views" />
<img src="https://img.shields.io/github/followers/StormShynn?label=Followers&style=flat-square&color=0e75b6" alt="followers" />
<img src="https://img.shields.io/badge/Based%20in-Vietnam-0e75b6?style=flat-square" alt="location" />

</div>

---

## About Me

```abap
CLASS zcl_nghia DEFINITION PUBLIC FINAL CREATE PUBLIC.
  PUBLIC SECTION.
    CONSTANTS: name     TYPE string VALUE 'Bui Hoang Tri Nghia',
               alias    TYPE string VALUE 'StormShynn',
               role     TYPE string VALUE 'SAP Technical Consultant & Full-Stack Developer',
               location TYPE string VALUE 'Vietnam'.

    METHODS get_sap_stack   RETURNING VALUE(rt_stack) TYPE string_table.
    METHODS get_web_stack   RETURNING VALUE(rt_stack) TYPE string_table.
ENDCLASS.

CLASS zcl_nghia IMPLEMENTATION.
  METHOD get_sap_stack.
    rt_stack = VALUE #(
      ( |ABAP - reports, enhancements, BAdIs, CDS views, AMDP| )
      ( |RAP - behavior definitions, OData V4, managed & unmanaged scenarios| )
      ( |Fiori / SAPUI5 - custom apps, Fiori Elements, extensions| )
      ( |S/4HANA Public Cloud - clean core, released APIs, developer extensibility| )
      ( |S/4HANA On-Premise - classic ABAP, custom development| )
      ( |SAP Business One - SDK / DI API add-ons, UDF & UDO, integration| )
      ( |SAP BTP - Cloud Foundry, side-by-side extensibility| )
      ( |Integration Suite & PI/PO - iFlows, mappings, adapters| ) ).
  ENDMETHOD.

  METHOD get_web_stack.
    rt_stack = VALUE #(
      ( |ASP.NET Core & C# backend services| )
      ( |Oracle / SQL Server - PL-SQL, T-SQL, tuning| )
      ( |JavaScript, Bootstrap, responsive front-ends| )
      ( |Clean architecture & maintainable codebases| ) ).
  ENDMETHOD.
ENDCLASS.

" Motto: Write code that your future self will thank you for.
```

<table>
<tr>
<td width="50%" valign="top">

**Currently working on**

- ABAP & RAP development on S/4HANA Public Cloud and On-Premise
- Fiori / UI5 apps and Fiori Elements extensions
- Integration flows on SAP Integration Suite & PI/PO
- SAP Business One customization and add-ons

**Currently learning**

- Deeper clean-core & BTP extensibility patterns
- CI/CD for ABAP (abapGit, gCTS) and containerized .NET

</td>
<td width="50%" valign="top">

**Ask me about**

- ABAP, CDS views, AMDP, OData, RAP
- Fiori / SAPUI5, Fiori Elements, launchpad setup
- SAP integration: Integration Suite, PI/PO, IDoc, BAPI, REST
- SAP Business One SDK & DI API
- C# / .NET, Oracle, SQL Server, REST APIs

**Fun fact**

- Half of debugging is reading the error message. The other half is believing it.

</td>
</tr>
</table>

---

## Tech Stack

<div align="center">

**SAP — Core & ERP**

![SAP](https://img.shields.io/badge/SAP-0FAAFF?style=for-the-badge&logo=sap&logoColor=white)
![ABAP](https://img.shields.io/badge/ABAP-0FAAFF?style=for-the-badge&logo=sap&logoColor=white)
![RAP](https://img.shields.io/badge/RAP-0FAAFF?style=for-the-badge&logo=sap&logoColor=white)
![CDS Views](https://img.shields.io/badge/CDS%20Views-0FAAFF?style=for-the-badge&logo=sap&logoColor=white)
![S/4HANA Public Cloud](https://img.shields.io/badge/S%2F4HANA%20Public%20Cloud-0FAAFF?style=for-the-badge&logo=sap&logoColor=white)
![S/4HANA On-Premise](https://img.shields.io/badge/S%2F4HANA%20On--Premise-0FAAFF?style=for-the-badge&logo=sap&logoColor=white)
![SAP Business One](https://img.shields.io/badge/SAP%20Business%20One-0FAAFF?style=for-the-badge&logo=sap&logoColor=white)

**SAP — UX, Platform & Integration**

![SAP Fiori](https://img.shields.io/badge/SAP%20Fiori-0FAAFF?style=for-the-badge&logo=sap&logoColor=white)
![SAPUI5](https://img.shields.io/badge/SAPUI5-0FAAFF?style=for-the-badge&logo=sap&logoColor=white)
![SAP BTP](https://img.shields.io/badge/SAP%20BTP-0FAAFF?style=for-the-badge&logo=sap&logoColor=white)
![Integration Suite](https://img.shields.io/badge/Integration%20Suite-0FAAFF?style=for-the-badge&logo=sap&logoColor=white)
![SAP PI/PO](https://img.shields.io/badge/SAP%20PI%2FPO-0FAAFF?style=for-the-badge&logo=sap&logoColor=white)
![OData](https://img.shields.io/badge/OData-0FAAFF?style=for-the-badge&logo=sap&logoColor=white)

**Languages**

![ABAP](https://img.shields.io/badge/ABAP-0FAAFF?style=for-the-badge&logo=sap&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

**Frameworks & Libraries**

![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET%20Core-5C2D91?style=for-the-badge&logo=dotnet&logoColor=white)
![Entity Framework](https://img.shields.io/badge/Entity%20Framework-512BD4?style=for-the-badge&logo=nuget&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)
![jQuery](https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white)

**Databases**

![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![SAP HANA](https://img.shields.io/badge/SAP%20HANA-0FAAFF?style=for-the-badge&logo=sap&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)

**Tools & Platforms**

![Eclipse ADT](https://img.shields.io/badge/Eclipse%20ADT-2C2255?style=for-the-badge&logo=eclipseide&logoColor=white)
![SAP GUI](https://img.shields.io/badge/SAP%20GUI-0FAAFF?style=for-the-badge&logo=sap&logoColor=white)
![Business App Studio](https://img.shields.io/badge/Business%20App%20Studio-0FAAFF?style=for-the-badge&logo=sap&logoColor=white)
![Visual Studio](https://img.shields.io/badge/Visual%20Studio-5C2D91?style=for-the-badge&logo=visualstudio&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

</div>

---

## SAP Capability Map

| Layer | Platform | What I build |
|---|---|---|
| **Classic ABAP** | S/4HANA On-Premise / ECC | Reports, ALV, Smart Forms, BAdIs, user exits, BAPI, IDoc, BDC |
| **Modern ABAP** | S/4HANA | CDS views, AMDP, ABAP SQL tuning, OData V2/V4 services |
| **RAP** | S/4HANA & BTP ABAP Env. | Behavior definitions, managed / unmanaged scenarios, draft handling |
| **Clean Core** | S/4HANA Public Cloud | Released APIs, key-user & developer extensibility, side-by-side apps |
| **UX** | Fiori / SAPUI5 | Custom UI5 apps, Fiori Elements, app extensions, launchpad config |
| **Platform** | SAP BTP | Cloud Foundry services, destinations, side-by-side extension apps |
| **Integration** | Integration Suite / PI-PO | iFlows, message mapping, adapters, SAP ↔ non-SAP interfaces |
| **SME ERP** | SAP Business One | SDK / DI API add-ons, UDF & UDO, Crystal Reports, integrations |
| **Data** | HANA / Oracle / SQL Server | PL/SQL, stored procedures, query optimization, data migration |

---

## Beyond SAP — Full-Stack .NET

| Area | Stack | Notes |
|---|---|---|
| **Backend** | ASP.NET Core, C#, Entity Framework | REST APIs, clean architecture, layered services |
| **Frontend** | JavaScript, jQuery, Bootstrap | Responsive UIs, front-end ↔ API integration |
| **Data** | SQL Server, Oracle, MySQL | Relational modeling, query performance |
| **DevOps** | Git, Docker, CI/CD | Containerization & pipelines (in progress) |

---

## GitHub Analytics

<div align="center">

<img height="165" src="https://github-stats-extended.vercel.app/api?username=StormShynn&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true" alt="GitHub stats" />
<img height="165" src="https://github-stats-extended.vercel.app/api/top-langs/?username=StormShynn&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Top languages" />

<br/><br/>

<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=StormShynn&theme=tokyonight" alt="Profile details" />

<br/>

<img width="49%" src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=StormShynn&theme=tokyonight&utcOffset=7" alt="Productive time" />
<img width="49%" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=StormShynn&theme=tokyonight" alt="Stats" />

<br/><br/>

<a href="https://github.com/ryo-ma/github-profile-trophy">
  <img src="https://github-trophies.vercel.app/?username=StormShynn&theme=tokyonight&no-frame=true&no-bg=true&column=7&margin-w=8&margin-h=8" alt="trophies" />
</a>

</div>

---

## Featured Projects

| Project | Stack | What it does |
|---|---|---|
| **[cds-kb-mcp-data](https://github.com/StormShynn/cds-kb-mcp-data)** | `CDS` `MCP` | *TODO: one line on what this repo does* |
| **[sap-abap-agent](https://github.com/StormShynn/sap-abap-agent)** | `ABAP` `AI` | *TODO: one line on what this repo does* |
| **[sap-error-codex](https://github.com/StormShynn/sap-error-codex)** | `SAP` | *TODO: one line on what this repo does* |
| **[mcp-switch](https://github.com/StormShynn/mcp-switch)** | `MCP` | *TODO: one line on what this repo does* |

<div align="center">

<a href="https://github.com/stormshynn/cds-kb-mcp-data">
  <img width="49%" src="https://github-stats-extended.vercel.app/api/pin/?username=stormshynn&repo=cds-kb-mcp-data&theme=tokyonight&hide_border=true&bg_color=00000000" alt="project 1" />
</a>
<a href="https://github.com/stormshynn/sap-abap-agent">
  <img width="49%" src="https://github-stats-extended.vercel.app/api/pin/?username=stormshynn&repo=sap-abap-agent&theme=tokyonight&hide_border=true&bg_color=00000000" alt="project 2" />
</a>
<a href="https://github.com/stormshynn/sap-error-codex">
  <img width="49%" src="https://github-stats-extended.vercel.app/api/pin/?username=stormshynn&repo=sap-error-codex&theme=tokyonight&hide_border=true&bg_color=00000000" alt="project 3" />
</a>
<a href="https://github.com/stormshynn/mcp-switch">
  <img width="49%" src="https://github-stats-extended.vercel.app/api/pin/?username=stormshynn&repo=mcp-switch&theme=tokyonight&hide_border=true&bg_color=00000000" alt="project 4" />
</a>

</div>

---

<!--
  OPTIONAL - Certifications.
  Uncomment and fill in once you have the certificate IDs / Credly links.

## Certifications

| Certification | Issuer | Year |
|---|---|---|
| SAP Certified Associate - Back-End Developer, ABAP Cloud | SAP | 20XX |
| SAP Certified Associate - S/4HANA Cloud Public Edition | SAP | 20XX |
-->

<!--
  OPTIONAL - Snake contribution animation.
  Uncomment ONLY after .github/workflows/snake.yml has run successfully
  and the "output" branch exists with snake.svg in it.
  Until then the URL returns 404 and shows a broken image.
-->
<div align="center">
  <img src="https://raw.githubusercontent.com/StormShynn/StormShynn/output/snake.svg" alt="snake animation" />
</div>

<div align="center">

### *"Talk is cheap. Show me the code."* — Linus Torvalds

<br/>

From [StormShynn](https://github.com/StormShynn) — thanks for stopping by!

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:6a11cb,100:0e75b6&height=120&section=footer" width="100%" alt="footer" />

</div>
