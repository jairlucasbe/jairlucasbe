<!-- header gift -->
<img src="https://capsule-render.vercel.app/api?type=waving&height=80&color=8DE0F2" alt="footer" width="100%">

<!-- Header -->
<div align="center">
	<picture>	
		<source media="(prefers-color-scheme: dark)" srcset="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=700&pause=7000&duration=6000&color=8DE0F2&lineSpacing=10px&width=500&size=35&lines=Hello%F0%9F%91%8B%2C+I'm+Jair+Lucas">
  		<source media="(prefers-color-scheme: light)" srcset="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=700pause=7000&duration=6000&color=010A26&lineSpacing=10px&width=500&size=35&lines=Hello%F0%9F%91%8B%2C+I'm+Jair+Lucas">
  		<img alt="Hello 👋, I'm Jair Lucas">
	</picture>
</div>

<!-- Github Activity -->
<div align="center">
	<!-- last commit -->
	<picture>	
		<source media="(prefers-color-scheme: dark)" srcset="https://img.shields.io/github/last-commit/jairlucasbe/jairlucasbe?style=for-the-badge&logo=github&logoWidth=30&labelColor=025159&color=79D0F2">
  		<source media="(prefers-color-scheme: light)" srcset="https://img.shields.io/github/last-commit/jairlucasbe/jairlucasbe?style=for-the-badge&logo=github&logoWidth=30&labelColor=025159&color=038C8C">
  		<img alt="Profile Update"/> &nbsp;
	</picture>
	<!-- commit activity -->
	<picture>	
		<source media="(prefers-color-scheme: dark)" srcset="https://img.shields.io/github/commit-activity/w/jairlucasbe/jairlucasbe?style=for-the-badge&logo=github&logoWidth=30&labelColor=025159&color=79D0F2">
  		<source media="(prefers-color-scheme: light)" srcset="https://img.shields.io/github/commit-activity/w/jairlucasbe/jairlucasbe?style=for-the-badge&logo=github&logoWidth=30&labelColor=025159&color=038C8C">
  		<img alt="Profile Update"/> &nbsp;
	</picture>
	<picture>	
		<source media="(prefers-color-scheme: dark)" srcset="https://badges.pufler.dev/repos/jairlucasbe?style=for-the-badge&logo=github&logoWidth=30&labelColor=025159&color=79D0F2" alt="jairlucasbe">
  		<source media="(prefers-color-scheme: light)" srcset="https://badges.pufler.dev/repos/jairlucasbe?style=for-the-badge&logo=github&logoWidth=30&labelColor=025159&color=038C8C" alt="jairlucasbe">
  		<img alt="Profile Update"/> &nbsp;
	</picture> 
</div>

---

<!-- Presentations -->
<div>
<h2>Professional Overview</h2>
<h4>
    I'm a Systems Engineer specializing in backend development using &nbsp; <img src="https://img.shields.io/badge/java%20%20-ff0000?style=plastic&logo=openjdk&logoColor=black&logoSize=30" alt="java"> &nbsp; and the &nbsp; <img src="https://img.shields.io/badge/spring%20framework%20%20-708c30.svg?style=plastic&logo=spring&logoColor=black&logoWidth=30" alt="Spring Framework">. Currently, I am focused on security topics with &nbsp; <img src="https://img.shields.io/badge/Spring%20security-708c30?style=plastic&logo=spring-security&logoColor=black" alt="Spring security" />, &nbsp; while continuing to expand my knowledge in advanced areas such as microservices architecture and other emerging methodologies.
</h4>
</div>

<img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width="100%"><br>

<!-- Social Networks -->
<div align="center"> 
	<a href="https://www.linkedin.com/in/jair-lenin-lucas-benavides" target="_blank"><img src="https://img.shields.io/badge/linkedin-000000?style=for-the-badge&logo=linkedin&logoSize=30&logoColor=white" alt="linkedin"></a>  &nbsp; 
	<a href="mailto:jairlucasbe@gmail.com"><img src="https://img.shields.io/badge/gmail-000000?style=for-the-badge&logo=gmail&logoSize=30&logoColor=white" alt="Gmail" /></a>  &nbsp; 
	<a href="#" target="_blank"><img src="https://img.shields.io/badge/stackoverflow-000000?style=for-the-badge&logo=stackoverflow&logoSize=30&logoColor=white" alt="linkedin"></a>  &nbsp; 
	<a href="https://medium.com/@jairlucasbe" target="_blank"><img src="https://img.shields.io/badge/medium-000000?style=for-the-badge&logo=medium&logoSize=30" alt="Medium" /></a> 
</div><br>
<!-- Profile Views -->
<div align="center"> 
	<img src="https://komarev.com/ghpvc/?username=jairlucasbe&style=for-the-badge&logo=github&color=yellow" alt="Profile views"/>   
</div>

<!-- My Stack Technology -->
<h2>Stack of Technologies</h2>

<!-- Stack technology icons -->
 <div align="center">
	 <picture>
		<img height="80px" src="https://cdn.svgporn.com/logos/java.svg" alt="spring-icon"/>
	 </picture>
	 <br>
	 <picture>
		 <img height="60px" src="https://spring.io/img/projects/spring-framework.svg?v=2" alt="spring-icon"/>
	 </picture>
	 &nbsp;&nbsp;
	 <picture width="50px">
		 <img height="60px" src="https://spring.io/img/projects/spring-boot.svg" alt="spring-boot"/>
	 </picture>
	 &nbsp;&nbsp;
	 <picture width="40px">
		 <img height="60px" src="https://spring.io/img/projects/spring-data.svg" alt="spring-data"/>
	 </picture>
	 &nbsp;&nbsp;
	 <picture width="50px">
		 <img height="60px" src="https://spring.io/img/projects/spring-security.svg" alt="spring-security"/>
	 </picture>
 	
</div>


```mermaid
%%{init: {"flowchart": {"defaultRenderer": "elk"}} }%%
flowchart TB
	subgraph spring["`**Spring Framework**`"]
		direction TB
		spring-framework(["`**Spring Framework**`"])
		spring-framework === spring-data(["`**Spring Data**`"])
		spring-framework === spring-security(["`**Spring Security**`"])
		spring-framework === spring-boot(["`**Spring Boot**`"])
		spring-framework === spring-web(["`**Spring Web**`"])
	end
	
	subgraph spring_data_jpa["`**Spring Data : JPA**`"]
		direction LR
		hibernate(["`**Hibernate**  `"]) -.-> jakarta_persistence(["`Jakarta Persistence`"])
	end

	subgraph database["`**Database**`"]
		direction TB
		relational_database(["`**Relational Database**`"])
		relational_database --- mariadb[(MariaDB)]
		relational_database === mysql[("`**MySQL**`")]
		relational_database -.- postgresql[(PostgreSQL)]
	end
	
	subgraph integrante_development_environment["`**Integrated Development Environment**`"]
		direction TB
		ides(["`**IDEs**`"])
		ides -.- spring_tool_suite([Spring Tool Suite])
		ides === visual_studio_code(["`**Visual Studio Code**`"])
		ides -.- intellij_idea([Intellij IDEA])
	end

	development_tools(["`**Development Tools**`"])
	backend_development(["`**Backend Development**`"])	
	backend_development ==> development_tools
	backend_development == JAVA SE ==> spring
	development_tools ==> integrante_development_environment
	development_tools ==> git(["`**Git**`"]):::gitclass
	classDef gitclass stroke:#FFF, fill:#393939, color:#FFF
	spring-data --> spring_data_jpa
	spring_data_jpa --> database
```

 
<!-- footer gift -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=8DE0F2&height=80&section=footer" alt="footer" width="100%">

















<!-- Not Used
	<picture>
		 <img height="40px" src="https://cdn.svgporn.com/logos/postgresql.svg" alt="postgresql"/>
	 </picture>
	 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
	 <picture width="50px">
		 <img height="40px" src="https://cdn.svgporn.com/logos/mysql-icon.svg" alt="mysql"/>
	 </picture>
	 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
	 <picture width="50px">
		 <img height="40px" src="https://cdn.svgporn.com/logos/visual-studio-code.svg" alt="vsc"/>
	 </picture>
	 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
	 <picture>
		 <img height="40px" src="https://cdn.svgporn.com/logos/git-icon.svg" alt="git"/>
	 </picture>
	 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
	 <picture>
		 <img height="40px" src="https://cdn.svgporn.com/logos/intellij-idea.svg" alt="intellij"/>
	 </picture>  -->
